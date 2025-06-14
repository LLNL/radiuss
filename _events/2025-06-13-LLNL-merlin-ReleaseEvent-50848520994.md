---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/49216024?"
user: bgunnar5
date: 2025-06-13
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/releases/tag/1.13.0b1
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/bgunnar5' target='_blank'>bgunnar5</a> released <a href='https://github.com/LLNL/merlin/releases/tag/1.13.0b1' target='_blank'>1.13.0b1</a>.

<small>## [1.13.0b1]
### Added
- API documentation for Merlin's core codebase
- New `merlin database` command to interact with new database functionality
  - When running locally, SQLite will be used as the database. Otherwise your current results backend will be used
  - `merlin database info`: prints some basic information about the database
  - `merlin database get`: allows you to retrieve and print entries in the database
  - `merlin database delete`: allows you to delete entries in the database
- Added `db_scripts/` folder containing several new files all pertaining to database interaction
  - `data_models`: a module that houses dataclasses that define the format of the data that's stored in Merlin's database.
  - `db_commands`: an interface for user commands of `merlin database` to be processed
  - `merlin_db`: houses the `MerlinDatabase` class, used as the main point of contact for interactions with the database
  - `entities/`: A folder containing modules that define a structured interface for interacting with persisted data.
  - `entity_managers/`: A folder containing classes responsible for managing high-level database operations across all entities.
- Added `backends/` folder containing a new OOP way to interact with results backend databases
  - `results_backend`: houses an abstract class `ResultsBackend` that defines what every supported backend implement in Merlin
  - `redis/`: A folder containing the `RedisBackend` class that defines specific interactions with the Redis database
  - `sqlite/`: A folder containing the `SQLiteBackend` class that defines specific interactions with the SQLite database
  - `backend_factory`: houses a factory class `MerlinBackendFactory` that initializes an appropriate `ResultsBackend` instance
- Added `monitors/` folder containing a refactored, OOP approach to handling the `merlin monitor` command
  - `celery_monitor`: houses the `CeleryMonitor` class a concrete subclass of `TaskServerMonitor` for monitoring Celery task servers
  - `monitor_factory`: houses a factory class `MonitorFactory` that initializes an appropriate `TaskServerMonitor` instance
  - `monitor`: houses the `Monitor` class, used as the top-level point of interaction for the monitor command
  - `task_server_monitor`: houses the `TaskServerMonitor` ABC class, which serves as a common interface for monitoring task servers
- A new celery task called `mark_run_as_complete` that is automatically added to the task queue associated with the final step in a workflow
- Added support for Python 3.12 and 3.13
- Added additional tests for the `merlin run` and `merlin purge` commands
- Aliased types to represent different types of pytest fixtures
- New test condition `StepFinishedFilesCount` to help search for `MERLIN_FINISHED` files in output workspaces
- Added "Unit-tests" GitHub action to run the unit test suite
- Added `CeleryTaskManager` context manager to the test suite to ensure tasks are safely purged from queues if tests fail
- Added `command-tests`, `workflow-tests`, and `integration-tests` to the Makefile
- Added tests and docs for the new `merlin config` options
- Python 3.8 now requires `orderly-set==5.3.0` to avoid a bug with the deepdiff library
- New step 'Reinstall pip to avoid vendored package corruption' to CI workflow jobs that use pip
- New GitHub actions to reduce common code in CI
- COPYRIGHT file for ownership details
- New check for copyright headers in the Makefile

### Changed
- Updated the `merlin monitor` command
  - it will now attempt to restart workflows automatically if a workflow is hanging
  - it utilizes an object oriented approach in the backend now
- Celery's default settings have been updated to add:
  - `interval_max: 300` -> tasks will retry for up to 5 minutes instead of 1 minute like it previously was
  - new `broker_transport_options`:
    - `socket_timeout: 300` -> increases the socket timeout to 5 minutes instead of the default 2 minutes
    - `retry_policy: {timeout: 600}` -> sets the maximum amount of time that Celery will keep trying to connect to the broker to 10 minutes
  - `broker_connection_timeout: 60` -> establishing a connection to the broker will not timeout for an entire minute now instead of the previous 4 seconds
  - new generic backend settings:
    - `result_backend_always_retry: True` -> backend will now auto-retry on the event of recoverable exceptions
    - `result_backend_max_retries: 20` -> maximum number of retries in the event of recoverable exceptions
  - new Redis specific settings:
    - `redis_retry_on_timeout: True` -> retries read/write operations on TimeoutError to the Redis server
    - `redis_socket_connect_timeout: 300` -> 5 minute socket timeout for connections to Redis
    - `redis_socket_timeout: 300` -> 5 minute socket timeout for read/write operations to Redis
    - `redis_socket_keepalive: True` -> socket TCP keepalive to keep connections healthy to the Redis server
- The `merlin config` command:
  - Now defaults to the LaunchIT setup
  - No longer required to have configuration named `app.yaml`
  - New subcommands:
    - `create`: Creates a new configuration file
    - `update-broker`: Updates the `broker` section of the configuration file
    - `update-backend`: Updates the `results_backend` section of the configuration file
    - `use`: Point your active configuration to a new configuration file
- The `merlin server` command no longer modifies the `~/.merlin/app.yaml` file by default. Instead, it modifies the `./merlin_server/app.yaml` file.
- Dropped support for Python 3.7
- Ported all distributed tests of the integration test suite to pytest
  - There is now a `commands/` directory and a `workflows/` directory under the integration suite to house these tests
  - Removed the "Distributed-tests" GitHub action as these tests will now be run under "Integration-tests"
- Removed `e2e-distributed*` definitions from the Makefile
- Modified GitHub CI to use shared testing servers hosted by LaunchIT rather than the jackalope server
- CI to use new actions
- Copyright headers in all files
  - These now point to the LICENSE and COPYRIGHT files
  - LICENSE: Legal permissions (e.g., MIT terms)
  - COPYRIGHT: Ownership, institutional metadata
  - Make commands that change version/copyright year have been modified

### Fixed
- Running Merlin locally no longer requires an `app.yaml` configuration file
- Removed dead lgtm link
- Potential security vulnerabilities related to logging

### Deprecated
- The `--steps` argument of the `merlin monitor` command is now deprecated and will be removed in Version 1.14.0.

@lucpeterson @ryannova @doutriaux1 @woutdenolf </small><a href='https://github.com/LLNL/merlin/releases/tag/1.13.0b1' target='_blank'>View Comment</a>
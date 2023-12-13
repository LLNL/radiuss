---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-12-12
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/commit/141eaaae74d1f589d7545f1858fd293611cbb323
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> pushed to <a href='https://github.com/LLNL/maestrowf' target='_blank'>LLNL/maestrowf</a>

<small>1.1.10 Release (#432)

1.1.10 Release (#432)

* Sync up read the docs config with dev environments using poetry (#399)
* Print usage on command line when no args are provided (#404)
* Add sacct fallback to slurm adapter to improve robustness of job tracking (#405)
* Update Flurm Job State mappings for flux versions >= 0.26 (#407)
* Bump certifi from 2021.10.8 to 2022.12.7 to address security issue (#409)
* Bump cryptography from 37.0.1 to 38.0.3 to address security issue (#410)
* Add missing shbang in unscheduled scripts from lsf adapter (#411)
* Update poetry lockfile to address dependabot flagged security issues (#412)
* Fix for Dockerfile smell DL3006 (#418)
* Port Maestro documentation to mkdocs and expand coverage of features and tutorials (#403)
* Update version info to be driven from pyproject.toml exclusively, and hook up to command line (#419)
* Pin mermaid to < 10.x due to api change (#422)
* Bump lock file certifi from 2022.12.7 to 2023.7.22 to address security issue (#426)
* Refactor flux adapter to avoid using pickle to talk to flux brokers installed in external environments (#415)
   Also adds flux integration tests to exercise against real flux brokers
* Add pager functionality to status command (#420)
* Patch broken flux job cancellation (#428)
* Insulate slurm adapters from user customization of squeue and sacct output formats (#431)
   Also adds live unit and integration tests for slurm adapter

---------

Co-authored-by: Francesco Di Natale <frank.dinatale1988@gmail.com>
Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com>
Co-authored-by: Bruno P. Kinoshita <kinow@users.noreply.github.com>
Co-authored-by: Charles Doutriaux <doutriaux1@llnl.gov>
Co-authored-by: Giovanni Rosa <grosa23@yahoo.com>
Co-authored-by: Brian Gunnarson <49216024+bgunnar5@users.noreply.github.com></small>

<a href='https://github.com/LLNL/maestrowf/commit/141eaaae74d1f589d7545f1858fd293611cbb323' target='_blank'>View Commit</a>
---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/5253432?"
user: slabasan
date: 2023-05-24
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/releases/tag/v2023.1.0
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/slabasan' target='_blank'>slabasan</a> released <a href='https://github.com/LLNL/hatchet/releases/tag/v2023.1.0' target='_blank'>v2023.1.0</a>.

<small>Version 2023.1.0 is a major release.

## Notable Changes
* caliperreader: Adds support for optional additional string attributes
* caliperreader: option to use native or aliased metric names
* Changes np.float to np.float64 to account for removal of np.float in newer versions of NumPy
* caliperreader: fix duplicate dataframe rows
* Enables support for multi-indexed DataFrames in the Query Language
* Refactors Query Language for Thicket
* Add Tuple Support and a Switch to Filter Function

## Internal Updates
- Changes the textx dependency to use version < 3 with Python < 3.6 and version >= 3 with Python >= 3.6
- Adds Cython to the build-system requires list in pyproject.toml
- Refactors setuptools to fix Cython issues and be consistent with Thicket
- Adds a line to setup.py to get the hatchet.query package
- Adds GitHub Action to build and (optionally) upload wheels and sdist (#87)</small><a href='https://github.com/LLNL/hatchet/releases/tag/v2023.1.0' target='_blank'>View Comment</a>
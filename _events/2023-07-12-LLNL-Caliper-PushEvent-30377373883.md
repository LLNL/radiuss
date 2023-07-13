---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2023-07-12
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/commit/38048324471359cac00a46a7fed04eaf427b361e
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> pushed to <a href='https://github.com/LLNL/Caliper' target='_blank'>LLNL/Caliper</a>

<small>Adding uberenv support for Gitlab CI (#477)

* Added .uberenv_config.json

* Added spack CachedCMakePackage in radiuss-spack-configs for Caliper

* Added .gitmodules

* Began build-and-test.sh

* Trying to fix submodules uberenv and radiuss-spack-configs

* Successfully builds caliper in a weird directory (to be fixed)

* Initial testing works with the exception of MPI testing

* Fixed 'gcc not found' error

* Minor cleanup and option checking

* Minor updates and radiuss-spack-configs commit

* Fixed CI tests failing on Quartz

* Exclude MPI tests from Lassen

* Updated prefix generation

* Updated gitlab-ci

* lassen-build-and-test-extra

* update lassen build and test extra

* update

* update

* update

* moved build-and-test.sh to gitlab folder

* update package in radiuss-spack-configs

* update testing CI

* fix

* update

* update

* update

* added build and test for other machines

* Remove extra test requirement

* Updated CI

* Fix radiuss-shared-ci include

* Update time limits

* update time allocation

* Update reading of SPEC

* Update package and change to spack v0.19.0

* Updates to radiuss-spack-configs caliper package

* Updated ROCm include

* Adding quartz to machines

* Move include of quartz build and test

* Added extra tioga spec

* Removed quartz include

* Added build-and-test-extra for ruby, corona, and tioga

* Fix compiler availability and update to caliper package

* Fix .gitlab-ci include

* Update radiuss-spack-configs and shared-ci

* Deactivate quartz (not removing .gitlab/quartz-build-and-test.yml yet).

* Update radiuss-spack-configs to define elfutils as an external

* Deactivate job mixing clang and rocm in favor of rocmcc

* Set papi as external

* Update radiuss-spack-configs to fix mpi management

* Update radiuss spack configs to Fix formatting

* Comment job using that was mixing clang and rocm

* Fix caliper package PAPI prefix

* Update radiuss spack configs with fix for intel+gcc compiler

* on Ruby intel either needs its module, or gcc@8.x to be set

* Update radiuss spack configs with added gcc@8.5.0

* Fix gcc 8.5.0 path

* Merge radiuss-spack-configs and radiuss-shared-ci

* Enable adiak by default

* Remove MPI from adiak on lassen

* Fix GLIB_not_found on Tioga master spec

* Update compilers in radiuss-spack-configs

* Update radiuss-spack-configs with new caliper package now requiring +tests variant in CI

* Add missing +tests in extra jobs

* Update radiuss-spack-configs

* Update radiuss-spack-configs

* Delete quartz-build-and-test.yml

* Apply suggestions from code review

* Add mpi externals for 3 main compilers, update rocmcc@5.5.0 externals

* restrict mpi providers list

* Fix cray_mpich -> cray-mpich

* Adjust allocation time, remove quartz, run ruby jobs concurrently

* Fix prefix creation to avoid collitions

* Fix the fix

* Add an allocation delay to improve robustness

* Update radiuss-spack-configs to main ref

---------

Co-authored-by: Adrien M. BERNEDE <51493078+adrienbernede@users.noreply.github.com></small>

<a href='https://github.com/LLNL/Caliper/commit/38048324471359cac00a46a7fed04eaf427b361e' target='_blank'>View Commit</a>
---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2024-07-05
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/commit/3f3a48f6eb25f672089ef38cce67290e7d5ec8b6
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> pushed to <a href='https://github.com/LLNL/sundials' target='_blank'>LLNL/sundials</a>

<small>Add SuperLU_DIST to benchmark (#266)

* start adding sludist option

* select linear solver by name

* updates to build the global matrix

* attach jac function, pass user data

* fix offsets, set additional NR_Loc values

* fix neighbor global index, initial first row ptr

* add sludist code to gpu version

* fix superludist build with rocm

* move hip::device to superlu_dist target

* debugging output

* set initial step size, serialize matrix output, print matrix before solve

* update global indexing so consecutive processes own consecutive rows

* remove debugging output

* update test output

* create grid crom cart comm

* add profiling to new functions

* hip build fixes

* remove SuperLU_DIST in mpi+gpu example

* add DAE Jacobian

* update ARKODE and IDA benchmarks

* fix cmake output typo

* fix typos

* add missing return

* fix initialization warnings

* fix deduce_stage initialization

* fix sign in IDA Jacobian

* fix int64 build

* update recent changes

* fix empty string when CUDA or HIP disabled

* fix warnings with RelWithDebInfo

* add option for benchmark install path

* Update README.md

* print if SuperLU_DIST has HIP/CUDA enabled

* Apply some suggestions from code review

Co-authored-by: Cody Balos <balos1@llnl.gov>

* Apply remaining suggestions from code review

* update var name

* add new template to tarscript

---------

Co-authored-by: Balos, Cody, J <balos1@llnl.gov></small>

<a href='https://github.com/LLNL/sundials/commit/3f3a48f6eb25f672089ef38cce67290e7d5ec8b6' target='_blank'>View Commit</a>
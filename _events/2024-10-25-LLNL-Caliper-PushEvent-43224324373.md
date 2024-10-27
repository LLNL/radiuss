---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-10-25
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/commit/b7139cc10782459e54311bb94ad86086177cfb84
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> pushed to <a href='https://github.com/LLNL/Caliper' target='_blank'>LLNL/Caliper</a>

<small>Refactors topdown service to support multiple types of calculations and adds support for Sapphire Rapids (#576)

* Reimplements the IntelTopdown service to support both Haswell/Broadwell calculations and Sapphire Rapids/Emerald Rapids calculations

* Adds infrastructure to update builtin_option_specs based on features like architecture support

* Adds conditional behavior to topdown service and builtin option specs based on architecture specified at configure time

* Splits TopdownCalculator and subclasses into own files to simplify implementation

* Adds a 'disable_multiplexing' configuration to the Papi service and use that configuration in the topdown service

* Checks whether PAPI uses rdpmc on SPR in the topdown service

* Reworks SPR topdown implementation to use rdpmc-style values instead of raw counter values

* Updates option spec for SPR topdown and adds instruction comments for making new topdown calculators

* Adds a CMake flag to let users tell us if PAPI is built to use rdpmc or not

* Disables multiplexing in topdown-counters

* Adds comments describing the expected behavior of the virtual methods in TopdownCalculator</small>

<a href='https://github.com/LLNL/Caliper/commit/b7139cc10782459e54311bb94ad86086177cfb84' target='_blank'>View Commit</a>
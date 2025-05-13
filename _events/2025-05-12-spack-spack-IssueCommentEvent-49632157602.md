---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/73240730?"
user: amd-toolchain-support
date: 2025-05-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/50023
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/amd-toolchain-support' target='_blank'>amd-toolchain-support</a> commented on issue <a href='https://github.com/spack/spack/issues/50023' target='_blank'>spack/spack#50023</a>.

<small>Sorry for the delay on this but we have managed to identify the root cause of the error: when using the Scons build system, some Spack environment variables need to be managed explicitly. https://github.com/spack/spack/pull/45189 has introduced new variables which need to be added to a Scone configuration file. See https://github.com/spack/spack/pull/44054 for an example of how this was done previously. A new PR will be created to fix the issue. ...</small>

<a href='https://github.com/spack/spack/issues/50023' target='_blank'>View Comment</a>
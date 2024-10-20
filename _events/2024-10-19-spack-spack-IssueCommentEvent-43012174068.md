---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12102506?"
user: psakievich
date: 2024-10-19
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/46885
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/psakievich' target='_blank'>psakievich</a> commented on issue <a href='https://github.com/spack/spack/pull/46885' target='_blank'>spack/spack#46885</a>.

<small>Thinking about this more I think to skip concretization we'd likely need to change how develop is recognized (make it an environment property rather than a spec property). It messes with a lot of fundamental stuff though. The other option I can think of is a surgical change to the DAG. Modify specs, change hashes, but don't actually solve. ...</small>

<a href='https://github.com/spack/spack/pull/46885' target='_blank'>View Comment</a>
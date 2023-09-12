---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/80296582?"
user: kwryankrattiger
date: 2023-09-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/39939
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/kwryankrattiger' target='_blank'>kwryankrattiger</a> commented on issue <a href='https://github.com/spack/spack/pull/39939' target='_blank'>spack/spack#39939</a>.

<small>For the first point, I agree we need to investigate more. I can imagine some edge cases where it would be problematic and pipelines would fail where a spec hash left existence two weeks earlier, and was reintroduced via a reversion or something on a PR that was depending on the old cached binary. I can't think of a case where it would break develop pipelines though, but maybe you have some ideas....</small>

<a href='https://github.com/spack/spack/pull/39939' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1305080?"
user: HadrienG2
date: 2023-01-07
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34842
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/HadrienG2' target='_blank'>HadrienG2</a> commented on issue <a href='https://github.com/spack/spack/pull/34842' target='_blank'>spack/spack#34842</a>.

<small>I'm not terribly surprised. LTO violates several common developer assumptions regarding what functions get exported from the final binary, what functions can be inlined... It can be made to work, and is certainly worth it (+10-20% runtime perf is not unheard of, and the binary size benefits are unbounded), but in larger projects it's usually not plug and play....</small>

<a href='https://github.com/spack/spack/pull/34842' target='_blank'>View Comment</a>
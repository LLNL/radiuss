---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2023-05-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/37417
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/spack/spack/issues/37417' target='_blank'>spack/spack#37417</a>.

<small>Hi @eugeneswalker , turns out this was a bug in Caliper's build system. A little tricky to find since libunwind is usually a system library. I've fixed it in the Caliper git repo, but we'll need a new Caliper release or patch in spack. Meanwhile a workaround is turning off either the sampler or libunwind option - between those two I'd probably turn off libunwind first....</small>

<a href='https://github.com/spack/spack/issues/37417' target='_blank'>View Comment</a>
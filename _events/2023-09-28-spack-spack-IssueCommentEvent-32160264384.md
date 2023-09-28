---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741229?"
user: sethrj
date: 2023-09-28
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/40226
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/sethrj' target='_blank'>sethrj</a> commented on issue <a href='https://github.com/spack/spack/issues/40226' target='_blank'>spack/spack#40226</a>.

<small>@keltonhalbert I think your solution is on the right track. First, it looks like spack doesn't even have a `libcanberra` package, which is a problem if Vim requires it. We need to make that dependency clear in the recipe (and for what versions), then mark that it's only needed when the gui is enabled. ...</small>

<a href='https://github.com/spack/spack/issues/40226' target='_blank'>View Comment</a>
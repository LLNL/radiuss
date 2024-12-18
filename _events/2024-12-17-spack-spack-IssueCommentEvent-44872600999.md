---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/598250?"
user: mdorier
date: 2024-12-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47822
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/mdorier' target='_blank'>mdorier</a> commented on issue <a href='https://github.com/spack/spack/pull/47822' target='_blank'>spack/spack#47822</a>.

<small>Note that I fixed it by `apt install`-ing `unzip` in my Docker image, not by adding a dependency on the `unzip` package. I cannot exclude that `zip` provides `unzip` but the bazel build was unable to see it for some other reasons....</small>

<a href='https://github.com/spack/spack/pull/47822' target='_blank'>View Comment</a>
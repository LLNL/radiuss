---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1305167?"
user: cosmicexplorer
date: 2024-01-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/41960
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/cosmicexplorer' target='_blank'>cosmicexplorer</a> commented on issue <a href='https://github.com/spack/spack/issues/41960' target='_blank'>spack/spack#41960</a>.

<small>Hm, one more thing. Currently, there is only a single canonical spack installation, which is downloaded from a release tarball and not updated (that spack workspace is reused for all cargo invocations using the same version of `spack-rs`). This was done to avoid breakages that might occur if a package definition is updated in a breaking way without coordinating with the cargo package. However, it also means that packages like PETsc would need to ask for a `spack-rs` version bump every time they wanted to update their package definition, which isn't great....</small>

<a href='https://github.com/spack/spack/issues/41960' target='_blank'>View Comment</a>
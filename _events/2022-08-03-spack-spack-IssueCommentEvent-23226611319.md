---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/38933153?"
user: eugeneswalker
date: 2022-08-03
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31883
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/eugeneswalker' target='_blank'>eugeneswalker</a> commented on issue <a href='https://github.com/spack/spack/pull/31883' target='_blank'>spack/spack#31883</a>.

<small>I'm not sure we can replace all of the individual root specs commented out in this PR with the SDK. The reason being that we want to make sure E4S products continue to be installable individually with Spack. What do you think about adding the data-viz-sdk meta-package without uncommenting everything else? This would ensure the products continue to be installable as they would concretize individually (i.e. without the additional constraints and logic embedded in the SDK metapackage.) ...</small>

<a href='https://github.com/spack/spack/pull/31883' target='_blank'>View Comment</a>
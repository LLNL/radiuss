---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8006981?"
user: climbfuji
date: 2022-08-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31684
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/climbfuji' target='_blank'>climbfuji</a> commented on issue <a href='https://github.com/spack/spack/pull/31684' target='_blank'>spack/spack#31684</a>.

<small>> It looks like it was removed in [08e75f7](https://github.com/spack/spack/commit/08e75f7a3e02ef697a5b38a692fb0c8282bd9e7d). There are also other new features that were accidentally reverted in that commit. @renjithravindrankannath @cgmb @srekolam I think what happened was that there was a bad rebase of #31591 that pulled in a bunch of changes from develop, then those changes were undone in multiple commits like [3bc3c80](https://github.com/spack/spack/commit/3bc3c809dd7bcaea1933ae468b3a690e76a30b57). So the PR branch shows no changes, but in reality that PR undoes those changes. @alalazo what's the best thing to do here? Revert [08e75f7](https://github.com/spack/spack/commit/08e75f7a3e02ef697a5b38a692fb0c8282bd9e7d) or manually re-add the removed features?...</small>

<a href='https://github.com/spack/spack/pull/31684' target='_blank'>View Comment</a>
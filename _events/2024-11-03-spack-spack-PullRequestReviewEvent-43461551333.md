---
event_type: PullRequestReviewEvent
avatar: "https://avatars.githubusercontent.com/u/5057884?"
user: vvolkl
date: 2024-11-03
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47180#pullrequestreview-2411963414
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vvolkl' target='_blank'>vvolkl</a> <a href='https://github.com/spack/spack/pull/47180#pullrequestreview-2411963414' target='_blank'>reviewed</a> a <a href='https://github.com/spack/spack/pull/47180' target='_blank'>spack/spack pull request</a>

<small>I'm not sure we gain anything by making nlohmann-json a build dependency. An include of nlohmann json ends up in the headers of edm4hep, so my understanding is that any other package  linking against edm4hep would have to have an nlohmann-json build dependency added to the recipe. Yes, like that different version of nlohmann-json could be used, but I don't think that justifies the effort, having that be consistent across the stack sounds like a feature, not a bug....</small>

<a href='https://github.com/spack/spack/pull/47180#pullrequestreview-2411963414' target='_blank'>View Review</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/82525672?"
user: AlexanderRichert-NOAA
date: 2023-12-01
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41283
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/AlexanderRichert-NOAA' target='_blank'>AlexanderRichert-NOAA</a> commented on issue <a href='https://github.com/spack/spack/pull/41283' target='_blank'>spack/spack#41283</a>.

<small>For a number of reasons including what @climbfuji mentioned we want to avoid external packages. I'm working on checking with the Rust developers about the Intel situation. If it turns out that Rust can't be built with Intel, is there some way we could tweak the recipe to use gcc under the hood even though Spack registers the compiler as %intel? Or for that matter, is there some way to build `rust%gcc` in our Intel stack but still ensure that the rest of its dependencies are %intel (assuming that would even work, namely with openssl and any possible intel-specific functions)? The issue I've run into in the past with trying to have an individual package use, say, %gcc in an otherwise %intel stack is that Spack (understandably) tends to want to make the dependencies %gcc as well....</small>

<a href='https://github.com/spack/spack/pull/41283' target='_blank'>View Comment</a>
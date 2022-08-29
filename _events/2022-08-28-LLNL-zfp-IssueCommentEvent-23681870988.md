---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/208010?"
user: tpwrules
date: 2022-08-28
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/178
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/tpwrules' target='_blank'>tpwrules</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/178' target='_blank'>LLNL/zfp#178</a>.

<small>I did some research and very recent versions of CMake know how to handle this automatically: https://cmake.org/cmake/help/v3.24/prop_tgt/CUDA_ARCHITECTURES.html#prop_tgt:CUDA_ARCHITECTURES . I understand requiring these recent versions is not an attractive proposition but it is a reference for the proper logic in CMake which is license-compatible. I would encourage defining `CUDA_ARCHITECTURES=all` by default. Defining more architectures allows more target-specific optimizations and increased performance, defining less reduces binary size and compilation time (though neither is at all significant now compared to the big ML frameworks!). If not enough are defined users simply won't be able to use `zfp` (and current versions will act quite mysteriously)....</small>

<a href='https://github.com/LLNL/zfp/issues/178' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2023-01-25
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1430
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1430' target='_blank'>LLNL/RAJA#1430</a>.

<small>@adayton1 I just build RAJA v.2022.10.4 on rzansel with CUDA 11.2.0 and clang-ibm-14.0.5 and it works for me. Try running our build script in the top-level RAJA directory: ./scripts/lc-builds/blueos_nvcc_clang.sh 11.2.0 70 ibm-14.0.5 and then run make -j in the build directory that is created. Compare the compile and link lines with that and what you have to see what the differences are. ...</small>

<a href='https://github.com/LLNL/RAJA/issues/1430' target='_blank'>View Comment</a>
---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/60698985?"
user: zulugithub
date: 2025-04-17
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/692
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/zulugithub' target='_blank'>zulugithub</a> open issue <a href='https://github.com/LLNL/sundials/issues/692' target='_blank'>LLNL/sundials#692</a>.

<p>Programm statically linked but still needs dll to run</p><small>I'm new to cmake and to sundials. I'm following the instructions for projects that use CMake in the documentation (https://sundials.readthedocs.io/en/v7.3.0/sundials/Install_link.html#cmake-projects) but changed the last line to `target_link_libraries(myexec PUBLIC SUNDIALS::core_static SUNDIALS::cvode_static) ` and added `#define SUNDIALS_STATIC_DEFINE` to my test file (cvRocket_dns.c). The resulting .exe fails to run with a missing sundials_core.dll error.  Changing the SUNDIALSTargets.cmake in INSTALL_DIR from ...</small><a href='https://github.com/LLNL/sundials/issues/692' target='_blank'>View Comment</a>
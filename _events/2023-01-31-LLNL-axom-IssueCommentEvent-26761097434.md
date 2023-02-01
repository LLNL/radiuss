---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/112360263?"
user: tlorentz77
date: 2023-01-31
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/982
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/tlorentz77' target='_blank'>tlorentz77</a> commented on issue <a href='https://github.com/LLNL/axom/issues/982' target='_blank'>LLNL/axom#982</a>.

<small>Thank you @kennyweiss and sorry for the late feedback.  I successfully build axom based on vcpkg now, but failed to search the axom using `find_package`. It reports that there is no `camp-config.cmake` file in the direcotry. The reason is that the `PATHS` provided in file `axom-config.cmake.in` (as shown in the follow) is not compatible with `vcpkg`. In `vcpkg`, the config files of packages like `xxxx-config.cmake` are usually in directory like `xxx/share/camp`. So I think the file `axom-config.cmake.in` should be update as well if we want to call axom on Windows platform....</small>

<a href='https://github.com/LLNL/axom/issues/982' target='_blank'>View Comment</a>
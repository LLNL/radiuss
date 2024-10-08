---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-10-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4517
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4517' target='_blank'>mfem/mfem#4517</a>.

<small>You are right, tracking an issue with a CMake failure like this requires some knowledge of how CMake works. When a test like this fails, there is a log of what happened, somewhere in the CMake directories. However it is not obvious (to me) where to find the log file -- I always have to browse a bit to find the right place. However, once you find the log file, you can see the exact command that failed and how it failed. Also, I think there may be `cmake` options to tell it to print these failure logs on the standard output but I have not used this approach myself....</small>

<a href='https://github.com/mfem/mfem/issues/4517' target='_blank'>View Comment</a>
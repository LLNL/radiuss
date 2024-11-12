---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-11-12
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4582
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4582' target='_blank'>mfem/mfem#4582</a>.

<small>Hi @emorell96 , this is interesting, because `getaddrinfo` is a POSIX function, so [it is supported on Windows](https://learn.microsoft.com/en-us/windows/win32/api/ws2tcpip/nf-ws2tcpip-getaddrinfo) and should work without problems for ANSI input. Is it that you modified the host name somehow and some wide characters have got to it? Unmodified example 1 otherwise uses just localhost, so I do not understand where the problem would come from 🤔 ...</small>

<a href='https://github.com/mfem/mfem/issues/4582' target='_blank'>View Comment</a>
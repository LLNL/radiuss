---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-10-02
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/967
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/967' target='_blank'>hypre-space/hypre#967</a>.

<small>RPATH is a choice for the person linking, not a choice that `libxyz.so` can make. Since there are multiple syntaxes for rpath flags, `petsc.pc` does provide a key `ldflag_rpath` with the flag (see `pkg-config --variable=ldflag_rpath petsc`. A caller from CMake would never use that because CMake has its own way to specify using RPATH....</small>

<a href='https://github.com/hypre-space/hypre/pull/967' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-09-10
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/240
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/GLVis/glvis/issues/240' target='_blank'>GLVis/glvis#240</a>.

<small>By the way, if the problem is in building GLVis with Intel then you can probably just use `g++` to build a serial MFEM version just for use with GLVis that is also built with `g++`. Such a build of GLVis should still work fine with apps build with parallel MFEM builds with Intel compiler. The only requirement is that if you enable `MFEM_USE_GNUTLS=YES` in the parallel build, you should also enable it in the serial build....</small>

<a href='https://github.com/GLVis/glvis/issues/240' target='_blank'>View Comment</a>
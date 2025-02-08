---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/36545119?"
user: jesusbonilla
date: 2025-02-07
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1230
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/jesusbonilla' target='_blank'>jesusbonilla</a> open issue <a href='https://github.com/hypre-space/hypre/issues/1230' target='_blank'>hypre-space/hypre#1230</a>.

<p>Question on AMS and AMG exact reproducibility</p><small>We are using AMS and AMG in some CI tests. The tests solve a diffusion problem in parallel and just check that the final solution matches a reference solution. For the moment, we are not allowing for any tolerance in the comparison. They need to be equal up to the last digit. As soon as the reference solution has been generated on the same machine with the same compiler, that should be an OK test if all operations are ensured to happen in the same order. In serial, this is the case, but in parallel there are last digit variations. A possible explanation would be that parallel collectives are not performed always in the same order, e.g., the additions are performed in order of message arrival. ...</small><a href='https://github.com/hypre-space/hypre/issues/1230' target='_blank'>View Comment</a>
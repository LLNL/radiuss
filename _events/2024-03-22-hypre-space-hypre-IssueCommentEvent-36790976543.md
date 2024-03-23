---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/103888790?"
user: LiMuxing666
date: 2024-03-22
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/539
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/LiMuxing666' target='_blank'>LiMuxing666</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/539' target='_blank'>hypre-space/hypre#539</a>.

<small>It seems I've figured out my issue. I'm using AMS_PCG. After careful observation, I noticed that during the iterative solving process, there are data stored in ams_data. However, it's quite evident that I don't want to destroy the entire ams_data. After some analysis, I realized that the matrix is the part I wish to retain. Then, I need to destroy other data within the AMSsolver, but the most crucial aspect is the BoomerAmg_data within ams_data...</small>

<a href='https://github.com/hypre-space/hypre/issues/539' target='_blank'>View Comment</a>
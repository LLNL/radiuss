---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2022-10-25
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/191
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/191' target='_blank'>LLNL/zfp#191</a>.

<small>One immediate issue I see above is that zfp uses Fortran ordering, so a 4 x 4 x 2 tensor (in Fortran order) should be compressed as 4 x (4 * 2) = 4 x 8 (mx = 4, my = 8 as a 2D field).  Now, the torch tensor a2 is presumably stored in C order as 2 x 4 x 4, with `nx = size[0] = 2`, `ny = size[1] = 4`, `nz = size[2] = 4`, which then is fed to zfp as an (nx * ny) x nz = (2 * 4) x 4 = 8 x 4 tensor (mx = 8, my = 4 as a 2D field), which will have zfp form 4 x 4 blocks by grabbing the wrong parts of the tensor....</small>

<a href='https://github.com/LLNL/zfp/issues/191' target='_blank'>View Comment</a>
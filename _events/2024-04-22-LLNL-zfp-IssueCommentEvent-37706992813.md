---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10498712?"
user: S-o-T
date: 2024-04-22
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/230
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/S-o-T' target='_blank'>S-o-T</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/230' target='_blank'>LLNL/zfp#230</a>.

<small>Thanks for elaborated answer. The scenario i am interested in is compression of 2d vector field as two strided 2d scalar fields. I believe that in such scenario i am bound to either manually (de)interleave vector components into separate planes prior/after compression/decompression or to rely on zfp's internal accounting for strides. As you suggested, storing strides externally and providing them during decompression seems to be a solution, although, i would argue that deriving all the meta required to setup decompression directly from a header would be more convenient....</small>

<a href='https://github.com/LLNL/zfp/issues/230' target='_blank'>View Comment</a>
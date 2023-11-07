---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/17625866?"
user: nselliott
date: 2023-11-07
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1188
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/nselliott' target='_blank'>nselliott</a> open issue <a href='https://github.com/LLNL/conduit/issues/1188' target='_blank'>LLNL/conduit#1188</a>.

<p>AMR polytopal transformations need to support adjacent domains with different axis orientations</p><small>The `to_polytopal` functionality I added for transformations of structured AMR meshes did not include support for multiblock meshes such as those supported by SAMRAI where adjacent domains may meet at the boundary of different logical mesh blocks that have different axis orientations. For example the positive i direction of one domain may be the negative j direction of an adjacent domain....</small><a href='https://github.com/LLNL/conduit/issues/1188' target='_blank'>View Comment</a>
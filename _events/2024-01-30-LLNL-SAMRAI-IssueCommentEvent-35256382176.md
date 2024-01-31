---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17625866?"
user: nselliott
date: 2024-01-30
repo_name: LLNL/SAMRAI
html_url: https://github.com/LLNL/SAMRAI/issues/256
repo_url: https://github.com/LLNL/SAMRAI
---

<a href='https://github.com/nselliott' target='_blank'>nselliott</a> commented on issue <a href='https://github.com/LLNL/SAMRAI/issues/256' target='_blank'>LLNL/SAMRAI#256</a>.

<small>Could you try rebuilding with using `GriddingAlgorithm.cpp` from branch `bugfix/nselliott/rebalance-connector`?  This may fix all of your assertions and crashes.  `Connector` is a class that holds a distributed graph representation of adjacency and overlap relationships between patches in different PatchLevels.  The Connectors between levels 0 and 1 get built during hierarchy initialization and modified during regrids, when level 1 changes while level 0 is constant, but in the current state of the code, they get cleared when level 0 is rebalanced.  Other parts of the code will rebuild those Connectors if they can't find them, but that's not something users can rely on to happen in all cases, so I consider this a SAMRAI bug.  It looks likely to me that all of the failure modes you report here are based on those Connectors being expected but not available.  The patch I added in the branch rebuilds them immediately....</small>

<a href='https://github.com/LLNL/SAMRAI/issues/256' target='_blank'>View Comment</a>
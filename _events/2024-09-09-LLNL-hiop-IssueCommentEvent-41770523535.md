---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/314792?"
user: tepperly
date: 2024-09-09
repo_name: LLNL/hiop
html_url: https://github.com/LLNL/hiop/pull/693
repo_url: https://github.com/LLNL/hiop
---

<a href='https://github.com/tepperly' target='_blank'>tepperly</a> commented on issue <a href='https://github.com/LLNL/hiop/pull/693' target='_blank'>LLNL/hiop#693</a>.

<small>> > I thought about it some more over lunch, and I think `load_state_from_data_store()` and `save_state_to_data_store()` should take a `::axom::sidre::Group &` as it's argument rather than a `::axom::sidre::DataStore &`. The `Group` argument should specify the group where the save/load should take place from rather than it being a fixed location relative to the root `DataStore`.

<a href='https://github.com/LLNL/hiop/pull/693' target='_blank'>View Comment</a>
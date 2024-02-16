---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2024-02-15
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/pull/467
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> commented on issue <a href='https://github.com/LLNL/merlin/pull/467' target='_blank'>LLNL/merlin#467</a>.

<small>Yeah, for those monolithic environments, frozen dependencies would definitely cause problems, as Lina noted.  They are great for reproducible dev work,  and with the github ci though where you're only exercising merlin.  Maybe worth retaining non-frozen requirements with softer and more flexible bounds for the main build system and keep the second lock file for building environments with for the devs?  Maestro does this with poetry where the lock file is separate, and only really gets activated if installing with poetry, but the pip installs  get the more relaxed version.  ...</small>

<a href='https://github.com/LLNL/merlin/pull/467' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-10-13
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1345
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1345' target='_blank'>LLNL/RAJA#1345</a>.

<small>I think it depends a little on what they are for.  If it impacts the structure of data or interfaces, then I think it should only check `ENABLED`, so that we don't end up introducing ABI or API breaks between files, but for some things `ACTIVE` (or whether we're compiling *this* file for OpenMP) is a reasonable check, like for whether some templates need to be accessible in the current TU.  Does that make sense?...</small>

<a href='https://github.com/LLNL/RAJA/pull/1345' target='_blank'>View Comment</a>
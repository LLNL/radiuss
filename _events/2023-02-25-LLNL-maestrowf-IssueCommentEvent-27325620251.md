---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-02-25
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/pull/403
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> commented on issue <a href='https://github.com/LLNL/maestrowf/pull/403' target='_blank'>LLNL/maestrowf#403</a>.

<small>Alright, first pass at addressing review comments (thanks @doutriaux1 !).  And one followup there to the question on host in the batch block that's not really addressed in the docs: while it is ignored by the scheduler in come cases, maestro's script adapters currently expect it to be there and will fail on a key error when trying to pop it off.  It looks like there's no schema validation on these yet, so might be an opportunity for improvement there in a follow on pr to get early failures and better warning messages for the users....</small>

<a href='https://github.com/LLNL/maestrowf/pull/403' target='_blank'>View Comment</a>
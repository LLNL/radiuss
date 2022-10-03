---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-10-02
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/979
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/979' target='_blank'>flux-framework/flux-sched#979</a>.

<p>Pull in newer date header, add some helpers</p><small>        These should work directly as arguments to the constructor of a time_point or duration defined using a double as its storage, then let you do the conversion safely.  Something like `std::chrono::time_point<system_clock, duration<double>>(duration<double>(start))` should create the appropriate time_point.  Sadly a lot of the convenience stuff is in a newer header version, we should probably pull in the portable implementation from [date](https://github.com/HowardHinnant/date) so it's just `round<seconds>(sys_time<duration<double>>(duration<double>(start)))`, little more readable....</small><a href='https://github.com/flux-framework/flux-sched/issues/979' target='_blank'>View Comment</a>
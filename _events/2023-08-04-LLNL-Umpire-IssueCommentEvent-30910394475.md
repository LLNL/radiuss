---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-08-04
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/pull/841
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/Umpire/pull/841' target='_blank'>LLNL/Umpire#841</a>.

<small>Either `std::make_shared` or `std::make_unique` are always preferred where appropriate.  I'm not sure why using `new` there would *fail*, but it's still not recommended. The reason is for exception safety.  If you use new, and an exception is thrown in creating the shared_ptr or unique_ptr from it, then the memory is leaked or in some cases may potentially produce UB.  Using `make_*` ensures that case never happens....</small>

<a href='https://github.com/LLNL/Umpire/pull/841' target='_blank'>View Comment</a>
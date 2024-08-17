---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-08-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4453
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4453' target='_blank'>mfem/mfem#4453</a>.

<small>In any case, I think the right thing to do is to remove `using namespace std` from `isockstream.cpp`. It is a bad practice and its uses are minimized in MFEM. There are just a few `std::endl` and one `std::istringstream` 😉 ....</small>

<a href='https://github.com/mfem/mfem/pull/4453' target='_blank'>View Comment</a>
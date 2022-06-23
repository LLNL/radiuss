---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9196588?"
user: termi-official
date: 2022-06-23
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/2852
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/termi-official' target='_blank'>termi-official</a> commented on issue <a href='https://github.com/mfem/mfem/issues/2852' target='_blank'>mfem/mfem#2852</a>.

<small>Thanks for the pointers. I also realized that there are more elements in the parallel runs (and also a higher tolerance) after I posted my benchmarks, but I could not find time to update the benchmarks yet. For now I can say that building MFEM without caliper and eliminating the differences (i.e. setting the tolerances and element numbers equal) evens the runtimes for the PA runs. However, the benchmarks which I posted suggest that there is quite some amount of blocking going on in the threaded regions, which I was unable to track down for now. I will come back to this once I find more time....</small>

<a href='https://github.com/mfem/mfem/issues/2852' target='_blank'>View Comment</a>
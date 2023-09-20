---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9196588?"
user: termi-official
date: 2023-09-19
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3693
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/termi-official' target='_blank'>termi-official</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3693' target='_blank'>mfem/mfem#3693</a>.

<small>I am still having trouble to check if the implementation really works. I have now modified example 15 to manually investigate some analytical examples and the computed errors. The computed errors follow the wavefront. For the analytical solution (parabola) the indicator has a small error (about 1e-7), which is not super close to zero. I also can observe that the indicator starts to fail when the threshold gets to low. With this in mind I think this might be a precision issue, however my recent commits fail to address the just described failure of the indicator. Below the modified example for reproduction purposes....</small>

<a href='https://github.com/mfem/mfem/pull/3693' target='_blank'>View Comment</a>
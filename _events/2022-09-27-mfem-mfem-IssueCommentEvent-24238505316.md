---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2022-09-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3231
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3231' target='_blank'>mfem/mfem#3231</a>.

<small>In addition to a class derived `Coefficient`, note that there is also `ProductCoefficient`. This class has very little memory, so you could have a `FunctionCoefficient` for the function and then 400 instances of `ProductCoefficient`. The derived class sounds like the best option, but I just wanted to point out `ProductCoefficient` since it may not be clear that there are ways to combine coefficients (see also `SumCoefficient` etc.)....</small>

<a href='https://github.com/mfem/mfem/issues/3231' target='_blank'>View Comment</a>
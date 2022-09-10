---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20000517?"
user: camierjs
date: 2022-09-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3178
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/camierjs' target='_blank'>camierjs</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3178' target='_blank'>mfem/mfem#3178</a>.

<small>The line `AsConst(t)(0, 0, 0); // Fine` is in fact not that 'fine' and should trigger the `VALID_HOST` error, as it is a host read while the data has been moved to the device....</small>

<a href='https://github.com/mfem/mfem/pull/3178' target='_blank'>View Comment</a>
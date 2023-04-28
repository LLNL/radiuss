---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1781919?"
user: BenWibking
date: 2023-04-27
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/issues/1122
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/BenWibking' target='_blank'>BenWibking</a> commented on issue <a href='https://github.com/Alpine-DAV/ascent/issues/1122' target='_blank'>Alpine-DAV/ascent#1122</a>.

<small>Ok, I've traced the issue to the fact that the binning operation runs on the CPU and it attempts to dereference a device pointer, since our code sends the device-resident data to Ascent via zero-copy. This works on systems with unified memory, such as Summit and Frontier, but fails on systems without it....</small>

<a href='https://github.com/Alpine-DAV/ascent/issues/1122' target='_blank'>View Comment</a>
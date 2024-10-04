---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7058064?"
user: jfavre
date: 2024-10-03
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/issues/1329
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/jfavre' target='_blank'>jfavre</a> commented on issue <a href='https://github.com/Alpine-DAV/ascent/issues/1329' target='_blank'>Alpine-DAV/ascent#1329</a>.

<small>I guess I ran into this particular bug when attempting to validate my CUDA-enabled compilations using the provided test from  https://github.com/Alpine-DAV/ascent/pull/1370. This is a very valuable toy example, but it crashes on both of my installations (laptop with RTX CUDA 12.6) and Grace-Hopper nodes (CUDA 12.4). I managed to make the test pass by commenting out the  `device_move(data["fields/vel/values/?"])` and `device_cleanup(data["fields/vel/values/?"])` instructions. The "vel" data is not used anyway in the Ascent actions. Am curious as whether this test passes on a HIP device....</small>

<a href='https://github.com/Alpine-DAV/ascent/issues/1329' target='_blank'>View Comment</a>
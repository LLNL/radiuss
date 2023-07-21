---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/30913496?"
user: siramok
date: 2023-07-20
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/pull/1175
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/siramok' target='_blank'>siramok</a> commented on issue <a href='https://github.com/Alpine-DAV/ascent/pull/1175' target='_blank'>Alpine-DAV/ascent#1175</a>.

<small>After trying to implement some use cases, I realize that callbacks should probably be allowed to return either void or bool (as opposed to only allowing one or the other). Void for cases where you want to perform an operation (like checkpointing) and bool for cases where you want to compute something and use the result as a trigger condition. It feels a bit odd to add `return true;` to a function that doesn't compute anything only so that ascent will let it be registered as a callback....</small>

<a href='https://github.com/Alpine-DAV/ascent/pull/1175' target='_blank'>View Comment</a>
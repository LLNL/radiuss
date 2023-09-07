---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/30913496?"
user: siramok
date: 2023-09-06
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/pull/1193
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/siramok' target='_blank'>siramok</a> commented on issue <a href='https://github.com/Alpine-DAV/ascent/pull/1193' target='_blank'>Alpine-DAV/ascent#1193</a>.

<small>Just noticed that the command tests are failing on MSVC: my guess is that it's due to `touch <file_path>` not creating a file (due to `touch` not being a thing), and subsequently failing to assert that the file was created. I believe we already have a conditional compilation directive for when the arch is Windows? A possible fix would be to use the Windows equivalent for `touch <file_path>` ifdef Windows, else use the existing command....</small>

<a href='https://github.com/Alpine-DAV/ascent/pull/1193' target='_blank'>View Comment</a>
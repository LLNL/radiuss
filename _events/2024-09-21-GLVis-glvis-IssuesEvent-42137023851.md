---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-09-21
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/311
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> closed issue <a href='https://github.com/GLVis/glvis/issues/311' target='_blank'>GLVis/glvis#311</a>.

<p>Characters requiring Alt do not work</p><small>Some characters like backslash '\\' require Alt to be pressed with some keyboard layouts (with Czech it is Alt+Q). This does not work since the merge of #294 , because Alt combinations are handled separately before translation to characters. The functions handling the key presses then ignore the modifier, so it is interpreted as 'q' and closes the window instead of setting the light source 😄 ....</small><a href='https://github.com/GLVis/glvis/issues/311' target='_blank'>View Comment</a>
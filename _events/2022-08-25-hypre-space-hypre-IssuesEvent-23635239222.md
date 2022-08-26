---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3051555?"
user: pbauman
date: 2022-08-25
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/723
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/pbauman' target='_blank'>pbauman</a> open issue <a href='https://github.com/hypre-space/hypre/issues/723' target='_blank'>hypre-space/hypre#723</a>.

<p>`version` file in utilities clashes with c++ `<version>`</p><small>Newer C++ standards have a `<version>` header. Thus the `version` (bash) file in `utilities` will now collide with this. In particular, whenever dependent libraries (in this case `thrust`) `#include <version>`, either explicitly or implicitly, they are picking up the `version` file in `utilities` instead. The simplest fix is probably to rename `version` to `version.sh`, but it wasn't clear to me if the file was still used at all or not. Pinging @liruipeng @ulrikeyang @rfalgout ...</small><a href='https://github.com/hypre-space/hypre/issues/723' target='_blank'>View Comment</a>
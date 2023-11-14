---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-11-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5553
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5553' target='_blank'>flux-framework/flux-core#5553</a>.

<small>Ok, some tests were failing because `run_name="__main__"` was missing from `runpy.run_path()`. This seems to work for commands that use the `flux.util.CLIMain` decorated (though I have no idea why), but some of our commands do not use that wrapper (`flux-perilog-run.py` for example)....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5553' target='_blank'>View Comment</a>
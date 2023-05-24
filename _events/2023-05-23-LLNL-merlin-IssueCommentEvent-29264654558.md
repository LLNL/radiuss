---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/133922096?"
user: dylancliche
date: 2023-05-23
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/issues/423
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/dylancliche' target='_blank'>dylancliche</a> commented on issue <a href='https://github.com/LLNL/merlin/issues/423' target='_blank'>LLNL/merlin#423</a>.

<small>@bgunnar5: Here's an idea (no matter if we make a new variable or change the MERLIN_SPEC variables) based on @koning's idea. What if we add `spec.specfile = os.path.basename(filepath)` in the `load_specification` class method within the `merlin/spec/specification.py` file. Then either make a special variable in `merlin/study/study.py` that sets it equal to `self.original_spec.specfile` (if we want a different variable), or use it to define the MERLIN_SPEC variables such as @koning's suggestion....</small>

<a href='https://github.com/LLNL/merlin/issues/423' target='_blank'>View Comment</a>
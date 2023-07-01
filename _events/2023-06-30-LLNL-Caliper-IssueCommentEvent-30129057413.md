---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2023-06-30
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/issues/476
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/LLNL/Caliper/issues/476' target='_blank'>LLNL/Caliper#476</a>.

<small>I'm not sure the AnnotationBinding class is going to work. NVTX and RocTX have a stack like API. HPCToolkit does not - it just has start and stop. So on an exclude region, I would need to call stop on the begin marker and potentially start on the end marker if an outer level is supposed to be timed. But if I understand correctly, on_begin and on_end for my service won't even be called for an excluded region. Or am I misunderstanding something?...</small>

<a href='https://github.com/LLNL/Caliper/issues/476' target='_blank'>View Comment</a>
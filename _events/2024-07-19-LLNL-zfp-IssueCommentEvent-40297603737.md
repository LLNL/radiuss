---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-07-19
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/239
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/239' target='_blank'>LLNL/zfp#239</a>.

<small>Nothing to be fixed here--the code is correct and unary negation is perfectly defined for unsigned types.  Surely VS is just being overly cautious and giving a warning, not an error, right?  And don't be fooled by Microsoft's documentation that suggests "An unsigned value is unchanged by the unary negation operator."  That is blatantly false.  For example, `-(1u) == 0xff...fu`....</small>

<a href='https://github.com/LLNL/zfp/issues/239' target='_blank'>View Comment</a>
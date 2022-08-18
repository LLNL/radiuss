---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-08-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4504
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4504' target='_blank'>flux-framework/flux-core#4504</a>.

<small>Gotcha, that macro works but it’s a bit of a trap, because it checks the max width of a char in the compile environment’s supported locales rather than the user’s runtime locale. We should be able to get the dynamic locale with setlocale with a null argument, then if it’s  C it’s ascii, empty string and MB_CUR_MAX>1 ought to be a multi byte locale so probably utf8, or if the string contains UTF-8 or we call nl_langinfo to see if the locale’s default encoding is utf8. I so, so wish locales were easier to query, *sigh*. ...</small>

<a href='https://github.com/flux-framework/flux-core/issues/4504' target='_blank'>View Comment</a>
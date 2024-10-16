---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-10-15
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/243
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/243' target='_blank'>LLNL/zfp#243</a>.

<small>Actually, neither is correct.  The last bit plane is encoded as `1001`.  The first (leftmost) *n* = 3 bits are encoded verbatim, without any group tests, since the rightmost one-bit among all bit planes above is in the third position (bit plane `0010` just above).  Hence, after outputting the *n* = 3 bits `100`, only the MSB remains, for which we have a positive group test followed by no value bits since the rightmost bit is implicit in this case (it must be a one).  Hope that helps, and sorry for getting it wrong in the paper....</small>

<a href='https://github.com/LLNL/zfp/issues/243' target='_blank'>View Comment</a>
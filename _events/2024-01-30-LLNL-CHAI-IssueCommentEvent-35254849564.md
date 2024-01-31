---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13812544?"
user: brunner6
date: 2024-01-30
repo_name: LLNL/CHAI
html_url: https://github.com/LLNL/CHAI/issues/203
repo_url: https://github.com/LLNL/CHAI
---

<a href='https://github.com/brunner6' target='_blank'>brunner6</a> commented on issue <a href='https://github.com/LLNL/CHAI/issues/203' target='_blank'>LLNL/CHAI#203</a>.

<small>We have a pattern in our code where we do an allocation, and then need to remember to zero the array.  We've had several bugs where we haven't remember that.  Having a feature where the zeroing could happen on the device where it was allocated would have avoided that.  (In contrast to std::vector, say, which even if you tricked the allocator out, you'd still zero initialize on the host and then transfer the memory to the GPU). ...</small>

<a href='https://github.com/LLNL/CHAI/issues/203' target='_blank'>View Comment</a>
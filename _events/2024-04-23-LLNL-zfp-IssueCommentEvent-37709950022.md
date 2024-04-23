---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-04-23
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/230
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/230' target='_blank'>LLNL/zfp#230</a>.

<small>As mentioned above, one rationale is that the consumer may not want to organize the data the same way the producer does.  In fact, I cannot think of a case where the consumer, which processes the data, does not know how it wants the data to be organized.  Can you think of a scenario where it would be beneficial to have the producer dictate the data layout for the consumer?  In the case of a code processing 2D vector fields, the consumer needs to know if the data layout is `float field[ny][nx][2]` or `float field[2][ny][nx]` (or some other permutation) so it can index the multidimensional field properly.  If the code is written with one of these conventions, it will fail if the data producer mandates the other convention.  While one can write such a code using strides (e.g. `field[stride_x * x + stride_y * y + stride_c * c]` to access vector component _c_ at (_x_, _y_)), oftentimes you want to use some container class like a NumPy array whose strides are given by the container, not the data producer....</small>

<a href='https://github.com/LLNL/zfp/issues/230' target='_blank'>View Comment</a>
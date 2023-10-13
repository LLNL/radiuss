---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-10-12
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/195
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/195' target='_blank'>LLNL/zfp#195</a>.

<small>See the third bullet above.  Currently, FP16 and bfloat16 can be handled similarly to `zfp_promote_int16_to_int32`, but with the user performing the conversions (e.g., to/from `float`).  We do eventually want to add full support, but as mentioned above, we'd need to add hundreds of tests and deal with the difficulties of portably converting to/from these types that typically don't have native support, including how to deal with rounding, subnormals, NaNs, etc.  This is potentially a lot of work, especially when you consider the multiple back-ends (serial, OpenMP, CUDA, HIP, SYCL), language bindings (C, C++, Python, Fortran), multiple array dimensionalities (1D-4D), the conversion functions themselves, the actual (de)compression pipeline, plus documentation, tests, and examples for the Cartesian product of all these variants.  This is a huge undertaking that will be simplified considerably when we transition to a single (de)compression pipeline and to a common implementation across back-ends.  Unfortunately, that work will itself take some time....</small>

<a href='https://github.com/LLNL/zfp/issues/195' target='_blank'>View Comment</a>
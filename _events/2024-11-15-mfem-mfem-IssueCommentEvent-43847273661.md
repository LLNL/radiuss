---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/76020022?"
user: adam-sim-dev
date: 2024-11-15
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4562
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/adam-sim-dev' target='_blank'>adam-sim-dev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4562' target='_blank'>mfem/mfem#4562</a>.

<small>> Ok, I had a brief look at the logs from our Windows CI builds and there are just a few major sources: `kernel_reporter.hpp` and `device.cpp`. I think we should fix this directly by defining a wrapper for `getenv()`, which is [safe for reading, but just returns an old-school `char *`](https://stackoverflow.com/questions/15034723/standard-c-usage-of-getenv-and-safe-practices). So we should place maybe to `globals.cpp` something like this:...</small>

<a href='https://github.com/mfem/mfem/pull/4562' target='_blank'>View Comment</a>
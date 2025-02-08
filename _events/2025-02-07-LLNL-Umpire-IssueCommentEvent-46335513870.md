---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/105904949?"
user: Arpan3323
date: 2025-02-07
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/issues/932
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/Arpan3323' target='_blank'>Arpan3323</a> commented on issue <a href='https://github.com/LLNL/Umpire/issues/932' target='_blank'>LLNL/Umpire#932</a>.

<small>After building the project as a debug build and running my fuzz test in GDB, I have found the exact arguments for `FixedMallocPool::FixedMallocPool(const std::size_t object_bytes, const std::size_t objects_per_pool)` on which the error occurs. This should allow us to reproduce the error deterministically. Moreover, updating the fuzz test source to only supply these values to `FixedMallocPool` constructor results in a clear signal from `AddressSanitizer` as opposed to `AddressSanitizer` failing internal checks, which was the case earlier.  ...</small>

<a href='https://github.com/LLNL/Umpire/issues/932' target='_blank'>View Comment</a>
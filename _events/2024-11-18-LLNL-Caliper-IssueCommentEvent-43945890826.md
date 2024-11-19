---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-11-18
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/pull/624
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/pull/624' target='_blank'>LLNL/Caliper#624</a>.

<small>I haven't dug through the logs yet but I suspect it's because Lassen and Tioga need to run MPI jobs on a compute node via lrun / flux run, which the Caliper CI script doesn't do. It just runs an MPI program as-is since it only needs one rank. For now I'd turn off the MPI tests on Tioga/Lassen (there's a CMake switch to do it, `-DRUN_MPI_TESTS=Off`) although in the long run it would be good to handle this properly....</small>

<a href='https://github.com/LLNL/Caliper/pull/624' target='_blank'>View Comment</a>
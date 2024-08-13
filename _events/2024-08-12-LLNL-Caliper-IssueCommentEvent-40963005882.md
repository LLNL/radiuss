---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-08-12
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/issues/584
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/issues/584' target='_blank'>LLNL/Caliper#584</a>.

<small>Hi @kawechel, thanks for the report. The fundamental issue here is that Caliper's MPI interception mechanism only supports the C MPI API but not the Fortran MPI API. That's why it doesn't capture and trigger a flush at `MPI_Finalize()` as it should. It works with the programmatic configuration since in this case the program calls the flush explicitly....</small>

<a href='https://github.com/LLNL/Caliper/issues/584' target='_blank'>View Comment</a>
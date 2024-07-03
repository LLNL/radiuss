---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/635034?"
user: andrewreisner
date: 2024-07-02
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/issues/230
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/andrewreisner' target='_blank'>andrewreisner</a> commented on issue <a href='https://github.com/LLNL/Caliper/issues/230' target='_blank'>LLNL/Caliper#230</a>.

<small>@Jiang-Weibo Try adding `mpiflush` to your `CALI_SERVICES_ENABLE`.  Otherwise, I would just use the config manager fortran api and call flush before calling MPI_Finalize: https://software.llnl.gov/Caliper/FortranSupport.html#caliper-fortran-api.  It has been a couple years since I have used Caliper with fortran, so I do not recall the configuration....</small>

<a href='https://github.com/LLNL/Caliper/issues/230' target='_blank'>View Comment</a>
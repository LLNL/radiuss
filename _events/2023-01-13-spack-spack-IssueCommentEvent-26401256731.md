---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/82525672?"
user: AlexanderRichert-NOAA
date: 2023-01-13
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34577
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/AlexanderRichert-NOAA' target='_blank'>AlexanderRichert-NOAA</a> commented on issue <a href='https://github.com/spack/spack/pull/34577' target='_blank'>spack/spack#34577</a>.

<small>@skosukhin The issue is with compiling the netcdf-c library itself. It looks like the netcdf-c/package.py changes are not needed (currently investigating), but some modifications are needed for netcdf-c to build. Can you please test with the following spec? `spack install netcdf-c@4.7.4~parallel-netcdf+mpi~shared~dap ^hdf5@1.10.6+hl+mpi~shared ^zlib@1.2.11~shared` I think the issue relates to the use of static zlib. The exact error depends on which system I compile on, but comes down to undefined reference errors for zlib functions (on my personal machine, when I install that spec on a current copy of spack develop, I get "undefined reference to symbol 'inflateEnd'")....</small>

<a href='https://github.com/spack/spack/pull/34577' target='_blank'>View Comment</a>
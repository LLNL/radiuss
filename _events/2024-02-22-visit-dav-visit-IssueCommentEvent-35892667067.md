---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2024-02-22
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19337
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/19337' target='_blank'>visit-dav/visit#19337</a>.

<small>The problem isn't the compiler. its the filesystem there. That is causing timestamps on various files to not quite line up. So, some files are seen as having been modified *in the future*. Normally, parallel make is the cause of this and `-j 1` fixes. But, I tried that to no avail. The filesystem winds up causing operations in CMake's bootstrap to emit warnings. Those warnings get interpreted by CMake's bootstrapping logic as you can see here... https://github.com/Kitware/CMake/blob/1d52195b96140dab76678cfa541c540bda654b9c/Source/Checks/cm_cxx_features.cmake#L60-L63...</small>

<a href='https://github.com/visit-dav/visit/issues/19337' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/106587?"
user: dylex
date: 2022-07-28
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31618
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/dylex' target='_blank'>dylex</a> commented on issue <a href='https://github.com/spack/spack/pull/31618' target='_blank'>spack/spack#31618</a>.

<small>This also seems to break installing `gcc@7.5.0` for me, which includes a patch with url `https://gcc.gnu.org/git/?p=gcc.git;a=patch;h=2b40941d23b1570cdd90083b58fa0f66aa58c86e`. As this url has an empty path, it ends up trying to download to the stage directory itself, which fails trying to `os.remove` the stage directory with `IsADirectoryError`....</small>

<a href='https://github.com/spack/spack/pull/31618' target='_blank'>View Comment</a>
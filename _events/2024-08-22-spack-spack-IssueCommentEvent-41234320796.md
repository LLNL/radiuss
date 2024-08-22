---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/47706097?"
user: ExplorerRay
date: 2024-08-22
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/44084
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/ExplorerRay' target='_blank'>ExplorerRay</a> commented on issue <a href='https://github.com/spack/spack/issues/44084' target='_blank'>spack/spack#44084</a>.

<small>I am not sure whether my own way is recommended, but this can solve the issue. Just add some lines like the following to `var/spack/repos/builtin/packages/<pkg>/package.py`. Then run `spack module lmod refresh`, you can use `ml show <pkg>` to see whether the LD_LIBRARY_PATH is prepended. I think the disadvantage of this method might be that you need to revise all the package.py according to your condition....</small>

<a href='https://github.com/spack/spack/issues/44084' target='_blank'>View Comment</a>
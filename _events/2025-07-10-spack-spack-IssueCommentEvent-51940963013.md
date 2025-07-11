---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/49785055?"
user: flxmr
date: 2025-07-10
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47767
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/flxmr' target='_blank'>flxmr</a> commented on issue <a href='https://github.com/spack/spack/pull/47767' target='_blank'>spack/spack#47767</a>.

<small>@wdconinc possible workaround could be to add a directory in the build stage to the PYTHONPATH, put a "reeentrant" sitecustomize.py in it and do `import setuptools` there. Afterwards `import distutils` works. have done this for LLVM@14 build-script and will prepare a patch - maybe this can be adapted....</small>

<a href='https://github.com/spack/spack/pull/47767' target='_blank'>View Comment</a>
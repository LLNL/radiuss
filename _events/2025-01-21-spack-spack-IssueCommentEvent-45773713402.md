---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2025-01-21
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/44654
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/spack/spack/pull/44654' target='_blank'>spack/spack#44654</a>.

<small>I think the problem with checking for ```FI_HMEM_ROCR``` is that this AMD specific flavor of cap was introduced recently into libfabric.  But since your proposed change already uses the   ```slingshot_network``` I'm okay with the PR now.  Maybe replace the is_CrayXE with a method which just checks if fi_info --caps FI_HMEM_ROCR returns at least one provider?...</small>

<a href='https://github.com/spack/spack/pull/44654' target='_blank'>View Comment</a>
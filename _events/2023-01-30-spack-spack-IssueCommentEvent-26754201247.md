---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6527504?"
user: scottwittenburg
date: 2023-01-30
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/35213
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/scottwittenburg' target='_blank'>scottwittenburg</a> commented on issue <a href='https://github.com/spack/spack/pull/35213' target='_blank'>spack/spack#35213</a>.

<small>Pipeline generation is controlled by `share/spack/gitlab/cloud_pipelines/.gitlab-ci.yml`, and `build_systems` appears to be using the default image, defined [here](https://github.com/spack/spack/blob/227c6061e5f390e00e4e10b6fef53d32a1d1e31d/share/spack/gitlab/cloud_pipelines/.gitlab-ci.yml#L4).  You could either change that default, or you could make `build_systems` use a custom image, like some other stack do, e.g. `radius-aws`, [here](https://github.com/spack/spack/blob/227c6061e5f390e00e4e10b6fef53d32a1d1e31d/share/spack/gitlab/cloud_pipelines/.gitlab-ci.yml#L482)....</small>

<a href='https://github.com/spack/spack/pull/35213' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2024-01-06
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41894
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/41894' target='_blank'>spack/spack#41894</a>.

<small>The issue with nlohmann_json is that this upgrade would break airgapped installs (and I do see the possibly irony of wanting "web tokens" to work on airgapped systems...). Previously (0.6.0) the `json.hpp` is included in the repo and so the distribution is fully vendored. Now (0.7.0) it would try to FetchContent nlohmann_json, which would fail on airgapped systems. ...</small>

<a href='https://github.com/spack/spack/pull/41894' target='_blank'>View Comment</a>
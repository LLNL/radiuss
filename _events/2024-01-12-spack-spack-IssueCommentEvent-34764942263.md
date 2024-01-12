---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2684626?"
user: cferenba
date: 2024-01-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/42038
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/cferenba' target='_blank'>cferenba</a> commented on issue <a href='https://github.com/spack/spack/issues/42038' target='_blank'>spack/spack#42038</a>.

<small>Did a little more digging, and the difference appears to be the timestamps.  I suppose that makes sense.  If Spack is fetching a numbered version, it retrieves a single once-for-all-time tarball.  But if it's fetching a commit, it has to create a local clone and tar that up, and the local clone will have the current timestamp....</small>

<a href='https://github.com/spack/spack/issues/42038' target='_blank'>View Comment</a>
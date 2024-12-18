---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2440928?"
user: rhc54
date: 2024-12-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/48013
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/rhc54' target='_blank'>rhc54</a> commented on issue <a href='https://github.com/spack/spack/issues/48013' target='_blank'>spack/spack#48013</a>.

<small>Well, I can only reiterate what I said before. PMIx never actually used liblustre - the configure code is a leftover remnant and has been removed. So if it were me, I'd just hardware the `without-lustre` flag for earlier versions of PMIx where the option appears (I honestly don't know when it snuck into the code), leaving it off for v5.0.5 and above. Caveat: I know _nothing_ about Spack, so have no idea if you can even do it....</small>

<a href='https://github.com/spack/spack/issues/48013' target='_blank'>View Comment</a>
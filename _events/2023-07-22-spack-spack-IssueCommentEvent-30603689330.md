---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2023-07-22
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/38823
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/38823' target='_blank'>spack/spack#38823</a>.

<small>One potential reason to keep urllib3 preferred to <2 is that botocore only recently supports urllib3=2, see https://github.com/urllib3/urllib3/blob/main/docs/v2-migration-guide.rst#importerror-cannot-import-name-default_ciphers-from-urllib3utilssl_. For spack installs which use buildcaches on S3, botocore could be provided by system packages which are commonly older (and botocore isn't bootstrapped). Once urllib3=2 is installed, this seems to leave spack in a degraded state because the system botocore tries to use the spack urllib3 (at least in environments)......</small>

<a href='https://github.com/spack/spack/pull/38823' target='_blank'>View Comment</a>
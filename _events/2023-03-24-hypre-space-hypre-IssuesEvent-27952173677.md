---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/31537082?"
user: peter-zajac
date: 2023-03-24
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/870
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/peter-zajac' target='_blank'>peter-zajac</a> open issue <a href='https://github.com/hypre-space/hypre/issues/870' target='_blank'>hypre-space/hypre#870</a>.

<p>incorrect int type bug in hypre_BigHash function (on Windows)</p><small>Hello, I have found an issue with the hypre_BigHash() function in src/utilities/_hypre_utilities.h then using 64 bit integers under Windows: If HYPRE_BIGINT is defined, then 'HYPRE_BigInt' is defined as 'long long', which is the correct 64 bit int type, however, the hypre_BigHash() function uses 'hypre_ulongint' (aka 'unsigned long int') for its internal calculations, which is a 32 bit int type on Windows. In consequence, the hash may turn out to be zero even if the input is non-zero (6 is a valid example), which then triggers the hypre_assert inside the hashing function, thus causing the code to crash....</small><a href='https://github.com/hypre-space/hypre/issues/870' target='_blank'>View Comment</a>
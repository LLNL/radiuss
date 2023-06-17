---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-06-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3734
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3734' target='_blank'>mfem/mfem#3734</a>.

<small>Looking at the build log (https://download.copr.fedorainfracloud.org/results/topazus/test-review/fedora-rawhide-x86_64/06085485-mfem/builder-live.log.gz) I see that the all CMake tests in the build directory ran fine, so the library `libmfem.so.4.5.2` must be linked fine. I'm not sure if something changes when it is installed and why `rpmlint` thinks there are issues. All the errors about "undefined-non-weak-symbol" are about symbols that should be present in `libHYPRE.so.*` or `libmpi.so.*`. I don't understand then why `libHYPRE.so.*` and `libmpi.so.*` are seen as "unused-direct-shlib-dependency" by `rpmlint`....</small>

<a href='https://github.com/mfem/mfem/issues/3734' target='_blank'>View Comment</a>
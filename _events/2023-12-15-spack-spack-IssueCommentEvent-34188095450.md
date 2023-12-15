---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/71396965?"
user: simonLeary42
date: 2023-12-15
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41663
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/simonLeary42' target='_blank'>simonLeary42</a> commented on issue <a href='https://github.com/spack/spack/pull/41663' target='_blank'>spack/spack#41663</a>.

<small>In order to prevent `test_hide_implicits` from creating a module name conflict, I had to add random characters to the end of the module name. And then, I'm not exactly sure how `@pytest.mark.usefixtures` works, but when you "use a fixture" for `mock_module_filename`, it uses the same filename for all the module writer objects. So I removed `mock_module_filename` from `usefixtures` and it's now correctly using separate fake modulefiles for separate fake packages....</small>

<a href='https://github.com/spack/spack/pull/41663' target='_blank'>View Comment</a>
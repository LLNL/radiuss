---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/39388941?"
user: boomanaiden154
date: 2023-09-09
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/39346
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/boomanaiden154' target='_blank'>boomanaiden154</a> commented on issue <a href='https://github.com/spack/spack/pull/39346' target='_blank'>spack/spack#39346</a>.

<small>It looks like there's one (transient?) unit test failure in the CI related to another mock package somehow gaining license information that it shouldn't have. I'm seeing one similar failure locally when using `xdist` but can't reproduce when running the test/test-suite individually (`lib/spack/spack/test/directory_layout.py::test_yaml_directory_layout_parameters`), even with `xdist`. What's incredibly odd is that the failure happens deterministically when running all the unit tests with `xdist`. The test that is failing on CI is `lib/spack/spack/test/spec_yaml.py::test_save_dependency_spec_jsons_subset `. I did a little bit of digging and couldn't see anything obvious....</small>

<a href='https://github.com/spack/spack/pull/39346' target='_blank'>View Comment</a>
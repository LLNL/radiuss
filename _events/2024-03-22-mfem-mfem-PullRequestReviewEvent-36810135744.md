---
event_type: PullRequestReviewEvent
avatar: "https://avatars.githubusercontent.com/u/14336752?"
user: psocratis
date: 2024-03-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4113#pullrequestreview-1955731828
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/psocratis' target='_blank'>psocratis</a> <a href='https://github.com/mfem/mfem/pull/4113#pullrequestreview-1955731828' target='_blank'>reviewed</a> a <a href='https://github.com/mfem/mfem/pull/4113' target='_blank'>mfem/mfem pull request</a>

<small>Looks very good! Just a couple of small things @mlstowell . One is to add the new miniapps to the makefile and their outputs to the `make clean` command. The second is a small suggestion to fix the data range of the colormap for both the submeshes to be the same, something like `<< "autoscale off\n" << "valuerange 0 1\n"`. This way you can check visually that the functions match on the common interface. ...</small>

<a href='https://github.com/mfem/mfem/pull/4113#pullrequestreview-1955731828' target='_blank'>View Review</a>
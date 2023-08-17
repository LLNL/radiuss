---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/43390106?"
user: sbugenha
date: 2023-08-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3690
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sbugenha' target='_blank'>sbugenha</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3690' target='_blank'>mfem/mfem#3690</a>.

<small>I'll leave up to you whether to just have IDASolver derive from ODESolver and override the Step and Run functions or to include a separate DAESolver class. I personally do think it's helpful having a separate interface for implicit solvers, and I think there are other classes that could benefit from this as well. For example, I'm currently writing a NonlinearForm integrator and had to write a derived version of the NonlinearForm and NonlinearFormIntegrator classes to introduce implicit versions of the Mult and AssembleElementVector functions in those classes that take both x and x' as input arguments. ...</small>

<a href='https://github.com/mfem/mfem/pull/3690' target='_blank'>View Comment</a>
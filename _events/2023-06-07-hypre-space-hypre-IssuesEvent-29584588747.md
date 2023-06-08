---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/33505548?"
user: Mr-LiuSw
date: 2023-06-07
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/916
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/Mr-LiuSw' target='_blank'>Mr-LiuSw</a> open issue <a href='https://github.com/hypre-space/hypre/issues/916' target='_blank'>hypre-space/hypre#916</a>.

<p>How can i assembly matrix on CPU and solve it on GPU when matrix need to be frequently updated ?</p><small>For non linear Finite Element problem, stiff matrix need to be updated after every Newton Iteration. In my project, element stiff matrix will be calculated first, and accumulated be a series calls of HYRPE_IJMatrixAddToValues. According to [issue226](https://github.com/hypre-space/hypre/issues/226#issuecomment-737690225), this frequently call of HYRPE_IJMatrixAddToValues will cause performance issue because of too much cudaMemcpy....</small><a href='https://github.com/hypre-space/hypre/issues/916' target='_blank'>View Comment</a>
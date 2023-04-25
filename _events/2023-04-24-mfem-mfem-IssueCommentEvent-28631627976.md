---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/31941539?"
user: beflaming
date: 2023-04-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3603
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/beflaming' target='_blank'>beflaming</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3603' target='_blank'>mfem/mfem#3603</a>.

<small>> Hi，beflaming. I have compared results of Example 2 with the results of ABAQUS as well as with the results of the beam theory. The results are consistent with each other. Besides, the code is also verified for more general cases. The Lame constants in the code may not represent true values. You can convert the mechanical parameters by using the following codes, double lame_l=v_E/((1+v)_(1-2_v)); double lame_m=E/(2_(1+v)); if(modelspace=="planestress") lame_l=2_lame_l_lame_m/(lame_l+2*lame_m); where E is the Young's modulus and v is the Poisson's ratio....</small>

<a href='https://github.com/mfem/mfem/issues/3603' target='_blank'>View Comment</a>
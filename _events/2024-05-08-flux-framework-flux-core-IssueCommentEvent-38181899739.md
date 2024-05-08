---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-05-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5917
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5917' target='_blank'>flux-framework/flux-core#5917</a>.

<small>Ok that's interesting.  It seems like that would still be kinda hard to express with the "or" syntax, since you'd have to enumerate all the permutations.  If we had the symbolic dependencies, or some other way to group them, maybe we could enable users to say something like `--dependency=stringcountok:myensemble?count=4` to mean "after four of the jobs that are currently in the system with this label as an output have completed"?  Have to chew on that some, it might make the implementation of the symbolic dependencies a bit more expensive because you would have to actually keep the information around while the jobs are running, where normally you only need to keep a hash-table of <userid>/<string>->jobid where jobid is the most recent job with an output or set dependency....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5917' target='_blank'>View Comment</a>
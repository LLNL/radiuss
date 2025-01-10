---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/57605961?"
user: EverettGrethel
date: 2025-01-09
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/issues/449
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/EverettGrethel' target='_blank'>EverettGrethel</a> open issue <a href='https://github.com/LLNL/maestrowf/issues/449' target='_blank'>LLNL/maestrowf#449</a>.

<p>Manually restarting an experiment after job completion</p><small>Suppose I run an experiment that dispatches N jobs, each restarting as many times as specified in restart_limit and restarting using code written in the "restart" section of the YAML script. I would like to be able to also restart the experiment at any point in the future, as opposed to the automatic restart. This way, I can manually restart later on if all of the original restarts fail or if I want to run additional times beyond the specified restart_limit. The restarts would occur within the same experiment folder, as opposed to generating a new folder which occurs when running "maestro run experiment.yaml". Does such a feature exist?...</small><a href='https://github.com/LLNL/maestrowf/issues/449' target='_blank'>View Comment</a>
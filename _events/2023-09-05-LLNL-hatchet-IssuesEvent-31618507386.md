---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/28907237?"
user: ilumsden
date: 2023-09-05
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/issues/106
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/ilumsden' target='_blank'>ilumsden</a> open issue <a href='https://github.com/LLNL/hatchet/issues/106' target='_blank'>LLNL/hatchet#106</a>.

<p>update_inclusive_columns fails with AttributeError</p><small>When running `update_inclusive_columns` on various datasets with a row `MultiIndex`, the function errors with an `AttributeError`. I originally discovered this while testing profiles associated with DYAD. I've managed to reproduce using HPCToolkit data in the Hatchet unit tests, but I'm not sure if HPCToolkit is still supported due to changes in the database format. So, I've attached the Caliper file from my DYAD testing. Because of GitHub requirements, I had to convert the file to a `.txt` file. It can be converted back into a `.cali` file by just changing the file extension. The code to reproduce is simply:...</small><a href='https://github.com/LLNL/hatchet/issues/106' target='_blank'>View Comment</a>
---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/61714427?"
user: samuelpmishLLNL
date: 2022-08-12
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/795
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/samuelpmishLLNL' target='_blank'>samuelpmishLLNL</a> commented on issue <a href='https://github.com/LLNL/axom/issues/795' target='_blank'>LLNL/axom#795</a>.

<small>> Taking a look at this after @white238 brought it up earlier. FWIW, not using RDC is almost certainly part of the problem. Clearly not the whole thing since @white238 tried it and it didn't take care of it, but it can't link with separate implementation without it. I'm actually surprised it's that symbol, and not one of the ones that are marked inline despite not being defined in the header, those should all be causing breakage at least at link time if not compile time....</small>

<a href='https://github.com/LLNL/axom/issues/795' target='_blank'>View Comment</a>
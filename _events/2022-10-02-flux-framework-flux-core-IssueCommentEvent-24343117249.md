---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-10-02
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4631
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4631' target='_blank'>flux-framework/flux-core#4631</a>.

<small>Heh, I came to give a rundown and @tgamblin beat me to it.  The thing that flake8 does that's really helpful, is that it's a meta-tool.  It actually runs pylint as well as several others, and offers a common interface for enforcing or ignoring violations from any of them.  I'm strongly in favor of running at least flake8, black, and mypy or pyright (for type checks, since we're on 3.6 we might as well get real type checking) all at a pinned versions easily fetched from a requirements file or similar so we don't run into a split between local dev and CI, and can easily keep things up to date....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4631' target='_blank'>View Comment</a>
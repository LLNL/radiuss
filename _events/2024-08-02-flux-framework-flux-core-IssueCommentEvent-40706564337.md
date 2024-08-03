---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1258022?"
user: koparasy
date: 2024-08-02
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6178
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/koparasy' target='_blank'>koparasy</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6178' target='_blank'>flux-framework/flux-core#6178</a>.

<small>@grondo I am just mentioning this here cause you refer to the `memo` event. It is indeed easy to get the `uri` through the memo event but there is no support to do that through the FluxExecutorFuture (at least I couldn't think of one) as `memo` is not part of `MAIN_EVENTS` ([here](https://github.com/flux-framework/flux-core/blob/master/src/bindings/python/flux/job/event.py#L19)) and the code raises an exception [here](https://github.com/flux-framework/flux-core/blob/master/src/bindings/python/flux/job/executor.py#L391) . I have added some support for it [here](https://github.com/LLNL/AMS/blob/features/flux-bootstrap/src/AMSWorkflow/ams/ams_flux.py#L12) for my project not sure if any of it is useful for flux-core part. ...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6178' target='_blank'>View Comment</a>
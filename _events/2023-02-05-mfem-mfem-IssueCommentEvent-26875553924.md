---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-02-05
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3447
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3447' target='_blank'>mfem/mfem#3447</a>.

<small>This is a good catch. The assumption I made in https://github.com/mfem/mfem/pull/3349#discussion_r1039488255 was that all overrides of `FiniteElementCollection::FiniteElementForGeometry` will return `NULL` when there is no specific FE associated with the given `Geometry::Type`. However, this convention is not followed by all `FiniteElementCollection` sub-classes and, instead, some of them generate an error....</small>

<a href='https://github.com/mfem/mfem/pull/3447' target='_blank'>View Comment</a>
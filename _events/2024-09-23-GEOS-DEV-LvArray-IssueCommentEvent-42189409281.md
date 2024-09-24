---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/32752943?"
user: corbett5
date: 2024-09-23
repo_name: GEOS-DEV/LvArray
html_url: https://github.com/GEOS-DEV/LvArray/pull/333
repo_url: https://github.com/GEOS-DEV/LvArray
---

<a href='https://github.com/corbett5' target='_blank'>corbett5</a> commented on issue <a href='https://github.com/GEOS-DEV/LvArray/pull/333' target='_blank'>GEOS-DEV/LvArray#333</a>.

<small>I don't think we want to do this in LvArray, plus if you put it there then anytime `LvArray::internal::getArrayManager` is called call backs will be disabled even if the user wanted to enable them. I would put it somewhere high up in GEOS (perhaps directly in main? https://github.com/GEOS-DEV/GEOS/blob/f9a64bb2d1fe34eab99adc25ea1d4be822eca129/src/main/main.cpp#L35) and then remove it from `ProblemManager` https://github.com/GEOS-DEV/GEOS/blob/f9a64bb2d1fe34eab99adc25ea1d4be822eca129/src/coreComponents/mainInterface/ProblemManager.cpp#L142...</small>

<a href='https://github.com/GEOS-DEV/LvArray/pull/333' target='_blank'>View Comment</a>
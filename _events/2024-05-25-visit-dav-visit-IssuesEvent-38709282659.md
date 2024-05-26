---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2024-05-25
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19565
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> open issue <a href='https://github.com/visit-dav/visit/issues/19565' target='_blank'>visit-dav/visit#19565</a>.

<p>This is alarming...Engine and mdserver linked with DB plugin libs!</p><small>Go to build dir for engine and do a `make clean; make VERBOSE=1  >& junk.out` and then grep `junk.out` for `hdf5`. You will get hits. But, you should NOT get hits for hdf5. hdf5 is used only in a database plugin lib. If I look at a link of the `libengine_ser.dylib`, I get all the items listed below. ...</small><a href='https://github.com/visit-dav/visit/issues/19565' target='_blank'>View Comment</a>
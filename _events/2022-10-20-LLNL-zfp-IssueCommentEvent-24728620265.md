---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2022-10-20
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/190
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/190' target='_blank'>LLNL/zfp#190</a>.

<small>Never mind--as I understand CMake is not even invoked here.  Rather, the issue seems to be that Cython is not being run to generate `build/python/zfpy.c` in the first place, which appears to be an issue with the current `setup.py`.  As best I can tell, we need to add [cythonize()](https://cython.readthedocs.io/en/latest/src/userguide/source_files_and_compilation.html#basic-setup-py) and some other magic to make this work, but I'm sufficiently inexperienced with [CP]ython to tackle this without risking messing up our current `zfpy-wheels` logic....</small>

<a href='https://github.com/LLNL/zfp/issues/190' target='_blank'>View Comment</a>
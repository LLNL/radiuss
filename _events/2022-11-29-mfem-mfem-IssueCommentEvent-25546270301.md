---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2022-11-29
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3339
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3339' target='_blank'>mfem/mfem#3339</a>.

<small>I realize I also never really offered an explanation to why `clang-format` might be preferred over `astyle`. One case is that it seems like Artistic Style doesn't really seem to enforce a lot of whitespace standards around function calls, operators, reference `&` and pointer `*`, etc. leading to differences in style throughout the codebase. One particular example (no offense intended) might be [`superlu.hpp/cpp`](https://github.com/mfem/mfem/blob/master/linalg/superlu.hpp) which follows a very different whitespace syntax than a lot of the rest of the code with pointers written as `const SuperLURowLocMatrix * APtr_;` and member functions as `void Mult( const Vector & x, Vector & y ) const;`. I realize this might be a nitpicky example but in practice it makes the code less readable and it means that any added contributions can result in large `diffs` according to different whitespace styles which hurts maintainability I feel. Uniform column width limits is another benefit I see of `clang-format`....</small>

<a href='https://github.com/mfem/mfem/issues/3339' target='_blank'>View Comment</a>
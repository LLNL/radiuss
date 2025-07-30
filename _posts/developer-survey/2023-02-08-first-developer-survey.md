---
title: "Results from the 1st LLNL Developer Survey, 2022"
date: 2023-02-08"
draft: false
layout: post
description: A summary of results from the 2022 survey of LLNL developers' practices and preferences.
---

> Author Vanessa Sochat, on behalf of the RADIUSS team

With software development underpinning much of LLNL's mission-driven science, the Lab's developer community has a long history of figuring out solutions to a huge number of complex challenges. But how do we know what's working and what isn't? What tools or other support do developers need to do their best work?

That's where the RADIUSS team comes in. Our [goal]({{ site.baseurl }}/about/) to provide a common foundation for HPC software development means we need to know more about LLNL developers' practices and preferences. So we surveyed them in late 2022 to assess their happiness and needs, both for awareness and targeted action that might be pursued in the next year.

We collected the results anonymously and shared them internally. But we also wanted to publish some of this insight publicly because we're advocates for knowledge sharing and community building. And since RADIUSS products are open source, external users can benefit from improvements we make internally and push out to our publicly available projects.

This post shares highlights from the survey results and some ideas we're excited about for the future.

<br>

# About Projects

## What best describes the type(s) of software you develop at LLNL?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/type-software-developed.png)

<p class="team team-summary team-summary-large">The first thing this chart reveals is the breadth of software developed at the Lab. The next is that our primary business is science; the middle of the chart shows software types that support this. But there's also a long tail of less represented categories of software, which may be a sign of representation bias: we were able to reach out to scientific code developers, for the most part. It's important to ensure that, while the categories on the right are championed, the middle and left categories also get the attention they need to be successful.</p>

<br>

# About Developer Experience

## What is your favorite editor to use?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/favorite-editor.png)

<p class="team team-summary team-summary-large">This result is an interesting mix of the two pillars that are Vim (and nvim) and Emacs challenged by VSCode. We think the increasing popularity of VS Code can be explained by a rich plugin offering and features that make it usable on the LLNL systems (e.g., remote editing). It tells us that if we invest time in preparing VSCode developer environments (and ensure it can work in different setups) many users would appreciate or benefit this work.</p>

## Languages

We asked developers about languages- specifically those they prefer to use,

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/languages-wanted.png)

and those they use regularly. 

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/languages-used.png)


Putting these side by side is hard to parse, so we thought it would be interesting
to look at the ratio between the two. E.g., are there languages developers would prefer to use that aren't regularly used?
If we divide preference / regular use, a large number would indicate a language that isn't used a lot but would be desired.

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/languages.png)

More generally, a value greater than one indicates more people want to use a language than regularly use it, while
a value less than 1 means that people use languages they would rather not.
For the above, there was no reported use of Ruby, and three developers wanting to use it. Since we cannot divide by 0 we 
cannot use this, but we take this result to mean that we need to better ask about web development work and languages
(as Ruby is common for these frameworks).

<p class="team team-summary team-summary-large">In the end, the results are not that easy to interpret. They put forward languages that are only used by a few but do not emphasize the popularity of Python 3 and Go: a score close to 1 with many users translates a good retention of the developers.
For the most part, C++ developers are satisfied by the language (score of ~0.9) but less so than with Python.
This brings us to the case of Rust. Looking closer at the data, the situation is glaring: among 107 polled, 17 expressed a desire to use Rust!</p>

## What platforms do you regularly develop software for?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/platforms.png)

<p class="team team-summary team-summary-large">Once again, this pie chart illustrates the diversity of development environment at the lab. The small representation of "Web" and "Embedded" is likely an indication of the representation biases of this survey. Again, we wish to reach out to as many developers as possible in the future to accurately depict the LLNL software development landscape.</p>

<br>

# About Developer Happiness

We ask about happiness rather than experience, because an experience could be useful but a developer
might not be happy. From these questions, we learned that over half of our developers feel happiest when
working on open source or personal projects, and this gives us insight that further
making the process to open source software easier will provide a boost to developer
experience. We can summarize the feedback about developer happiness in the following points:

<ul>
<li>There is immense intellectual and temporal freedom to explore ideas.</li>
<li>Collaborations can be very fulfilling.</li>
<li>Switching between projects gives a wide range of experiences.</li>
<li>The work itself is meaningful, impactful, and interesting.</li>
<li>Working remotely is hugely appreciated.</li>
<li>Time to create the right solutions without being rushed is appreciated.</li>
<li>The people and resources available are excellent.</li>
<li>The opportunity to work on open source is highly valued.</li>
</ul>

<br>

# About Learning and Innovation

## What new languages or technologies are you most excited about?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/technologies-excited.png)

We have many developers excited about new languages like Rust, Julia, and Python, along with using containers (Docker)
and cloud computing.

## If you were given time to work on whatever you wanted, what would you do with it?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/more-time.png)

## What would you do if you had funding and time to refactor an existing piece of software?

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/free-time.png)

Many developers expressed desire to remove technical debt, and include better CI/CD and testing, automation, along with
expressing a desire for more consensus on versions (e.g., compilers) and then being able to remove a lot
of legacy code that only exists to support deprecated ones. Some developers pointed out they refactor
regularly, while others said they aren't interested.

<br>

# About Contribution

## How many software projects do you regularly contribute to in a given year?

We find that our developers devote most of their time to a small set of projects,
with slight variation for more or less.

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/projects-per-year.png)

<br>

# About Cloud

As we are growing as a community that uses cloud, we are interested in understanding
how teams use or want to use the cloud. 

## If cloud resources were available to you, how do you think you'd use the cloud

![]({{ site.baseurl }}/assets/img/posts/developer-survey-2022/cloud-resources.png)

<br>

## Summary and Limitations

Overall, we grouped the individual feedback we received about developing at the lab into four areas of focus:

- Skills, decision making, work management
- Day to day development issues
- Technical constraints and challenges 
- Administrative Constraints and Challenges 

We're pleased with the enthusiastic responses to our first survey, and excited to strengthen the LLNL developer community through the opportunities revealed by these results. And this is just the beginning! We plan to conduct the survey annually to see how practices, preferences, and improvements evolve over time.


> This work was performed under the auspices of the U.S. Department of Energy by Lawrence Livermore National Laboratory, LLNL-MI-844868.


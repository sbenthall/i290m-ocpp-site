Title: Assignment 1 - Approaching the PDF.js community
Date: 2013-09-16 11:00
Category: assignment1
Slug: fchasen-assign1
Tags: pdfjs
Author: Fred Chasen
Summary: My first pull request for the PDF.js Project

As a Mozilla Labs project, PDF.js is well structured for community development and I found their setup on Github was particularly welcoming to new contributors. Their Readme on Github has only a two sentence description of the project, followed immediately by larger section on Contributing. This section lays out a detailed, but concise set of rules to for coding, and a guide to their work flow. Written over two years ago by the main developers, these wiki articles form an easy script to follow for newcomers.

PDF.js has a mailing list that is mirrored and archived on [Google Groups](https://groups.google.com/group/mozilla.dev.pdf-js/topics). I scanned through the archive, which goes back to roughly 2011, and it doesn’t seem to be heavily used. Many posts for help or feature requests are of poor quality and go unanswered while most bug reporters are pointed to Github issues. There isn’t much development discussion occurring on the list, though the main developers occasionally use it to make announcements, such as work priorities or big launches. One recent announcement asked for help tackling 20 font rendering bugs. I hope to work on a few of these once I am more familiar with the code-base.

In that email the two main developers mentioned they are “happy to get you started or offer advice” on IRC, but it was quiet during my initial visits. Additionally, two weekly conference calls are held, a Bug Triage on Mondays and an Engineering call on Thursdays. I lurked on a recent Bug call, which moved very quickly. I couldn’t really follow much other than that there seems to be multiple bug trackers, but that bugs eventually land in Github issues.

Luckily, I didn’t need to be a part of that discussion to get a sense of good bugs to start with. They have marked around 10 bugs as “[Good Beginner Bugs](https://github.com/mozilla/pdf.js/issues?direction=desc&labels=5-good-beginner-bug&page=1&sort=created&state=open)” on the Github issues page and there seems to be active and encouraging discussion around them. I picked [an issue](https://github.com/mozilla/pdf.js/issues/2784) that seemed to be within my ability to get done, and forked the repo.   

One developer had began work on the issue around half a year ago, but the discussion on his pull request reveled the issue was more complicated then it appeared to be at first. I am currently trying to finish a few of the complications of the bug, which implements a new UI toggle. I hope to be finished soon and will update this post once I have a pull request submitted.

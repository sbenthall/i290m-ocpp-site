Title: React community
Date: 2013-10-04 2:37
Category: assignment2
Slug: matnel-assign2
Tags: i290m-ocpp
Author: Matti
Summary: React and basic history

## Background

[Reactjs](http://facebook.github.io/react/) is an user interface library (and related tools) licenced under the Apache Licence. It is a newcommer in the field, relased May 2013 (based on [GitHub stats](https://github.com/facebook/react/graphs/contributors)). They explain the purpose of the project in [an early blog post](http://facebook.github.io/react/blog/2013/06/05/why-react.html), which highlights technical aspects of the contribution. This was also indicated as the first response given by the project team over IRC:

> matnel: btw, what is the reason react has been open sourced originally?
> @vjeux: matnel: because it's a good technology that people outside of fb can use

However, further exploration of the topic (circa 40 lines of comments over 40 mins) highlighted other attributes also:

- improve team motivation in Facebook
- increase level of documentation and robustness of the library
- pr value and potential to hire capable peple
- contributions from outside, both in terms of code and questions

The reasons are clearly driven by practical functions, however there are certain ideological motives also ("releasing good technology"). As this is a company driven effort, it is interesting to estimate the utility of practical functions to a corporation; especially as building an open source community is time consuming task. The intervieew observed this in a positive tone of voice:

> @vjeux: it requires quite some time to open source a project, but I think the result is worth it

## Community

Measuring size of the community is a non-trivial task. In GitHub there are 2205 stargazers, 172 watchers and 245 forks. This indicates a general interest towards the React platform, and a large number of people have done their own copies of the code (forked). GitHub lists 36 contributors to the code total (differnet number than their manual contributors lists). As we can from figure see, majority of the contributions are small (note: lograthimic scale). Put differently, over 99 % of the code changes originate from top 10 programmers, and of these 9 are originating from Facebook.

![](./content/assignment2/react-contributors-log.png "")

Recarding other kinds of community metrics, the IRC channel has around 40 persons on it.

## Contribution!

A was able to move fast and make my first contribution to the project. [React Maps](https://github.com/matnel/react-maps) is a higher level component to all mapping needs of the project. I developed it based on IRC discussion about the difficulty to have a mapping set up in React (it requires a bit of source code trickery), and aim to develop this further as a code example and a tutorial chapter for the React documentation. I was also contacted about adding this to [React Pages](https://github.com/facebook/react-page/), and I try to push this forward.
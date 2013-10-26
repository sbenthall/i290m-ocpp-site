Title: PeerLibrary's governance and policies
Date: 2013-10-26 13:05
Category: assignment4
Slug: matnel-assign4
Tags: react
Author: Matti
Summary: All developers are equal, but some are more equal than others: Governance and React

### Formal rules

React lacks of a formal visible organization structure to make decisions, their [contribution guideline](https://github.com/facebook/react/blob/master/CONTRIBUTING.md) explains that pull request are handled by the core team, namely those who have push access to the GitHub account. Furthermore, for Facebook employees there is a separate access, making them more first class citizens:

> Other changesets will come via a bridge with Facebook's internal source control. This is a necessity as it allows engineers at Facebook outside of the core team to move fast and contribute from an environment they are comfortable in.

Even while from open source perspective there are certain issues, such as every now and then discussed "Internal APIs" there's also another aspect on this: Facebook is using React in production. However in ICR this relation is opened in more comments

> once it gets accepted internally, i will put it out
> cool, accepted the internal diff w/ comments
> still waiting on somebody to review it internally

### Practices of the community

I examined the email discussions for words that might indicate governance

* decision
* governance
* internal (13 matches, however these are like React internals, not Facebook internal)
* proposal (6 matches)
* comments (5 matches, non relevant)
* comment (6 matches, non relevant)

 Seems that *proposals* are mostly Facebook originating, but community engaged to discussions on those - however the discussion seems to be <= 5 messages; where as the contribution base in total is circa 40 messages. There are even a proposal which have [no responses from the community](https://groups.google.com/forum/#!searchin/reactjs/rfc/reactjs/5fKxvSBhOpk/f_0PfRw4LFAJ). Examining the IRC log via grep did not bring up any extra light on this; however more detailed conversation analysis might be needed.

 #### Conclusion: a committee?

 As a conclusion, it seems that there is a council of some kind inside Facebook making the final calls; however in the discussion it is only referenced as "the internal." Future discussion with the public core members could support examination of this more.
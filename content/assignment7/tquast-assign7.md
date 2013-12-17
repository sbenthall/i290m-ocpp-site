Title: Assignment 7 - Thoughts about hypothes.is
Date: 2013-12-10 11:59
Category: assignment7
Slug: tquast-assign7
Tags: i290m-ocpp, hypothes.is, assign7, tquast
Author: tomnar
Summary: Final thoughts about Hypothes.is, its community and my contributions.

##The project's community and its technical modularity##
Hypothes.is' community consists mainly of developers (See [assignment 2](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/tquast-assign2.html)). The community is technical and professional about the tool and its usage, in other words [Conway's Law](http://www.melconway.com/research/committees.html) is at full play here. The tool fits the needs and wishes of the community very well, because the community is an active part of creating the tool. How this changes when Hypothes.is enters the open beta phase is hard to say, but a change in the community will unquestionably occur. 

Technically Hypothes.is' modularity is high, as it builds on top of several other open source projects. The main project worth mentioning here is [Annotator](https://github.com/okfn/annotator) which is used for the annotation functionality. Other projects used are for example the [Dom-text-mapper](https://github.com/csillag/dom-text-mapper) for DOM parsing and interpretation or [vagrant](https://github.com/samrose/vagrant_ubuntu_h) for the development environment. A full list of modules can be found on their [Github page](https://github.com/hypothesis) or in the [install instructions](https://github.com/hypothesis/h/blob/develop/INSTALL.rst).

##The collaboration structure##
Most of the core-team of Hypothes.is is located in the Bay Area, with a few living in other countries. Hypothes.is has its own office space in San Francisco and enough desk space for people me meet physically to work. However, physical meetups are rare. Most communication happens over mail or ad hoc via IRC. The internal structure is defined through a combination of Github and mails. People claim areas they are working on and branch them into the main tool after review. 

##How does it get work done?##
People at Hypothes.is work independently. This does not mean that there is no communication or collaboration, but the relatively small [core-team](http://hypothes.is/who/) of six people makes it possible to work with a minimalistic structure. They have worked together for months and are aware of their roles in the community. Whenever new code is ready it is submitted to review and the others review it. Thereby everyone knows where the tool is heading and has a good understanding of what people work on.

##My contribution to Hypothes.is##
Throughout the last four months I have worked intensively with Hypothes.is. I have been in contact with the team both personally by visiting their office in San Francisco and through IRC chat and mail. It has also been a great help to be able to see [Jake Hartnell](http://hypothes.is/who/) on a daily basis. I have seen the tool evolve by reaching [milestones](https://github.com/hypothesis/h/wiki/roadmap) and seen them discuss and set new ones. 

Together with other students from the [UI class](http://blogs.ischool.berkeley.edu/i213f13/) at the [School of Information](http://www.ischool.berkeley.edu/) I have worked on fleshing out the [requested](https://github.com/hypothesis/h/wiki/roadmap) [groups feature](https://docs.google.com/document/d/17HDaujAt5P9o5x2Yinr8jL_tZS_3Zd36VBYbpPz-bkM) of the tool. After initial discussions with the core-team we found this task most promising, since it is a challenging problem that does involve more than just coding, which as described [here](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/tquast-assign3.html) included a very steep learning curve.

When we started the groups feature was still very vaguely documented and more an idea. Before we embarked on this project, Hypothes.is had two diametrically opposing settings for sharing annotations: “public”, which shared an annotation with the entire world, and “private”, which shared it with nobody but its creator. There was nothing in between. 

Groups created an option that would lie in between “public” and “private”, allowing someone to share particular annotations with particular sets of people. Many things were still unclear, some of the questions we have given an answer to over the past months are; How would groups be formed? How would they be administered? How would people be invited to, join, and leave groups? Could there be subgroups? Would we have private and public groups? How would users sort through and view annotations by the various groups of which they were members? 

To answer these questions we heavily relied on the input from potential users. Therefore intensive user testing has been one of our main contributions to Hypothes.is. Throughout the last four months we have hold more than twenty user interviews and test sessions. The prototypes we have developed can be divided in the following the categories:

###Paper Prototypes###
Based on different use-cases and personas we created a few low-fidelity paper prototypes e.g. [this](https://dl.dropboxusercontent.com/u/2440776/h_paper_Prototype.jpg) that implemented key tasks and scenarios. Using these paper prototypes, we did think-aloud sessions to gather feedback, and then iterate further with another paper prototype. 

The focus here was on the overall workflow and whether people understood the concept of groups and annotations. By using paper it enabled us to quickly adapt and test some different ideas. For example, we tested the layout of the tool as well as naming conventions.

###Interactive Prototype###
Using the feedback from our paper prototypes, we developed interactive prototypes using the [Balsamiq](http://balsamiq.com/) prototyping tool.  At this stage we had another student group conduct [heuristic evaluation](http://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/) using a [list of heuristics](http://www.nngroup.com/articles/ten-usability-heuristics/) by Jakob Nielson.

The main focus here was on the interaction with the prototype. Was the flow in the prototype understandable and did the different icons make sense? By using a heuristic evaluation we got highly detailed feedback, which made it easy to fix many of the problems that occurred during the tests. 

###Final Prototype###
The final prototype we have been working on can be seen **[here](http://groupsdemo.dokku.hypothes.is/)**. It is not meant to be implemented into the tool as it is, but more as a comment on how the functionality could be realized. We agreed on making it this way, because it was too resource intensive to code the backend while not knowing how the frontend would look like and what functionality would be needed. The prototype shown above has been thoroughly tested with users and all the findings are documented and sent to Hypothes.is. Having agreed on that this is the way it should look and work like Jake will take it the step further and implement it into the actual tool in the [coming months](https://github.com/hypothesis/h/wiki/roadmap).

##Conclusion##
It was a pleasure to work with Hypothes.is. After having worked with them I am confident that they have the best shot at how to finally make open annotation happen on the web where so many others have failed (see [assignment 6](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/tquast-assign6.html)). I hope that my contributions were helpful and that Hypothes.is will stand the critical look of real users when they enter the open beta. Hypothes.is has great potential and it's vision to free and democratize the web was the [reason why I joined](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/tquast-assign1.html). Many [influential people](http://hypothes.is/who/) are working on or watching the project.
Time will tell if Hypothes.is can live up to its expectations.

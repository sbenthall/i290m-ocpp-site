Title: Community ties through PeerLibrary
Date: 2013-10-15 21:00
Category: assignment3
Slug: aswigart-assign3
Tags: i290m-ocpp, peerlibrary
Author: Anna
Summary: PeerLibrary's community


Over the past few weeks, I've been getting more acquainted with what community really means for an incubating open source project like PeerLibrary. I've learned that there are multiple layers of support and discussion at play, each serving an important role.

Most saliently, there is the project's development community. These are the people that I am working with most closely UC Berkeley. The project leaders and core contributors (Mitar, Rodrigo, and Tony) are the members I turn to for direction on what to work on next and historical context for the project.

A couple of activities that I've been involved with recently have incorporated extra layers of community outside of our small group. Last week we entered a contest called the [Open Source Software World
Challenge 2013](http://www.ossaward.org/) that is centered in Korea:

>"Open Source Software World Challenge 2013" is the annual competition hosted
 by The Ministry of Science, ICT and Future Planning of Korea. This
 competition is mainly intended to promote open source software and expand
 various exchanges among open source software developers all over the world.

For the development group, the goal of submitting a demo of the project for this award served as a welcome motivator. We worked together to get the tool to a point where it was functional and complete enough to share with a global open source community. I was (and still am!) still working on learning the ins and outs of [Meteor](http://www.meteor.com/main) (the development framework PeerLibrary is built upon), so I ended up being part of the task force to design and implement our first full version of a [landing page](https://github.com/peerlibrary/peerlibrary/pull/148). This was a challenging, slightly intimidating, and very rewarding experience that let me eventually practice my HTML/CSS skills. More importantly, it gave me a chance to talk to the project leaders about the main ideas they wanted to be communicated about the project and how to boil these ideas down into compelling, bite-size pieces. I heard a number of different perspectives and set off to combine them in a new way, that I hoped was representative of the project's goals.

After a couple of sessions where I got feedback from two team members independently, I had notes full of sketches and possible description snippets, along with a rough mockup in Adobe Illustrator. I even posted these files to our [github repository](https://github.com/peerlibrary/design-files), but didn't get much feedback traction on them. Soon Mitar pointed out that it was time to start creating the actual page, and I made the switch. Though this was kind of terrifying initially (it was my first real set of code commits on github!), I started getting so many more comments and fixes as soon as I actually implemented the page in the format it was meant to be in. We ended up applying for the award and we even have a nice [preview video](https://archive.org/details/PeerLibraryPreview) of the tool.

I find that my experience here really aligned with [Fogel's](http://producingoss.com/en/consensus-democracy.html#version-control-relaxation) passage about the power of open-source software being bundled with version control software. Once I overcame the apprehensions I had about stepping on people's toes by misrepresenting the landing page content or --perhaps worse-- breaking something (even though I made a branch for my pull request!), I could see that those who had an opinion would voice it, and perhaps silence from others was quiet acceptance, which is perfectly normal as well. This type of behavior is consistent with some [voting practices of the Apache group](http://www.apache.org/foundation/voting.html), an resource that also helped me understand better what a "+1" response on a [past bug report](https://github.com/peerlibrary/peerlibrary/issues/89) I filed really meant.

In the case of the landing page, what mattered was getting the ideas out there in the proper format so that we could iterate on them. In the future, I'm certain we'll improve the design I chose and the words we wrote for it, but that doesn't mean we need to be at that "refined" state today, or that my landing page design is somehow less valid than one that a more senior member could have made. I'm learning that the workload in this kind of project is distributed, and sometimes in a very different way from work that might be *delegated* in a more structured, hierarchical project environment. FOSS depends on contributors' motivation more than anything else, and I'm looking forward to digging in more to find out about where this motivation comes from for different people.


I am also starting to design an admin dashboard for PeerLibrary, which will help keep track of new users and content (publications, annotations, highlights, etc.) and, critically, errors that occur client- and server-side. Since the [Meteor](www.meteor.com) web development framework we are using is a relatively young open-source product itself (with a healthy following!), there is very active [Google Group forum](https://groups.google.com/forum/#!forum/meteor-talk) around new issues that come up when implementing apps with this framework.
Last week, I [posted a question](https://groups.google.com/forum/#!topic/meteor-talk/D1-qNlB57S8) to the meteor-talk Google group and am so pleased that I have gotten several constructive and helpful replies!

After a slightly confusing application process and a long string of clarification emails with the [Jetbrains](http://www.jetbrains.com/) group, Mitar and I were also recently able to get our group a [free Professional Edition OSS group license](http://www.jetbrains.com/pycharm/buy/buy.jsp#openSource) for the [PyCharm IDE](http://www.jetbrains.com/pycharm/) (which also supports web development languages with a little bit of configuration).


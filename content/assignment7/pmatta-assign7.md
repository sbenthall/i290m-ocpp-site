Title: Assignment 7: Technical modularity of Geonode, its collaboration structure and how work gets done at Geonode; and my contributions.
Date: 2013-12-15 10:30
Category: assignment7
Slug: pmatta-assign7
Author: Prabha
Tags: assignment7, GeoNode, open source, peer collaboration
Summary: Technical modularity of Geonode, its collaboration structure and how work gets done at Geonode. Finally, my contributions to Geonode and OpenSource software in this semester.

# Geonode's community  
Geonode's community involves 3 groups : Users, Developers and Admins. The project caters to these three groups individually through various documentation and online workshops. 

[Users](http://geonode.org/user_features.html) use Geonode software and do not involve much in the development of the project. [Their workshop](http://docs.geonode.org/en/latest/tutorials/users/index.html#users) mainly deals with as to how to create an account on GeoNode, add layers and maps to your account as well as publishing those.

[Developers](http://geonode.org/dev_features.html) form the major part of the Geonode community and involve not only in the development of the core product but also the sister applications which support the project like Geonode platform, template support software, Geonode Website, Geonode Server Extensions, SDK applications, etc. [Developers' workshop](http://docs.geonode.org/en/latest/tutorials/devel/index.html#devel) provide tutorial on how to develop with and for the GeoNode software application - installation tutorials, core modules, software environment, etc

[Admins](http://geonode.org/admin_features.html) also use Geonode software in their applications and mainly deal with webservices, security issues, metadata and scalability issues. [Their workshop](http://docs.geonode.org/en/latest/tutorials/admin/index.html#admin) teaches how to install and manage a deployment of the GeoNode software application in the above mentioned aspects.

Among all the 3 above mentioned groups, developers play major role to keep the system upto-date and involve in the development and release of new software. Currently, GeoNode is under a feature freeze and testing phase. For the last few months, I have been a part of this group and involved in testing and bug-fixing of the project.


# Geonode's technical modularity
 Geonode is the ubmbrella software comprising of submodules involved to support the core Geonode software architechture. All the  sub-technical modules of the GeoNode are segregated based on their main funtionality. Few of those important ones are:

[Geonode](https://github.com/GeoNode/geonode) module is the main open source platform that facilitates the creation, sharing, and collaborative use of geospatial data. 

[Geonode-website](https://github.com/GeoNode/geonode.github.com) is the main [portal website](http://geonode.org/) of Geonode platform which contains blogposts, Geonode demos, contact points for users and developers, documentation, tutorials and thereof.

[Geonode-project](https://github.com/GeoNode/geonode-project) is the skeleton for GeoNode new template support.

[Gisdata](https://github.com/GeoNode/gisdata) module maintains GIS Sample Data to be uploaed into Geonode software before running the application.

[geoserver-geonode-ext](https://github.com/GeoNode/geoserver-geonode-ext) modules handles GeoNode's GeoServer Extensions.

# Collaboration structure of Geonode
The main team of the Geonode collaborates with World Bank and other developmental organisations and decide the roadmap for this project. They are not only concerned with most important features to be planned in the future releases, but also involve in day-to-day activities like coding, implementation, testing and bug-fixing, etc. Few of these core developers who have been since the beginning of the project, raise important issues related to feature implementation in the form of pull-requests and open issues. However, all the developers including old and newbies like myself can comment or fix any part of the code.I observe that there is no fixed hierarchy, at least while raising issues/bugs, assigning to developers and fixing those bugs in Github.

# How does work gets done at Geonode
Apart from Github, Geonode community also uses other forms of communication channels like [mailing list](https://groups.google.com/a/opengeo.org/forum/#!forum/geonode-dev) and [IRC](irc://irc.freenode.net/geonode). Though the internal structure seems semi-formal in nature as seen in github and mails, code changes follow a rigorous process at Geonode as per the the [GeoNode Patch Review Process]( https://github.com/GeoNode/geonode/wiki/Patch-Review-Process).

Whenever any critical/mandatory requirement needs a major change in the code, the developer raises an issue in Github and there is a proper patch review process in place. During the process, others will comment and discuss the possible solutions for that issue on the github itself. Once the issue is finalized, anywork can work on that issue. 

Similarly, any new feature or bug is raised as an [open issue](https://github.com/geonode/geonode/issues?labels=&milestone=4&page=1&state=open). Anyone can assign the issue to onself and starts working in a new branch. Whenever the code is ready, the developers submits the code in the form of [pull request](https://github.com/GeoNode/geonode/pulls). Such code changes which are sent as pull-requests to the collaborators are reviewed and merged into the code base.
Thus the integrity of the system is kept intact by the contributors of the project.

---
---

# My contributions to the Geonode project

In the last four months, I have gone through various stages from intial frustation due to installation problems to testing, then to bug fixes , sending pull requests and finally to an excited phase of closing issues.

 Initially, I went through the documentation to understand GeoNode's development environment. Most of my time is spent on fixing the installation problems as well as Code development problems due to mac incompatability libraries and thus leading to multiple crashes of my virtual box. (See [assignment 3](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/pmatta-assign3.html) for more details of the technical difficulties)

Once I installed the software successfully on my machine, I looked into the list of [open issues](https://github.com/geonode/geonode/issues?labels=&milestone=4&page=1&state=open), to find out various types of work I can contribute to. The list contains documentation improvements, new features as well as bugs. Since, GeoNode is currently under a feature freeze and testing phase, there is a lot of work to be done- testing, bug fixing and timely relase of GeoNode 2.0. There are about 200+ open issues/bugs and still huge amount of testing to be done to ensure quality of the code.

I worked on the following issues:

1.["Issue 1078: Upload page needs CSS adjustments"](https://github.com/GeoNode/geonode/issues/1078): When I initially installed, the application was running properly, however, I did not see any data or maps. Where do I get the data for the application to test on? So, I asked about this issue in the [mailing list](https://groups.google.com/a/opengeo.org/forum/#!topic/geonode-dev/9gVUVKiAxwA). I followed the procedure given in the reply, however, I encountered several system errors which was due to a broken mechanism in how the data dependencies were being searched while running the server. This is a new issue which I raised in github as [Issue No. 1230](https://github.com/GeoNode/geonode/issues/1230)

2.Another major problem I found in Geonode is the absence of critical documentation for the new release. Apparantely, there has been a problem in migration from Version1.0 to Version2.0. This was the same reason which caused my installation problems and the lack of de-bugging instructions thereof. This issue was raised in [Issue No. 1116](the https://github.com/GeoNode/geonode/issues/1116) which I decided to fix. I submitted [pull request](https://github.com/GeoNode/geonode.github.com/pull/13) fixing this issue to the repository and it was accepted.

3.There was one more relatively small but critical website bug which gives information to the GeoNode clients regarding the features installed in the Geonode server. There has been some problem with the features and some of them have been updated, merged and/or removed.  This was raised in [Issue No.1130](https://github.com/GeoNode/geonode/issues/1130). In response to this issue, I have done code changes in a branch and sent 2 pull requests: [pull request 12](https://github.com/GeoNode/geonode.github.com/pull/12) and [pull request 14](https://github.com/GeoNode/geonode.github.com/pull/14). Both of the pull requests have been accepted.

4.Currently, I am working on [Issue No.1183](https://github.com/GeoNode/geonode/issues/1183) and [Issue No. 943](https://github.com/GeoNode/geonode/issues/943). I have done code changes and it is in the testing phase on my local machine. Once the testing is completed, I intend to send the pull request for fixing these issue.

Besides these, I also tested various pull request changes and commented on the issues from time to time for possible fixes to those issues. Further, due to my code contributions, I am responsible for closing 2 issues: [Issue No. 1116](the https://github.com/GeoNode/geonode/issues/1116) and [Issue No.1130](https://github.com/GeoNode/geonode/issues/1130)


# What I learned from contributing to open source software
Apart from Geonode, this course has instilled in me a new passion to understand open source projects and do quantitative analysis of Github actitivity to predict the contributors behaviour. In this pursuit, I started my own mini-project [GITVIZ](http://people.ischool.berkeley.edu/~prabha.matta/gitviz/) for understanding Github open source software projects. This project is still work-in-progress.

Towards the end of the semester, I had the pleasure of working with Thomas Maillart, instructor of my Peer Production Course, to study productive bursts in code activity of various Github contributors throughout the life-cycle of the open source project, and developed a small vizualization on code activity productive bursts. The current prototype is [here](http://people.ischool.berkeley.edu/~prabha.matta/prod_bursts/) and I plan to continue on this work in the next semester to understand contributors dynamics through Github activity.

It has been a wonderful experience working with Geonode. After going through the whole life-cycle of Code Change and Review Process, I could understand the nuances of open source software contribution. This course taught me a very important teaching that open source world is not that scary as I used to think and that everyone can contribute in their own way to these projects. It gave me that initial push, which I badly required, to venture out into open source project world, approach the projects and try to figure out various projects to find the right fit for oneself.

Hopefully, I will continue participating in OpenSource projects as a personal hobby :)


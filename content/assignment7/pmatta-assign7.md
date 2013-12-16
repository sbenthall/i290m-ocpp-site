Title: Assignment7: Technical modularity of Geonode, its collaboration structure and how work gets done at Geonode; and my contributions.
Date: 2013-12-15 10:30
Category: assignment7
Slug: pmatta-assign7
Author: Prabha
Tags: assignment7, GeoNode, open source, peer collaboration
Summary: Technical modularity of Geonode, its collaboration structure and how work gets done at Geonode. Finally, my contributions to Geonode and OpenSource software in this semester.

ASSIGNMENT 7: Does your project's community mirror the technical modularity of the project? How does it structure its collaboration--synchronously? Asyncronously? How does it get work done?



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

# Collaboration structure
The main team of the Geonode collaborates with World Bank and other developmental organisations and decide the roadmap for this project. They are not only concerned with most important features to be planned in the future releases, but also involve in day-to-day activities like coding, implementation, testing and bug-fixing, etc. Few of these core developers who have been since the beginning of the project, raise important issues related to feature implementation in the form of pull-requests and open issues. However, all the developers including old and newbies like myself can comment or fix any part of the code.I observe that there is no fixed hierarchy, at least while raising issues/bugs, assigning to developers and fixing those bugs in Github.

# How work gets done at Geonode
Apart from Github, Geonode community also uses other forms of communication channels like [mailing list](https://groups.google.com/a/opengeo.org/forum/#!forum/geonode-dev) and [IRC](irc://irc.freenode.net/geonode). Though the internal structure seems semi-formal in nature as seen in github and mails, code changes follow a rigorous process at Geonode as per the the [GeoNode Patch Review Process]( https://github.com/GeoNode/geonode/wiki/Patch-Review-Process).

Whenever any critical/mandatory requirement needs a major change in the code, the developer raises an issue in Github and there is a proper patch review process in place. During the process, others will comment and discuss the possible solutions for that issue on the github itself. Once the issue is finalized, anywork can work on that issue. 

Similarly, any new feature or bug is raised as an [open issue](https://github.com/geonode/geonode/issues?labels=&milestone=4&page=1&state=open). Anyone can assign the issue to onself and starts working in a new branch. Whenever the code is ready, the developers submits the code in the form of [pull request](https://github.com/GeoNode/geonode/pulls). Such code changes which are sent as pull-requests to the collaborators are reviewed and merged into the code base.
Thus the integrity of the system is kept intact by the contributors of the project.

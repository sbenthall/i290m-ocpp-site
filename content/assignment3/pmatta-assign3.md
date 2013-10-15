Title: Assignment3: Community participation at Geonode Open Source Project until now
Date: 2013-10-15 13:30
Category: assignment3
Slug: pmatta-assign3
Author: Prabha
Tags: assignment3, GeoNode, open source, peer collaboration
Summary:  My experiences during participation at GeoNode open source project, the problems I faced and how I go about to solve them. Further, I also included my experiences in GeoNode related to our readings/regular class -  Résolution solving in GeoNode, Decision making process and Governance structure in Geonode community


#My experiences of engagement in the GeoNode community

GeoNode is currently under a feature freeze and testing phase. As a result, there is lot of work to be done- testing, bug fixing and timely relase of GeoNode 2.0. There are about 200+ open issues/bugs and still huge amount of testing to be done to ensure quality of the code. In order to do development on GeoNode itself, one should be familiar with basic web development concepts as well as with general GIS concepts. To understand this GeoNode development environment, I went through the following documentation:

1. [Introduction to GeoNode development](http://geonode.org/workshops/devel/intro/index.html#intro) - This document contains information about all the components that GeoNode is built with, the standards that it supports and the services it provides based on those standards, and an overview its architecture. To name a few: Django , GeoServer, GeoExplorer, PostgreSQL and PostGIS, Geospatial Python Libraries, jQuery, Bootstrap,etc

2. [Github Installation Documentation](https://github.com/GeoNode/geonode/blob/master/README) - This contains the installation instructions for GeoNode development environment on various machines.


#Problems faced during Installation:
As explained in my previous assignment, Geonode doesnot support many operating systems and versions. I experienced a great difficulty in installing GeoNode on my Mac. Since they do not support Mac, I installed Virtual Box for running Ubuntu OS. However, my virtual box crashed after GeoNode installation and all my work is lost. I had to re-create the whole system again. 


#Problems faced during Code Development:
Apparantly, GeoNode can be set up using 2 methods:
a. Run Geonode installation directly  to try geonode on Ubuntu using "sudo apt-get install geonode". This is easy and painless, however one cannot do any code changes or contribute to geonode github community.
b. Set up development environment to Geonode - This involves a complicated process where in, one has to install on the geonode and python dependency libraries in a separate development virtual environment. Later, GeoNode code in github repository is cloned, development server is set up, data is loaded and finally the server is run.

I installed geonode application using "sudo apt_get install geonode" to see the application in general and also simultaneously installed geonode development environment to fix bugs and push changes to github. They seem to share some common variables which created problems while running the Geonode development server


#How I resolved/resolving:
1. This is clearly a hack to get around the isse and solve the critical bugs at hand - I created multiple ubuntu virtual box machines - one for geonode server and other for genode.org website
2. Further,  I plan to raise these issues in Github as "open issues" - so that some experienced developer can look into them and fix them permanently. So that new-comers will not face these similar problems

##My work/contribution so far:
The first place I looked into the type of work I can contribute to, is the list of [open issues](https://github.com/geonode/geonode/issues?labels=&milestone=4&page=1&state=open). It involves documentation improvements, updates to the website as well as real bugs

I looked into 2 issues ->
1. ["Issue 1078: Upload page needs CSS adjustments"](https://github.com/GeoNode/geonode/issues/1078): When I initially installed, the application was running properly, however, I did not see any data or maps. Where do I get the data for the application to test on? So, I asked about this issue in the [mailing list](https://groups.google.com/a/opengeo.org/forum/#!topic/geonode-dev/9gVUVKiAxwA).

I followed the procedure given in the reply, however, I faced another problem in running the server with data loaded. This is a new issue which I raised in github as
"problem with running geonode server using test data" [Issue No. 1230](https://github.com/GeoNode/geonode/issues/1230)

2. GeoNode also has another major component aka GeoNode.org website itself. The issues related to design and bugs in the website are listed at
[geonode.org website open issues](https://github.com/GeoNode/geonode/issues?labels=website&page=1&state=open). I started looking into various issues, specifically at a relatively small but critical website bug: ["Issue 1225: No links to developers or users mailing lists in website"](https://github.com/GeoNode/geonode/issues/1225). 

Initially, I looked into the geonode github checked out code to find the relevant html and css files. But, after a thorough search, I realised there might be another github repository which is related to geonode.org. I found out that [this separate repo](https://github.com/GeoNode/geonode.github.com) handles geonode.org website code, which I am currently looking into, to solve the bug.




##My experience in GeoNode related to our readings/regular class:
#1. Résolution solving in GeoNode - 
very amicable - anyone can open an issue. Others can do 3 things 1) solve the issue/bug 2) write more comments as to how to replicate the issue 3) if there is an idea to solve it, that idea can be discussed in the form of comments in github. For eg: When I raised the issue of about problems faced while load the geo-spacial data into the server, others give immediate responses/options as to how I can go about solve this issue.

 
#2. Transparent decision making process at GeoNode with respect to feature implementation - 
Currently no new features are implemented in GeoNode. When ever any critical/mandatory requirement needs a major change in the code, the developer raises an issue in Github. Others will comment and discuss the possible solutions for that issue on the github itself. This ensures to keep a track of list of new features and the decision making process very transparent.

#3. Governance structure in Geonode - 
There exists a semi-formal governance structure in GeoNode i.e., there are few core developers who have been in the project for quite long time who get to raise important issues related to feature implementation. However, all developers can comment or fix any code. I observe that there is no fixed hierarchy, atleast while raising issues/bugs, assigning to developers and fixing those bugs in Github. Therefore, I can say the governance structure is somewhat of Benevelent Autocratic stucture at GeoNode


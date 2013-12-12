Title: PeerLibrary: Modularity, Structure and Contributions
Date: 2013-12-08 16:21 
Category: assignment7
Slug: tchen-assign7 
Tags: peerlibrary
Author: Tony Chen
Summary: 

### Technical Modularity

The goal of PeerLibrary is to capture the global conversation on scholarly literature. It is a daunting and non-trivial task that involves many moving parts. At the beginning, every contributor had generalist roles and everyone was pushing commits to master. As the project grew, we discovered that modularity in both the code base and organizational structure was necessary to make development more efficient. Contributor roles became more specific - Mitar took on the role of building the infrastructure, Rodrigo implemented new features and I predominantly worked on the client-side code. Our application is structured for modularity between client side and server side code to avoid our work breaking each other's code.

As more members joined the team, we became more rigorous with what got added to the master branch of the codebase. Whenever a new feature is worked on, we have to create a new branch for its implementation. Then by self-moderation, other contributors approve these additions before merging it with master.

In building with Meteor, we have also developed packages for it and submitted patches upstream. For example [PeerDB](https://github.com/peerlibrary/meteor-peerdb) is a package that implements database support for reactive references and auto-generated fields. We have also ported a lot of node.js packages into the Meteor ecosystem by forking their respective repositories and building Meteor smart packages.

### Community Goals

Operating a project with a lot of moving parts demands rigorous organization. The progress of PeerLibrary is tracked through our [milestones](https://github.com/peerlibrary/peerlibrary/issues/milestones?state=closed&with_issues=yes) on GitHub. Each milestone describes a series of very specific goals for each release and a deadline in which we should aim to ship this release.

Often, novel features get brought up during brainstorming sessions and it is important to prioritize which releases they should be in. Currently for 0.1 we're focusing on annotations and uploading of documents as barebone features for the application.

### Recent Contributions

My most recent [contributions](https://github.com/peerlibrary/peerlibrary/commits?author=chilldude) have been designing the frontend for the landing page and user authentication. Both contributions have been merged to the master branch as of recent.

Earlier last month, I had trouble building PeerLibrary on my local machine and encountered several system errors which was due to a broken mechanism in how the dependencies were being searched in Meteor. At that time I also submitted a [pull request](https://github.com/oortcloud/meteorite/commit/169e913afafd321f612c21eaa88bbe106b2a4a09) fixing this issue to the repository for the Meteor version manager, [Meteorite](https://github.com/oortcloud/meteorite) and it was accepted.

Title: The structure and modularity of PeerLibrary
Date: 2013-11-12 03:30 
Category: assignment7
Slug: rochigame-assign7
Tags: peerlibrary
Author: Rodrigo
Summary: How we work

In PeerLibrary, technical modularity has emerged informally. Our team never had assigned roles, but people naturally took responsibility for specific parts of the project: An works on writing, Anna works on client-side features, Seema works on outreach, and Tony works on the front end. Mitar works on everything, but concentrates most of his effort on organization and infrastructure.

I work on whatever is left: setting up the initial structure of the repository, fixing bugs, implementing authentication, creating the [interface for importing publications](https://github.com/peerlibrary/peerlibrary/pull/98), designing the [viewer](https://github.com/peerlibrary/peerlibrary/pull/188), etc. Mostly, I work on features that involve communication between client and server, because those are the least developed.

We work asynchronously, meeting sporadically to discuss our work. Thanks to Mitar, our issues are very well-organized on GitHub. It is easy to know which features and bugs are most urgent. Out of the communication channels we set up, GitHub tickets are the most used by far. Our IRC channel is mostly empty and the development mailing list is fairly inactive. Tickets are efficient and strongly linked with the code.

At some point, we decided to move to [this git branching model](https://github.com/peerlibrary/peerlibrary/wiki/Development-Model). According to it, we should make pull requests for any code pushed to the repository. This is not enforced too strictly: all of us make pull requests for large changes, but push minor ones directly to master. Anna is the only good one who follows our development model perfectly.

I like our de facto model. Having to create pull requests for tiny changes can cause some gridlock. In practice, we create branches and pull requests when they are *relevant* (i.e. when the changes will benefit from a code review).

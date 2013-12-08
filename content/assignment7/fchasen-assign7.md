Title: PDF.js Modularity and Structure 
Date: 2013-12-08 14:00 
Category: assignment7
Slug: fchasen-assign7 
Tags: pdfjs
Author: Fred Chasen
Summary: Modularity and Structure of the PDF.js project, and an update on my contributions.

### Technical Modularity

PDF.js is a project with the single goal of enabling PDF rendering and creation through Javascript. However in recent years Javascript execution has leaped out of the Browser with projects like Node enabling serve side applications. Additionally, PDF.js runs locally as an extension on several web browsers. Each of these ecosystems has it’s own needs and quirks, forcing modularity of the project.

There are slightly different viewers for the Firefox extension, Chrome extensions and B2G (Boot to Gecko, a “standalone operating system for the open web”).  While the web viewer is updated almost everyday by a large group of contributors, these extensions receive far more infrequency updates (about every two weeks) by a small core group.

### Structure and Guiding of Work

Guiding the progress of the library is done through [milestones on Github](https://github.com/mozilla/pdf.js/issues/milestones?state=closed&with_issues=yes). These milestone set out a specific goals for a release, such as “Text selection and search” or a specific Firefox release. There have also been special requests, like Font testing, on the mailing list. Of course contributors are free to work on any issues they please, but merging those issue will be less of a priority or might be delayed to the next milestone.

### My Contributions

As for the progress of my [contribution](https://github.com/mozilla/pdf.js/pull/3815), it has gotten caught up in a very active discussion on the how to [handle user preferences](https://github.com/mozilla/pdf.js/pull/3850). I am following this discussion closely and once this large change to the viewer has been merged, I will update my contribution to autohide the toolbar to match the changes. 

I hope to continue my contributions to PDF.js, as it has been a great project to be a part of. It is fantastically well documented and organized for new contributors while maintaining compliance with the mature ecosystem of the PDF platform. Seeing how they balance new ideas with compliance has helped guide my approach on my own project to render ePubs using Javascript. Finally being able to contribute to the user interface of the viewer has been personally rewarding and I can’t wait till I can open a PDF in Firefox on any computer and see my commits in action.
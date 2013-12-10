Title: PDF.js Funding 
Date: 2013-12-08 14:00 
Category: assignment6
Slug: fchasen-assign6 
Tags: pdfjs
Author: Fred Chasen
Summary: Funding for the PDF.js project.

### Funding Sources

PDF.js is a part of Mozilla Labs, which gives employees of the non-profit Mozilla Foundation time to work on it. How Mozilla is structured and funded is beyond the scope of this blog post, but they receive direct donations, corporate donations (from Aol and others) and funding from “search royalties.” These royalties come from an agreement that makes Google the default search in Mozilla Firefox web browser. The foundation receives around [300 million dollars a year](http://allthingsd.com/20111222/google-will-pay-mozilla-almost-300m-per-year-in-search-deal-besting-microsoft-and-yahoo/) from this.

As PDF.js is shipped as the core PDF viewer in Mozilla’s Firefox web browser, the project likely receives more employee time then most other Mozilla labs projects. However, like other Lab projects the infrastructure is paid for and hosted by Mozilla. This includes a wiki, a etherpad server, aconference call system and a bug tracker. Additionally, there are weekly public meeting lead by a Mozilla project manager.

I’ve tried unsuccessfully to determine how often the employees on the project are located in the same building, as this could greatly affect the community's cooperative dynamics. Irregardless, the Github repo and Mailing list give the impression that there are not backchannel decisions being made. For instance on several issue threads on Github, one member will “Ping” another core contributor to take a look a the issue in the comments of that thread. Further discussion of solutions will continue in the comments below. This suggests that the public infrastructure is the main means of communication.

### Competing Projects

There are many competing PDF rendering engines, though no other major Javascript ones. Beyond the official Adobe reader and creator, every operating system and browser ships with one along with many independent implementations. To handle this large ecosystem Adobe has created tools to check compliance with the PDF specification. This helps to ensure that a PDF created with one writer can be rendered in a different reader, but also allow for  projects like PDF.js to easily validate their efforts and choices against a large and mature test suite.  

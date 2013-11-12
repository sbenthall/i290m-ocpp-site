Title: A2 - History of CourtListener
Date: 2013-10-09 12:21
Category: assignment2
Tags: free law project history court listener courtlistener
Slug: pnguyen-assign2
Author: Peter Nguyen
Summary: Report on history, infrastructure, and demographics of Free Law Project

## History of CourtListener / Free Law Project
In 2009, The Free Law Project was created to provide universal access to legal material for researchers and everyday users. Brian Carver advised Michael Lissner on the project. After he graduated, they continued working on the site to grow the database to over 900k documents. These legal documents are in the public domain to begin with. However, they have always been protected by law search companies and services that charge ridiculously high subscription fees. CourtListener is an open platform (under the Free Law Project) that anyone can use and build upon. The code is open-source and publically available, allowing anyone to run their own "CourtListener" as well. 

Brian and Michael made it open-source so that if they ran out of money or had tragic accidents, others would be able to continue development right where they left off. I would say their reasoning is ideological because they want to help people access legal documents. In Richard Stallman's "Why Software Should Not Have Owners," he talks about how free software leads to production of more free software. He adds that people "deserve" free software, which has traditionally been guarded by people who confuse the public with terms like, "intellectual property" and "damage". We are used to hearing exaggerations of losses derived from copyright infringement. Likewise, making the project open-source is practical because researchers and developers can help build and grow the platform to encompass more courts, cases, and briefs. Others, like myself, can contribute our expertise too. I am contributing user interface design expertise, usabilility/needs assessment, and creating state portals that can hopefully grow into a directory of attorneys to financially sustain the project. 

## Size of CourtListener Community
There are about 10 project contributors and developers right now. Brian sent out a message to our listserve last month introducing us to one another. Our global team consists of law school faculty (Japan), Chinese data scientists, computer science PhDs (U.C. Santa Cruz), law students (Harvard), a Canadian lawyer, and more! We're well versed in all facets of the development process-- from design, to research, to coding, and even legal issues that might come up. Again, this information isn't available on the free law project website, but it was sent to each of us earlier this semester via email. 

## Project Information about CourtListener
The Free Law Project is a collection of three services: CourtListener (search engine), Juriscraper (case archiver), and the entire law corpus it has archived. The Free Law Project aims to develop and implement useful technologies for public research, create an open ecosystem for legal research, and teach others about it with thoughtful seminars and workshops. CourtListener is the product I am directly involved with. It falls under Creative Commons licenses and should be used for research purposes. The law corpus has been integrated into law research startups, and interest grows daily. State courts are even looking for better ways to search their own archives, something I look to tackle this upcoming semester. 

"Governments, market forces, publishers, and traditional academic libraries can influence, but are not able to stop, the international movement of distributed information" (Hess, C. & Ostrom). The Free Law Project is at the forefront of this distributed information movement, allowing people to access legal documents without costly subscriptions or gatekeepers. The body of scholarly information is also available as a whole, which means that people don't have to try to reinvent the wheel when creating their own research projects. I feel like this is vital to innovation!

## Court Listener Infrastructure
CourtListener runs on various open source libraries itself. Juriscraper is the scraping process, which is a custom XPath-based scraper using lxml. The operating system is UNIX, an open source operating system that runs Apache (web server), django (database management system), and a "blazingly fast" open source enterprise search platform called Solr. Solr runs on Apache, the open-source backbone of over 65% of websites. Under Karl Fogel's "Technical Infrastructure" guidelines, the project lacks real-time chat. Other than that though, there is a website (Apache), mailing lists (Mailman), version control and bug tracking (bitbucket/github).

Readings
* [Stallman, R. "Why Software Should Not Have Owners."](http://www.gnu.org/philosophy/why-free.html)
* [Chapter 3, "The Movement", and Chapter 4, "Sharing Source Code", from Kelty, C. Two Bits](http://twobits.net/pub/Kelty-TwoBits.pdf)
* [Fogel, K. “Technical Infrastructure” Producing Open Source Software](http://producingoss.com/en/technical-infrastructure.html)
* [Hess, C. & Ostrom, E. Ideas, Artifacts, and Facilities: Information as a Common-Pool Resource. Law and Contemporary Problems 111-146 (2003).](http://scholarship.law.duke.edu/cgi/viewcontent.cgi?article=1276&context=lcp)

Links
* [Court Listener](https://www.courtlistener.com/)
* [Free Law Project Home](http://freelawproject.org/)
* [Free Law Project Mailing List / Development Archives](http://lists.freelawproject.org/pipermail/dev/)
* [Free Law Project Bitbucket](https://bitbucket.org/mlissner/search-and-awareness-platform-courtlistener/)
* [Juriscraper Bitbucket](https://bitbucket.org/mlissner/juriscraper)
* [Press Release](http://www.dailycal.org/2013/09/29/free-law-project-provides-access-to-legal-materials-and-research-for-public/)
* [Apache Usage Statistics](http://w3techs.com/technologies/details/ws-apache/all/all)


added Comments Thomas 11/6/2013 (see commit description)

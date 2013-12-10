Title: Free Law Project Structure
Date: 2013-11-30 18:00 
Category: assignment7
Slug: amcconachie-assign7
Tags: i290m-ocpp, Free Law, Structure, Conway's Law, Parkinson's Law
Author: Andrew McConachie
Summary: Structure in the Free Law Project

I've mentioned [Conway's Law](http://www.melconway.com/research/committees.html) a few times this semester in large part because I've thought it important to reference older contributions to the literature that we're reading now.  When we read [The Architecture of Participation](http://mansci.journal.informs.org/content/52/7/1116.abstract) I couldn't help but think about how they benefitted from the earlier observations of Conway and [Parkinson](http://www.princeton.edu/~achaney/tmve/wiki100k/docs/Parkinson_s_law.html) and it would have been nice if they would have referenced their contribution.

Conway's Law is definitely relevant concerning how the Free Law Project gets work done.  The Free Law Project is organized along the lines of a benevolent dictatorship and this means that the software artifacts they produce bear a certain resemblance to other software artifacts developed under benevolent dictatorship models.

Take for example Juriscraper.  Originally Juriscraper was written by Mike Lissner as a part of courtlistener.com.  It was highly coupled and non-modular in relation to the rest of the project.  As the project grew Juriscraper was broken out into its own software library with the idea being that it would eventually get used by other projects that might want to scrape court opinions.  This has so far not happened, no other project has come forward to use Juriscraper for scraping court opinions.  So there has been no achieved utility from modularizing Juriscraper yet.  However, it shows an interest in the founders of the Free Law Project to grow through modularization and try to attract more people to their project.  Maybe even to share power to another benevolent co-dictator.  The first thing I contributed to the Free Law Project was a pull request on Juriscraper.  Having it broken out as a separate module definitely eased my burden of contributing to the project since it meant it required less of an initial investment for getting up to speed.

Another example of Conway's Law in reference to the Free Law Project is the [Free Law Ferret](http://citationstylist.org/2013/08/20/free-law-ferret-document-to-cited-cases-in-a-click/).  The Free Law Ferret is a Firefox plugin that finds citations in online legal documents then performs a search on courtlistener.com to retrieve them.  It's an easy way for someone researching the law to find relevant opinions without having to leave their browser.  It also integrates with Zotero and MLZ, two popular citation assistants for Firefox that are useful for organizing citations of web resources.

It's development is independent of the Free Law Project but both projects gain value from each other.  As a software artifact its own development organization follows the benevolent dictatorship model so organizationally one can think of both projects as just two dictators working together for common benefit.  However, the Free Law Ferret is definitely complimentary to the Free Law Project and not the other way around.  The Free Law Ferret could not exist without courtlistener.com.  In this way the development of the Free Law Ferret in relation to the development of the Free Law Project mirrors the structure of their communications network.  The Free Law Ferret's developer is not a Free Law Project co-dictator so the unidirectional satellite relationship between the two projects applies to both how they're developed and how they institute power.

#### Contributions to the Free Law Project
My first contribution to the Free Law project was adding the Virginia state appellate courts to Juriscraper.  Since then I have been working on adding a feature to courtlistener.com which shows relevant key-terms for each court opinion.  In the process I have discovered many bugs in the [Free Law Virtual Machine](http://freelawproject.org/2013/10/15/free-law-virtual-machine-available-for-academics-and-developers/).  Some of them I have resolved myself and contributed upstream, but most of them have been things I discovered which didn't work and then Mike Lissner resolved with code changes.  I hope to finish my development on finding key-terms in opinions and eventually have it merged with the live courtlistener.com.  But so far this work is ongoing.


















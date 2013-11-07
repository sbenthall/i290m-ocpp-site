Title: Exploring Common Crawl
Date: 2013-10-07 10:20
Category: Open Collaboration and Peer Production
Tags: pelican, publishing, commoncrawl
Slug: rbora-assign2.md
Author: Renu Bora
Summary: Assignment 2

**ASSIGNMENT 2: Report on the history, infrastructure, and demographics of the project.**

**1. Why is the project open? Is it for ideological reasons, or practical reasons, or both?**
The project is open in several ways, for ideological reasons (possibly some practical, as I�ll speculate).
As per their website [common crawl faq], their mission as a 501c(3) is �to democratize access to web information by producing and maintaining an open repository of web crawl data that is universally accessible.� They envision [common crawl our work] �a truly open web that allows universal open access to information and enables greater innovation in research, business, and education.� They aspire to crawl and share as much of the web as possible (their most recent dataset is over 100 Terabytes). The data has various formats, including an archive of JSON metadata. They also offer materials besides the data crawl [common crawl crawl data].
In addition to their data being open, they offer some sample code on Github. This includes both internally produced samples and code offered by the community. Since their organization is partly staffed by volunteers, the distinction between external and internal members is not always simple.
Common Crawl also offers an Amazon machine image with some code and scripts, to help users get running more quickly (including Hadoop code designed to extract data from their Amazon S3 buckets).
The reason for these project assets and processes being open is stated by their mission. One might infer that it would be expensive to publish even more of their internal communications, decision-making, and processes. Also, with the exception of support, their product and community product are focused on the data itself, with some some data mining tools and scripts.
The core product is not evidently peer-produced (though the web that it harvests contains peer production!). The business and technical decisions of the foundation are fairly centralized (though likely fall short of the Linus Torvalds �benevolent dictator� model). The sole founder of Common Crawl is Gil Elbaz, and the director of the foundation is Lisa Green. Both have interesting backgrounds in their own right, which presumably guide how they implement the mission and vision. (EXPAND LATER- POSSIBLY INCLUDE BOARDS AND TEAM).
Their mission does state that they want more than just large search engines to have access to the entirety of the web. They do not mention explicitly what some see as threats to the �open web� in the form of �walled gardens� such as Facebook, Apple, etc., or threats in the form of �non-open activity� as per private companies or covert surveillance by governments or criminal parties. A similar threat might be in the �App-API-data� model which might correspond to the decline of the browser-world that seems to define the web. One might speculate, the �open web� may not only enable innovation, but by demonstrating value, facilitate ongoing �open�-leaning or transparent policies, products, and even public domains/commons/democracies.
Also to EXPAND LATER, more granular descriptions of the open and peer facets of the product(s). Also, Find out more about the Ajax-y URI JSON resources (to what extent do they get included in the corpus?)

**2. How big is the community? Where are its members located? How did you find out?**
The community, including all users asking questions, seems to be less than 100. I found out by estimating:
1) Staff/volunteers listed on their website. Some via blog entries or video presentations (8)
2) Board members/advisors listed on their website (16)
3) Github repository members and contributers (~18). Fourteen repos were present, including the main data extraction tool for Amazon/Hadoop and many examples of using the data. Most repos were entries for their first coding contest. Activity showed mainly forks and commits, but few contributor submissions that reflect growing communities. 
4) One additional community group of researchers used not Github but Subversion and Assembla.com (8).
5) Community user support materials on their wiki [support site]: Atlassian.com. (5).
4) Participants in their Google Groups (~50?)
One problem mentioned by the Director, Lisa Green, is that they cannot easily track the use of the data set with back-end analytics. It is almost certain that there are users or user communities that are not part of the larger community.
Github shows some local activity graphs that are not substantial enough to extrapolate a larger product lifecyle chart (Though the larger lifecyle looks endogenous non-critical, the individual annual data releases look engogenous critical). Likewise, Google trends shows what might be local peak plateaus in 2012 and 2013 (as well as a smaller peak in 2010). However, the project (started in 2009) seems too new to tell whether there will be a stable, periodic, annual peak, or the project will ultimately rise more, to eventually fall. 
The board members and team are all US-based. Most live in San Francisco or Los Angeles. (Gil Elbaz�s company Factual is based in Los Angeles, and several Factual employees are part of the team).



**3. What kind of product is it and how is it licensed?**
The main product consists of the crawl datasets (as hosted on Amazon). The supporting products include code samples, and the Amazon machine image. They offer terms of usage that mainly involve disclaiming liability for the data usage, and stating that their data is not intended to support the breaking of any laws. Their Limited License as per their website [terms], works with their Terms of Use, and will take more analysis to explain:
�LIMITED LICENSE. CC grants you a limited, non-assignable, non-transferable, non-sublicensable limited license to access the Service subject to the terms and conditions of this ToU. You may not use the Service or the Site in any manner except as authorized under this ToU. CC reserves all other rights not otherwise granted in this ToU.�
EXPAND LATER: Lisa Green said she would explain some of their interesting licensing features.

**4. What sort of infrastructure does it use? Why does it use those tools and not other options?**
They use tools to make their repository available, usable, and affordable [accessing the data]. As per [common crawl faq], �We store the crawl data on Amazon�s S3 service, allowing it to be bulk downloaded as well as directly accessed for map-reduce processing in EC2.� Amazon�s E2/S3 cloud infrastructure was used for several reasons. This cloud hosting is easily scalable, and while users do need to pay for their own S3 instances to run Hadoop and Amazon MapReduce jobs, users don�t have to pay for the bandwidth between their instances and the Common Crawl dataset. (One community used not Hadoop, but Amazon�s SQS and other libraries/customizations). Amazon is also the most popular cloud computing platform. Hadoop is most commonly used with java (the language it is written in), but users can use Hadoop�s API�s with Ruby, PHP, and other languages (made easier with Amazon�s MapReduce which seems to be a Hadoop GUI). Users do have to pay for their S3 instance(s), and possibly E2 if they want to store any data on Amazon.
Their processing pipeline infrastructure is not fully opened (since it is not really part of their product), but described as follows [data processing pipeline]: �Our internal data center hosts various sets of servers, including a Hadoop cluster and a bank of dedicated crawlers. We crawl the web via our connection to a Tier 1 ISP. We transfer all download content to our internal HDFS cluster. We then run various MapReduce jobs to process the content, and then archive the content into compressed ARC files, each of which is approximately 100MB in size. These files are then uploaded to one of our S3 buckets within the Amazon cloud.�
Common Crawl recently started using Apache�s Open Source �Nutch� for their crawling engine, but the crawling code is not available (or presumably, needed) to users. Common Crawl�s documentation also mentions a crawler called ccbot, which is either their legacy crawler, or an additional customization. As mentioned, for communication and collaboration support they have a website, Github repository, [support site], and Google group. 
	
**Feel free to ask the community directly about these questions. There may be historical archived records of conversations about these decisions. Please provide links to any evidence you use in this report.**

**The primary purpose of this project is to gain factual information about your project. This will make it easier to compare projects systematically.**

**In addition to this factual information, feel free to elaborate on your personal reflections on this material. (This is especially encouraged for those who are working on the same project with several other classmates):**

**5. What do you think about the reasons for the project's openness? Does it resonate with what interested you in open collaboration in the first place?**
**6. Would you have approached the community differently, knowing what you know now about it?**
**7. How are you finding the experience of using the project infrastructure? Are they helping or hindering your participation in the project?**
**8. Please try to connect your answers to the literature that we've been reading in class. Is anything surprising, given what you've read? Anything resonate with any of the readings in particular?**
**Idea: Collect Google Groups and other discussion text, analyze for sentiment, etc.**
----- Links for Pelican ------
[support site]: https://commoncrawl.atlassian.net/wiki/display/CRWL/Quick+Start+-+Build+from+Github 
[discussion forum]: https://groups.google.com/forum/?fromgroups#!forum/common-crawl
[common crawl]: http://commoncrawl.org
[common crawl faq]: http://commoncrawl.org/faq
[common crawl our work]: http://commoncrawl.org/our-work/
[common crawl crawl data]: http://commoncrawl.org/author/ahad-rana/
[support site]: https://commoncrawl.atlassian.net/wiki/display/CRWL/Quick+Start+-+Build+from+Github
[accessing the data]: http://commoncrawl.org/data/accessing-the-data/
[data processing pipeline]: http://commoncrawl.org/data/processing-pipeline/
[terms]: http://commoncrawl.org/about/terms-of-use/full-terms-of-use/


read by Thomas 11/6/2013


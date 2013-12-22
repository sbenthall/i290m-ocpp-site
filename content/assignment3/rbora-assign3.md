Title: Exploring Common Crawl
Date: 2013-10-07 10:20
Category: Open Collaboration and Peer Production
Tags: pelican, publishing
Slug: commoncrawl
Author: Renu Bora
Summary: Assignment 3

ASSIGNMENT 3: Blog post about community participation. Incorporate links to your project participation and engage the readings. Do they generalize to your experience? Or not? How?

My participation has had many challenges, so my contribution is mainly in a list of ideas and recommendations that I am offering to Common Crawl (my scope kept retreating with various setbacks, but also as I learned the technical nature of Common Crawl). One could see this document as a marketing/community-building document, so is in the category of non-technical contributions (though somewhat technically informed). Also, the contribution is experimental in that it builds on the themes of the class centering on the challenges to joining.
I do believe the most useful participations are in the sharing of use-cases of Common Crawl, which they call inspirations:
[ccwiki inspirations]
Even though this is not a code or product contribution, the research and innovation enabled by Common Crawl is fully known, so these projects help people map and imagine the opportunity space and concrete ideas.
The process of trying to participate led to many setbacks, but is an interesting learning experience and sheds some insight on a few factors in open source participation.
There are some interesting takeaways:

1) I initially believed that contributing would be made easier by direct contact with the Director of the organization. I do believe that in the long run, (after this class), this relationship will be valuable and helpful to all parties and hopefully the broader community. However, I didn’t anticipate that since there was a new product release for the year, and many other factors, their responsibilities would demand that they attend to high-priority contingencies and urgencies. Communication was excellent in terms of needing to postpone our planning or coordinating phone calls, but in practice, we had only one actual call in mid-October (which was very helpful and informative). There were several meetings that were cancelled, but again, communication was good about the status, and I took each turn to research more about the organization activities and shift my proposal and questions about needs.

2) One positive outcome of the delays in participating are that the newest crawl is now out, and technical work from this point involves a few format and technology updates, which should be valid for several years ongoing.

3) Because the amount of time left kept changing, I kept changing the scope of my contribution possibilities. It became clearer over time that the technical baseline knowledge to get started with the system was greater than I anticipated (AWS seemed feasible to use, but then Eclipse and Java have a steeper learning curve, though I have some familiarity with Java. Their libraries do make some Hadoop use much easier.) I increasingly shifted scope to helping with some type of support work in the form of web site design, else documentation or marketing work. That shifted to trying to help plan and perhaps use the course for insight on joining practices. While it is true that there could be easier to-do tasks made available, it may also be true that their standard contributor flow involves using the forums if needed to either get help with research/analysis or sharing research/analysis and process with the community. My difficulties doing non-technical or non-research work aren’t necessarily indicative of a deeper problem they have, since I may not be their exact target audience. My own impression is that I may resemble a potential user which might more be a student taking a much more structured data mining/big data class with specific data assignments and projects, in which incremental learning could happen via Common Crawl usage. As a matter of fact, Raymond Yee’s class on “Open Data” at Berkeley’s Information School might provide that form of structure towards using Common Crawl as an educational vehicle, so their community may ultimately benefit from my work in the long haul. (e.g. Common Crawl is aware that their “Get Started” and onboarding improvements are one of their priorities, but their own next step is not yet clear. My contribution below involves suggesting improvements in their documentation and organization, in part to help beginners, with the caveat that I suspect that my own use case is an outlier of sorts. The resources needed to do such improvements involve both management and projects/tasks, so I am trying to provide both. (It is possible that I am replicating basic management work that Common Crawl is already doing). I am assuming they do not have resources to completely re-design their communication infrastructure pieces mainly the in the form of the website, but also Atlassian, Google Groups, Github, and YouTube. 

My project is not fundamentally open source software production, but the paper most relevant to my joining efforts was “Community, joining, and specialization in open source software innovation: a case study” by Krogh, Spaeth, and Lakhani. There is no structure of joiners, newcomers, and developer for the product team. However, structurally, my position was similar in that I was interested in helping, and following initially a declaration of intent to contribute, then sought out collaboration in terms of how, and task definition. As per Krogh’s research, I do believe that as an open project of sorts, just doing work and offering it would be more easily incorporated than expressing an interest in doing work, but the structure or my skillset didn’t match their community offering initially, or their availability (which is why helping the organization directly was my initial goal, rather than doing research which could become a case study for the community). The measure of overhead in bringing newcomers in is assessed as a cost, as Krog et al explain. The place where people do contribute is in the use of the crawl, and sharing of practices. That body of work is arguably part of the whole resource itself, the company Trivio (Scott Robertson, the CEO) created indexing software for Common Crawl which they not only posted on Github, but updated from a contributor’s patch: [trivio index] . The Common Crawl ecosystem, then, is potentially a spawning ground for open source projects. Common Crawl also utilized hisSince the community uses and code do not need to be integrated with each other or the core code, it doesn’t make perfect sense to use “specialization,” “contribution barriers,” and “feature gifts” in the same way as Krogh, but “joining script” makes some sense in that just being added (if not integrated) to the Common Crawl information ecosystem (not code or data) does seem to follow a pattern of someone creating some code and/or analysis as a user, then offering it just by publishing it to the community. Sebastian Speigler, who contributed a demo video, is on their volunteer roster, whereas Scott Robertson is not. The status or meaning of the volunteer status isn’t quite clear, so increased transparency may or may yield more information on versions of “joining script.”

IDEAS AND RECOMMENDATIONS
COMMUNICATION CENTRALIZATION AND CONTENT COORDINATION

1) Though Common Crawl has links to a Google Group (which seems fresh/active) and a website blog (also fresh/active), there are links to a wiki which is on Atlassian that has a FAQ and many items from 2012 that seem somewhat dated (though some technical information still applies). [wiki faq]. Now that a new dataset is out, there, the wiki could be updated to reflect the new specifications.

2) The wiki may also need updating, since this page: [wiki guides]
Doesn’t reflect the helpful links from the newest crawl:
[new crawl]
The wiki materials referring to ARC formats and older crawls still apply, but they need to be updated to clarify that they apply only up to 2012.

3) The Github codebase (which contains Common Crawl’s engine code that is used to generate the dataset) [codebase] shows no activity for several months. It seems that their newest crawling code has not been pushed up to Github, so that could either be done, or some other option or explanation could be given.  

4) Their wiki “inspirations” use-case list hasn’t been updated with their co-sponsored “Norvig Award” entries. This a contest sponsored by Common Crawl and Surf Sara, [surfsara], a Netherlands technology organization, which evaluates submission’s use of Common Crawl and Hadoop for 
[norvig award]
Though these do seem to appear as repositories in Common Crawl’s GitHub, they could be more accessible if described and listed on the website, as well.

5) Purpose of the group:
[google group] has a clear list on forum purpose, which could be listed on the website under the link to describe the types of community potential and need: “ 
*Discuss challenges 
*Share ideas for projects and products 
*Look for collaborators and partners 
*Offer advice and share methods 
*Ask questions and get advice from others 
*Show off cool stuff you build” 

BUDGETING HELP

Budgeting for Common Crawl AWS use is somewhat hard to estimate because there are so many variables, but ballpark numbers do seem helpful, and such numbers are available within the various content of the site. It might be beneficial to centralize some example costs, though the community need should likely be validated, as well.
a) This page helps explain the value of using the new contributed index data (Amazon data transfer seems to be free within the same region, so it would help to have a doc explaining how to ensure one’s instances are in the same region. (Note: the index data resource is not the same as the crawl repository)
[url index]
b) This page links to a PDF report which describes some fairly extensive analysis costing only about $200 in AWS fees.
[analysis]
c) This video by the CTO Jordan Mendelson called “Big Data for Cheapskates” has valuable optimization tips for Common Crawl and Big Data in general, with some mentions of AWS costs in different use-cases, so could be posted on the website
[cheapskates]
4) In a forum one member answered a question by linking to the Amazon pricing page. This link could also be useful in a budgeting section: http://aws.amazon.com/s3/pricing/

SPAM COMMENTS

To help with their forums, I read through many posts (Google Groups, wiki/Atlassian, and the Blog which for commenting integrates the services of DISQUS, a 3rd party company), and flagged two spam articles in comments:
[spam]
However, the articles have not yet been removed so it may just be feeding data to spam filtering systems, rather than being reviewed by a human being for removal.

[ccwiki inspirations]: https://commoncrawl.atlassian.net/wiki/display/CRWL/Inspiration+and+Ideas
[wiki faq]: https://commoncrawl.atlassian.net/wiki/display/CRWL/Frequently+Asked+Questions
[trivio index]: https://github.com/trivio/common_crawl_index
[wiki guides]: https://commoncrawl.atlassian.net/wiki/display/CRWL/Helpful+Guides+and+Links
[new crawl]: http://commoncrawl.org/new-crawl-data-available/
[codebase]: https://github.com/commoncrawl
[surfsara]: https://www.surfsara.nl/
[norvig award]: http://norvigaward.github.io/entries.html
[google group]: https://groups.google.com/forum/#!forum/common-crawl
[url index]: http://commoncrawl.org/common-crawl-url-index/#comments
[analysis]: http://commoncrawl.org/a-look-inside-common-crawls-210tb-2012-web-corpus/
[cheapskates]: https://www.youtube.com/watch?v=vWa9CUsNzdw
[spam]: http://commoncrawl.org/common-crawl-url-index/#comments

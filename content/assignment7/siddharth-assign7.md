Title: Assignment 7 – Technical Modularity
Date: 2013-12-15 18:50
Category: assignment7
Slug: assign7
Tags: i290m-ocpp, freelaw, courtlistener
Author: Siddharth
Summary: Details about the technical modularity of freelaw project.

----------

Freelaw project has mainly two modules: Juriscraper and Courtlistener. Juriscraper is a scraper library written in Python, and is used to scrape the American court system. It is currently able to scrape all major appellate Federal courts, and work is ongoing to add state courts. Second module is the Courtlistener, which is responsible for calling a scraper, and downloading and saving its results. There are other tools used in the whole process such as Eclipse with the PyDev, Aptana, SOLR for search engine, and xpath.

To get started on the development environment of Freelaw project, I installed the Freelaw VM on my system. There were lot of issues with VM which had be resolved but quick responses from [Mike Lissner], and FAQ section in the VM helped to a great extent. Although the small size of the community and benevolent dictatorship model of Freelaw was helpful to get my issues fixed quickly, but it proved to my disadvantage in few cases. For example, once we got the VM image and started using it for our project, when we encountered errors and debugged them we figured out that database schema had been changed by the administrator and there was no communication. This went back and forth for some time until we decided to create our own corpus by converting all the opinions in database in text format. Since there are not many contributors currently, issue could be handled with few mail exchanges, but in future when number of contributors will increase and if project is not modularized properly, there might be various issues which might take longer to resolve.

####My contribution:
Currently I am working with another contributor on this project and our goal is the enhancement of opinions on courtlistener.com by identifying and extracting relevant key-terms for each opinion. These key-terms can then be used to create a tagsonomy and provide users of courtlistener.com another means of navigating relevant opinions. We intended key-terms to be general enough such that they appear in more than one opinion, but specific enough such that they do not appear in too many opinions as to be useless for navigation purposes. Key-terms could be single words (unigrams) or they could be n-grams that occur frequently. Once an effective means of determining key-terms had been developed they needed to be integrated into courtlistener.com.
[Mike Lissner]: https://bitbucket.org/mlissner


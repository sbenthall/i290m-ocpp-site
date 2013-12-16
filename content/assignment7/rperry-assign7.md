Title: Modularity in the CiviCRM Community
Date: 2013-12-15 21:30 
Category: assignment7
Slug: rperry-assign7
Tags: i290m-ocpp, civicrm 
Author: Robyn Perry 
Summary: CiviCRM Modularity


The project itself is modular insofar as there are different pieces of functionality that are decoupled from each other. CiviCRM features CiviMail for sending communications, CiviContribute for managing donations, CiviEvent for managing events, and CiviMember, CiviCase, and CiviReport for their self-evident features. With few exceptions, each can be used completely independently from the others. 

My knowledge of the technical modularity of the project is related to what I can see, which is the forums, the documentation, and the conversations I've been part of. I have not contributed to code, so I am not familiar with the intimate details that would illuminate the degree of modularity of the project and its interlocking pieces. 

According to the bug tracker, there are four large buckets into which bugs are sorted: two are related to the main project, CiviCRM and infrastructure. The other two are somewhat special components that some CiviCRM users have invested in heavily but are not widely used: CiviHR contains all the bugs related to CiviCase, which is a component that tracks case management, and CiviVol, which are bugs related to [CiviVolunteer](http://civivolunteer.org/), an extension of CiviCRM currently under development that is being managed outside of the project proper. Reviewing the issue tracker, the two former sets of bugs (CiviCRM and Infrastructure) do seem to be handled by two different groups of people, with a bit of overlap. Tim Otten, Coleman Watts, and Adam Wight feature prominently on the infrastructure page as both reporters and assignees for bugs in 2013. There's greater diversity in reporters and assignees in the CiviCRM section; presumably this is where the bulk of the work and by extension, the bulk of the bugs, emerge.  

From my perspective, the community doesn't really mirror the modularity of CiviCRM components. There isn't further categorization of the CiviCRM bucket of bugs, and tasks are portioned out to whoever is available and capable of fixing them. Most developers declare themselves available and get regular assignments, but it seems that there is enough to do that they can also self-appoint by problem or module depending on what their clients' needs are and what they take a special interest in. 

So far, I've only talked about the ongoing development which is asynchronous. This ongoing work results in multi-annual new releases of CiviCRM, some minor, and usually fewer than 1 major release per year. The current version is 4.4, and CiviCRM has been around since 2005, so that's 4 major version releases in 8 years. 

There are also documentation and code sprints around which work is organized. This work is done synchronously, and usually consists in large gatherings of Civi community members in a single, physical place, often for a week or longer. These gatherings produce large chunks of documentation and code all at once, and they are a unique opportunity for developers and community members who may have only interacted virtually to connect and collaborate together.  
______________


My CiviCRM Contributions
------------------------
My project contributions amounted to two new additions to the main CiviCRM website. One is an introduction to the CiviCRM "universe" for newbies. I'm waiting for feedback from Michael and Dave about it, but my latest conversation with Michael determined that it was in pretty good shape. [Read the draft](https://docs.google.com/spreadsheet/ccc?key=0AjpFNt0c8qlVdFlXc2xPWFBRY0RFQ0FhSkY5eUlYNnc&usp=sharing).   

I've also written a FAQ page based on questions Dave gets asked all the time. It's still in revision and I'm waiting for feedback from Michael and Dave about it, but the draft is [here](https://docs.google.com/spreadsheet/ccc?key=0AjpFNt0c8qlVdG95dUdicXkyOUp5M0pLMXVXR1pGN1E&usp=sharing).

I also continued my role as a CiviCRM Ambassador an answered a number of inquiries from people interested in CiviCRM. Here's an example of one: 

Hi Julia! 

I'm glad you contacted me and are considering CiviCRM. Civi is flexible, although I've never used it for tracking GPAs or graduation rates. It takes an investment of time and some money and energy to make it worth it, but it could do the trick for you. 

CiviCRM lets track donations, communications, events, membership if needed, and a series of other activities related to your work with your constituency and donors. It is a web-based tool meaning anyone with access to it can access it in their browser anywhere they have an internet connection.

I have some thoughts about how you might track GPA and graduation rates. Basically, Civi lets you create custom fields for special data you want to track. I think a key thing to be able to do would be identify each cohort of students that's in the program, be able to determine all current students and those who have graduated (or not) to get a sense of numbers of students going through the program and success rates. These things would be possible in Civi but you really ought to have someone on staff dedicated to the work of getting this going (sounds like that's you!) and I'd highly recommend the services of a Civi expert who can walk you through the process of getting this set up. 

In my experience, this process takes quite a while and can require a big shift in an organization to really make it work the way you need it to. 

Steps in the set-process include the following: 

1. Get the site hosted and installed
2. Determine what data you'll want to track (this is ongoing/iterative as you better understand your needs overtime, but important to start with something)
3. Assemble the data you have in your organization that is what you want to put into the database (staff excel spreadsheets, records related to graduation rates that you have, GPA information wherever it may be, mailing lists, etc.)
4. Create a data dictionary which maps all the data you have into fields in CiviCRM. This involves making a plan for what new custom fields you're going to need. 
5. Get the data into shape for being able to import (make sure it's accurate, there are not duplicates, email addresses are valid, etc.)
6. Go through process of importing this data. (I would recommend finding someone who can really help you with this.) 
7. Develop processes in your organization to keep this data up to date. (This is ongoing and will take training, time, and buy-in!) 

A couple of people I recommend are Stu Gaston and MayFirst/PeopleLink (mayfirst.org) or Hershel at CiviHosting (http://civihosting.com/) to host your site. MayFirst has a more radical underpinning if your organization is dedicated to social justice. 

You may find some useful advice and even assistance at FreeGeek Chicago since they're local. I've met folks from there who are awesome, so someone may know about Civi or at least be able to point you in the direction of someone local who uses it/knows about it: http://freegeekchicago.org/about 

Good luck! 
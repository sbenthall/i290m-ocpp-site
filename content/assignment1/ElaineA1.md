Title: Elaine Assignment 1
Date: 2013-09-17 14:00
Category: Assignments
Tags: Assignment1
Slug: ElaineA1
Author: Elaine Sedenberg
Summary: In Assignment 1, I detail how Zooniverse (managed by Citizen Science Alliance) is organized, what technical and user interface platforms are used, and reached out to a local scientific data contributor.  


Elaine Sedenberg Assignment 1
---------------

Zooniverse is the self-proclaimed “largest, most popular and most successful citizen science projects” (1) on the web. Zooniverse is an intricate user interface created by the Citizen Science Alliance (CSA). CSA governs the activities and direction of Zooniverse and related projects, and works with the scientific community to develop new proposals for projects. In July 2007, the site began with a single project called Galaxy Zoo, which opened up data captured by the Hubble Space Telescope and the Sloan Digital Sky Survey in New Mexico for classification by mostly untrained “citizen scientists.” The project received over 70,000 classifications in 24 hours after launch, and had over 50 million classifications from over 150,000 users by the end of the first year. The success of this project led to multiple publications and the completion of an initial phase of the research, which led to additional projects in multiple disciplines. As of 9/17/13, Zooniverse had 864,706 registered users worldwide.

Zooniverse is designed to engage individuals with minimal training or experience in scientific research, so most of the backend technical design is completed by staff or partner research institutions.(2) CSA has clear guidelines for what types of research projects they are looking for and Zooniverse’s rational for how they optimally engage volunteers.(3) For example, CSA has a goal of making sure that new projects are only published when they are ready to collect data since projects receive the most contributions when they are newly released. CSA conducts beta testing with each new project using local volunteers or focus groups and then opens up the project for additional testing with existing users. CSA uses the science team (usually a partner institution that proposed the project) to conduct data validation and reduction to account for biases in observations or possibly weight user inputs based on individual past performance. 

Projects on Zooniverse are supported by the Zooniverse API (called Ouroboros) that presents users with scientific data in the form of images or video (among other formats) to an interface and then collects user-generated data back. CSA designed the API to be language agnostic so it could be expanded internationally. Ouroboros is a custom Ruby on Rails application (Rail 3.2) that stores data using MongoDB and Redis as a query cache. The API runs on Amazon Web Services. Recently, CSA posted the GitHub account (4) where you can monitor the back end technical development but it does not appear users can contribute code at this time. 

Zooniverse does offer multiple levels of engagement for member volunteers, or “Zooites.” Most Zooites contribute work through the main user interface where users select projects to contribute to and interact with associated research forums. (5) Newer projects, such as Galaxy Zoo Quench (6) offer opportunities for the community to collaborate on data analysis and writing up the results with the science team. There are also multiple dashboards developed by CSA to help visualize personal or group progress. (7)

CSA produces a blog that explains new projects, the Zooniverse backend, discusses technical problems, or successes of the various citizen projects. (8) Contributors to the blog appear to only be CSA employees, but it is updated regularly. Only minimal comments are posted to the blog from users. CSA additionally manages a Facebook and Twitter account. (9)

Zooniverse also actively contributes to open access journals (like arXiv’s Astro Ph) since they believe that open source science should result in open publications. CSA designed Zooniverse to be different than other earlier citizen science initiatives that focused on utilizing volunteer’s computer power (SETI Home). The only reference I have to a similar initiative is SciStarter, which might make an interesting citizen science project comparison. 

Since this is such a large project and CSA states on Zooniverse “Contact Us” that they receive many emails and may not respond to all correspondence, my intention for the first draft of Assignment 1 was to: (a) understand the organizational and technical structure of Zooniverse (CSA); (b) understand what data may be available for analysis of this community (mostly noted in footnotes); and (c) determine first steps in developing my Zooniverse project profile and contacting the organization. In my research, I discovered one of the Zooniverse Nature projects used entomology data from “CalBug” – a consortium of UC museums/libraries including the UC Berkeley Essig Museum of Entomology. I reached out to Peter Oboyski to see if I could talk about how they got involved with citizen science and Zooniverse specifically. He referred me to Joanie Ball who has been directly involved with the citizen science push from the beginning. My plan is to try and contact any local contributors or scientific contributors before reaching out to Citizen Science Alliance so I have more heft in my questions and interactions.

###References :

(1) https://www.zooniverse.org/about  
(2) List of partner institutions that contribute technical support or data to CSA (http://www.citizensciencealliance.org/partners.html) which includes UC Berkeley.  
(3) http://www.citizensciencealliance.org/downloads/zooniverse_guide.pdf  
(4) https://github.com/zooniverse/ Contains metadata about who contributes (staff members) and how the Zooniverse platform is developed is available, though it does not appear that code contributions from users are accepted. Interestingly enough, the technical director (Arfon Smith) just publically announced his resignation to go and work for GitHub as their “science guy.”  
(5) Example of a research forum for a project. (http://www.galaxyzooforum.org/). This is the oldest forum, so it has a much richer history (and generally more participation) than other newer forums. Newer projects host forums through the dashboard, (Example: http://talk.notesfromnature.org/#/boards) and contain metadata about the project. (Number of posts and participants in the Discussion).  
(6) http://quench.galaxyzoo.org/   
(7) http://tools.zooniverse.org/#/dashboards/galaxy_zoo, The Zootools dashboard offers a way for users to analyze group contributions and progress. This tool is in beta testing, and may be a good resource for this research project about the community. Additionally, http://live.zooniverse.org/ was launched in August 2013 and offers a real-time visualization on contributions made to the project.  
(8) http://blog.zooniverse.org/  
(9) https://twitter.com/the_zooniverse; https://www.facebook.com/therealzooniverse  


Attachment 1: Email correspondence with UC Berkeley Essig Museum of Entomology.
---------------

Hi Elaine,

I am going to pass you off to Joanie Ball who got us connected with Zooniverse and has been part of our citizen science initiative from the very beginning. I will be away for the next month and therefore will not be much help. But I would like to hear about your discussions with Joanie.

Pete


------------------------------------------------------------
Peter T Oboyski, PhD
Collections Manager & Senior Museum Scientist
Essig Museum of Entomology
1170 Valley Life Science Building
University of California, Berkeley

mailing address:
1101 VLSB, #4780
Berkeley, CA 94720

http://nature.berkeley.edu/~poboyski/
http://essig.berkeley.edu

essig.museum@gmail.com
510.643.0804 (work phone)
510.847.0360 (cell phone)

 
On Tue, Sep 17, 2013 at 1:57 PM, Elaine Sedenberg <elaine@ischool.berkeley.edu> wrote:
Hello,

I am a graduate researcher at the Berkeley School of Information and I'm beginning a research project comparing the structure and community engagement of citizen science initiatives. CalBug caught my attention, and I was wondering if it would be possible to to talk to someone in the library about the project and particularly your involvement in Citizen Science Alliance's Zooniverse.

Thanks,
Elaine


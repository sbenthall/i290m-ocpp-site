Title: CiviCRM background and structure
Date: 2013-10-07 20:30
Category: assignment
Slug: ljervis-assign2
Author: Lisa
Summary: On CiviCRM's history, purpose, community, ways of working--and mine.

History, purpose, alignment
---------------------------

As detailed in a 2006 [status report](http://civicrm.org/sites/civicrm.org/files/SSF_yearend_2006.pdf) on the project,
[CiviCRM](http://civicrm.org/) was launched in 2005 as the first open-source CRM software.
This report makes clear that its openness is both practical and ideological: 

>Technology is not a sufficient condition for raising nonprofit
>effectiveness. It is a well documented fact that technology only
>impacts corporate productivity when combined with changes in
>business process. Technology and business process together are
>necessary and sufficient conditions for increasing nonprofit
>effectiveness.
>
>We are building an open source ecosystem that allows us to tackle
>both the technology problem and the business process problem at
>the same time, relying on an existing nonprofit consulting
>industry to deploy CiviCRM and improve effectiveness.

>People and organizations contribute to CiviCRM development
>because they can sell business process services to large nonprofits.
>Small nonprofits benefit because the software is free and open
>source. Philanthropic resources can invest in solving the business
>process problems in small organizations in a sustainable, reusable
>and viral way. This is made possible by free technology and an
>open source community.

While there are many practical reasons I became involved with Civi--at my last job I worked
closely with an organization that is a big contributor; the product is much better suited
to organizations I work with than any other affordable CRM I have evaluated--the alignment 
of their stance with mine is profound. While I would phrase it quite differently from the 
author of the report quoted above, I strongly believe and my experience has borne out that
no matter how sophisticated, well-designed, or feature-rich your technological tools may be,
unless those tools are aligned with your work practices, they won't help. I also hold dear
many things that overlap with some important ideals of open source in general and Civi 
(perhaps because of its nonprofit focus) in particular: mutual aid, resource sharing, and
the like.

Community
---------

The [Civi website](http://civicrm.org/what/community) estimates the community at more than
 15,000 people, though they are not at all clear on who they're counting. So while 
 hard numbers may not be available, the developer 
 community is very robust, with [sprints](http://forum.civicrm.org/index.php?board=56.0)
 happening several times a year (for some reason the most recent sprint, happening this 
 week in London, is not listed here). Users, implementers, and developers (categories that 
 often overlap) hold [regular meetups, conferences, and trainings](https://civicrm.org/civi-upcoming-events). 
 The [forums](http://forum.civicrm.org/) are active—to the point of being overwhelming sometimes!
 
 Members are located all over the world: the core team (see "Project structure," below) 
 has members in the U.S., the U.K., and India; core contributors in those countries and 
 Australia, New Zealand, Mexico, and many countries in Europe. (I'm sure there are more locations
 for contributors--I just don't know what they are.) The user community is similarly global: 
 As noted on [an About page](http://civicrm.org/what/whatiscivicrm), "CiviCRM is localized in over 20 languages including: Chinese 
 (Taiwan, China), Dutch, English (Australia, Canada, U.S., UK), French (France, Canada), 
 German, Italian, Japanese, Russian, and Swedish."
 
 Infrastructure
-------------
 
 This far-flung project uses all the tools you'd expect: [the codebase in a version control system](http://github.com/civicrm/),
 a [bug tracker](http://issues.civicrm.org/jira/secure/Dashboard.jspa), [forums](http://forum.civicrm.org/), 
 a [developer wiki](http://wiki.civicrm.org/confluence/display/CRM/CiviCRM+Wiki), a [documentation wiki](http://wiki.civicrm.org/confluence/display/CRMDOC/CiviCRM+Documentation), 
 an IRC channel, and various [mailing lists](http://lists.civicrm.org/lists). 
 (Oh, and there are also [some](http://book.civicrm.org/) [books](https://www.packtpub.com/search?keys=civiCRM&op=Go&count=2&types=1&forthcoming=0&available=0&forthcoming=1&available=1).)
 
 While all this communication infrastructure is great, in my opinion it would be a huge
 benefit to the project if it were more streamlined. It's difficult for newcomers to get
 oriented and there's a lot of redundancy. And while I can't speak to the situation for
 contributing developers, for documentation people a lot of the resources are underused/
 out of date. The documentation roadmap hasn't been updated since January, there's been
 no traffic on the documentation email list in even longer, and a number of documentation 
 issues that have been identified to me over email as longstanding ones are not in the 
 issue tracker (which does have a documentation category). (This is something I'd like to 
 address with other community members and contribute to fixing, but I didn't want to lead
 with complaints in my first interaction in 18 months.)
 
 However, as a result of this overproliferation of communications infrastructure and in
  direct contradiction to [the best practices laid out by Karl Fogel](http://producingoss.com/en/technical-infrastructure.html),
  a lot of conversation about documentation happens over private email. 
 
Project structure
-----------------

Civi is maintained and run by community members led by and in partnership with 
a group of people known as the ["core team"](http://civicrm.org/what/coreteam)--
seven developers and one implementer who manage the community, decide what goes on the 
development roadmap, talk Civi up at conferences, write code, write documentation, 
and (I can only assume because this work is necessary and almost 
always invisible) tend to the day-to-day administrative work of running any kind of organization
 (payroll, tax filings, business licensing, etc.). 
 
 There are [core community members](http://civicrm.org/what/contributors) as well--consultants 
 who take part in sprints, write new modules, fix bugs, bring their clients' perspectives, 
 do community management, and more.
 
This information is gleaned from my involvement with Civi first as a 
user and then as a contributor on the documentation team; taking part in a sprint in the
 spring of 2012 was a very interesting window onto the project. While the 
phrase "the core team" was used a lot (as in "That's up to the core team," "Ask someone
on the core team," etc.), the core team members themselves were actively trying to 
discourage its use and the attendant distinctions between them and other members of the 
community. However, in my opinion a project this large needs more active management than could be provided
without a core team or similar body.


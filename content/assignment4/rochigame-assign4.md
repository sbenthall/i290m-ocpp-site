Title: Reflections on PeerLibrary governance
Date: 2013-11-12 7:30
Category: assignment4
Slug: rochigame-assign4
Tags: peerlibrary
Author: Rodrigo
Summary: From structurelessness to a benevolent dictatorship

The governance of PeerLibrary lacks a formal structure. The communication channels (IRC, [development mailing list](http://lists.peerlibrary.org/lists/info/dev)) are not moderated. Everyone who has ever contributed to the repository in any way (even just commenting on issues) has commit privilege. For a while, everyone was directly pushing to the `master` branch.

For practical reasons, much of the communication about development happens in person. We often meet on campus, typically at night in Hearst Mining Memorial Building or Sutardja Dai Hall. We always invite everyone by [announcing](http://lists.peerlibrary.org/lists/arc/dev/2013-10/msg00016.html) the meetings on the mailing list.

However, this architecture is vulnerable to some of the issues described by Jo Freeman in [The Tyranny of Structurelessness](http://www.jofreeman.com/joreen/tyranny.htm). For example, Freeman states:

> The inevitably elitist and exclusive nature of informal communication networks of friends is neither a new phenomenon characteristic of the women's movement nor a phenomenon new to women.

PeerLibrary has been an "informal communication network," especially in the beginning. I don't know if I can qualify the structure as elitist or exclusive, but I recognize that informality discourages new contributors from taking on significant design decisions. In PeerLibrary, even though everyone has commit privilege, I can't point to anyone who took the initiative to make decisions as a new contributor (except Mitar, who convinced us to rewrite the entire codebase in the first week). Our experience made me realize that governance has very little to do with _formal_ structure (e.g. commit privilege). Informally, we have very clearly become a benevolent dictatorship. Except in the early days, when everyone was pushing to `master`, nobody has made a contribution without Mitar's approval. Everyone who worked on the project lately (An, Anna, Seema) has essentially worked under Mitar's supervision. From Anna's and Seema's assignments:

> Many important decisions are spearheaded by the group's benevolent dictator, Mitar. [Anna, assign. 4](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/aswigart-assign4.html)

> The project leaders and core contributors (Mitar, Rodrigo, and Tony) are the members I turn to for direction on what to work on next and historical context for the project. [Anna, assign. 3](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/aswigart-assign3.html)

Mitar merits his status. He is the most active and experienced contributor. He is also does a good job explaining issues. Code quality has improved dramatically. Mitar and I joke that our development model is "depth-first development," since he likes perfection on every detail of every feature.

But how does the benevolent structure affect contributors' motivation? Seema thinks it is conducive to development:

> This [benevolent dictatorship] helps the team keep a check on all the new developments, keeps the team motivated and this is helps keep contributors from slacking off. [Seema, assign. 4](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/p-seema-assign4.html)

I disagree. PeerLibrary has seen very few contributions (from non-Mitars) after we moved to this model. The [contribution graphs](https://github.com/peerlibrary/peerlibrary/graphs/contributors) show that contributions have significantly dropped since then. I can't isolate governance structure as the cause, but my personal experience is that the strenuous process of adapting trivial contributions to Mitar's standards can be a bit demotivating. Also, the impression that Mitar has made a lot of extremely important decisions by himself has been particularly demotivating to me. For example, Mitar decided that we should have built-in security features to prevent users from reading non-OA papers, but we never discussed this publicly or as a group. Imagine working on the Open Access Initiative, and months later, being asked to implement controls for restricting access to papers...

This project could never have existed without Mitar, but he isn't fond of his own benevolent dictatorship either. His vision is a non-hierarchical community:

> What I would like to see is that we would be organized in a non-hierarchical community where common decisions are made consensually through constructive debate and arguments, but where in the case of equivalent arguments, we favor arguments of those who are more actively participating in PeerLibrary. Of course, those should pay attention to not overuse this favoring carelessly because the dissatisfied can in any moment decide not to participate anymore. That way, the whole project would be at loss. [Mitar, assign. 4](https://github.com/sbenthall/i290m-ocpp-site/blob/master/content/assignment4/mmilutinovic-assign4.md)

This vision is similar to what Seema has proposed:

> I would suggest that the group starte preparing for such a future and make all discussion and decision making through an online voting process. This would ensure that the voices of all the people in the group get heard, and people get into the practice of documenting all decisions made. [Seema, assign. 4](http://courses.ischool.berkeley.edu/i290m-ocpp/site/article/p-seema-assign4.html)

That is what I would also like to see... And such future may not be that far.
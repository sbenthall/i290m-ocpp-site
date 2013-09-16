I had a very easy time introducing myself to the community of the Free Law Project, otherwise known as courtlistener.com.  Dr. Carver directly gave me a VMWare image on a USB drive, some links to read and a video to watch[1].  He then sent a mail blast to everyone who had previously expressed an interest in the project, including myself, announcing the formation of a mailing list and writing a mini-bio of everyone.  This was the first time he had removed himself as the wheel-spoke of email communication and therefore was the first instance some of these people were communicating with each other directly.  Everyone wrote a short mail to the list introducing themselves, what their interest was in courtlistener.com, what they had or were planning to contribute and what their background was.  I followed suit stating that I was interested in courtlistener.com because of the intrinsic public good associated with lowering access barriers to the public record and that I would be contributing to courtlistener.com as part of a class I was taking on open collaboration and peer-production.  Unfortunately for everyone these mails were not archived because of some, now fixed, configuration problems with the Mailman program[2].

This was a pleasant change for me compared to my past experiences with open source development.  I have previously contributed or attempted to contribute to at least four different open source projects.  Only one of them had a pleasant outcome where a maintainer got back to me and accepted my changes.  The other three open source projects I attempted to contribute to never worked out.  Either because maintainers never got back to me after sending in patch requests or lack of follow up on submitted bugs.  The good project was TripleA and the 3 bad projects are dpkt, Scapy and the FreeBSD kernel.  

In the case of TripleA[3] I sent in a patch and got it incorporated into the next release.  It was my first real interaction with Open Source and I loved the feeling that people all over the globe were now using a feature I had implemented.

In the case of Scapy I reimplemented their DHCP request functionality since it was horribly broken.  Created a bug, sent them source code and then never heard a response.[4]

In the case of the FreeBSD kernel I discovered a kernel panic in their IGMP stack which I could reproduce easily but which never was investigated.  I even included example code to reproduce the issue[5] in my bug report.

In the case of dpkt I fixed numerous issues, developed new features and implemented new protocols[6] but I have never once heard a peep from any of the maintainers.  It's frustrating, but since I really need dpkt to work for my own open source baby hexcap[7], I will continue to use it.  I even had a conversation[8] with another developer when we both implemented a fix to the same bug and lamented the fact that none of the maintainers could bother talking to us.  I don't want to fork dpkt.  I want to work with the extremely skilled people who have marshaled it through success up to this point in history.  However I will be forced to fork dpkt, if by some interpretations I haven't already, if the current maintainers don't want to take my patches simply because I have to move forward with hexcap.

I don't regret contributing to projects where no one got back to me.  In both the FreeBSD and Scapy instances I had to do the work regardless of whether I shared it.  I needed the dhcp_request() function in Scapy to work for my job that I was getting paid for.  So I had no alternative to fixing it.  The additional act of sharing my changes cost me next to nothing.  In the case of FreeBSD I found a bug, reproduced it, isolated it, wrote it up and sent it in.  These actions did not cost me very much additional time beyond what I had already invested by finding the bug.

We don't have control over how maintainers will respond when we send them patches.  I understand people are busy and we are all stretched for time.  But if you're claiming to be the maintainer of a project then the least you should do is respond to people who are trying to help you.  If you are unable to do that then you should gracefully step aside and allow others to wear the hat of maintainer.  Especially if the role of maintainer grants you abilities that non-maintainers don't have such as access to the main source repository.

Thankfully the upshot of feeling frustrated when maintainers don't contact you is feeling thankful when they do take the time to contact you.  So in the case of TripleA I am very thankful that the maintainers took the time to contact me and accept my patch.  They got a patch for their game that helps it work better when displayed on overhead projectors.  I got to interact with smart people and know that thousands of people all over the world are interacting with something I made and finding joy in it.  Contributing to open source is addictive, and sending that first patch into TripleA set me on a path to rediscovering the joy of hacking that I had somehow lost in the process of adapting my passion to my profession.  So while I hope the next time I contribute to open source engenders collaboration, I'm not going to stop sending patches to maintainers even if they're too busy to accept them.  I still have many itches that need scratching[9].

*[1] http://people.ischool.berkeley.edu/~bcarver/juriscraper.html

*[2] Free Law Project Development Mailman archives http://lists.freelawproject.org/pipermail/dev/

*[3] http://sourceforge.net/p/triplea/mailman/message/21718648/

*[4]http://bb.secdev.org/scapy/issue/788/update-to-dhcp_request-in-dhcppy

*[5] http://www.freebsd.org/cgi/query-pr.cgi?pr=kern/167202

*[6]https://github.com/smutt/hexcap/tree/master/dpkt-read-only/dpkt

*[7]https://github.com/smutt/hexcap/

*[8]https://groups.google.com/forum/#!topic/dpkt/Y1ixQQdNjhY

*[9] The Cathedral and the Bazaar, Eric S Raymond, 1999, O'Reilly
Title: A brief history of bitcoin, namecoin
Date: 2013-10-07 10:23
Tags: bitcoin, namecoin
Slug: nmerrill-assign2
Author: Nick Merrill
Summary: Amidst Bitcoin turmoil, a look at the project's past.

## A general contextual update
This past week, drug trading site [The Silk Road](http://en.wikipedia.org/wiki/The_Silk_Road) was [seized](http://gizmodo.com/bitcoin-seized-from-silk-road-is-in-a-highly-prankable-1441808572) by the FBI. Since Silk Road trading accoutned for a large proportion of interest in Bitcoin, the value of [the currency dropped over 20% the days after the seizure](http://arstechnica.com/information-technology/2013/10/amid-silk-road-uncertainty-bitcoin-value-drops-over-20-in-3-hours/).* 

## Bitcoin: A mailing list, a history, a flood
> Why is the project open? Is it for ideological reasons, or practical reasons, or both?

Traditionally, Bitcion's origin is traced to Satoshi Nakamoto, the psuedonym of the developer(s) responsible for the modern Bitcoin project. However, upon interrogating a few developers, one learns that Bitcoin's history actually begins in 1998 on the cypherpunks mailing list. 

In an thread on banking, Wei Dai made an observation:

>  "Money is any object, or any sort of record, accepted as payment for goods and services and repayment of debts in a given country or socio-economic context,"

He coined - pardon this word choice - the term "cryptocurrency" to refer to a token of wealth that had no physical instantiation. Instead, the currency would be a cryptographic token that is assured, by the laws of physics and computation, to be unique. 

Bitcoin is open for ideological reasons. The cypherpunk mailing list was interested in ways to subvert government influence using code and cryptography. Bitcoin fully embodies Stallman's canonical "free as in freedom." 

However, from a practical stance, open sourcing bitcoin's code also allows the larger community to vet the currency's cryptographic standards, which helped to bolster its credibility in the long term. 

> How big is the community? Where are its members located? 

There is no knowable answer to this question. 138 people contribute to bitcoin's repository in github. Many of them are by Satoshi Nakamoto, who may be one or multiple hackers.

It is not known where bitcoin contributors are based. Gavin Andersson, a major contributor, is a well-known South African anarchist/crypto-libertarian. Most contributors hide their identities.

By nature of the project's design and aim, the number of people who use and trade bitcoin is unknowable. However, 11750000 bitcoins have been mined so far. So, the total value of bitcoins in circulation is about US$1,485,000,000. Although many of this coins may have been taken out of circulation (accidentally deleted, for instance), one imagines that hundreds of thousands of people must have some number of bitcoins.

## Bitcoin under the hood
> What sort of infrastructure does it use? Why does it use those tools and not other options?

Bitcoin's core code is written in Typescript, which is compiled into C++. Developers site C++'s speed as the foremost factor behind this choice of language.

However, bitcoin developers are quick to note that bitcoin could be ported to any language. One simply needs to implement certain algorithms properly and import bitcoin's blockchain. A few developers are experimenting with the creation of a Go version of bitcoin, hoping that the language's straightforward handling of concurrency could add efficiency to mining and trading.

I'd like to quickly reference a quote from [Tim O'Riley's conversation with Adam Turoff](http://oreillynet.com/lpt/wlg/3017):

> I briefly delved into Delphi many years ago. Attending a local Delphi users group had the feeling of a self-help group, where some people came across a key failing and traded coping strategies because there was no way to cause a change in Borland's product.

Judging from the #bitcoin-dev IRC channel, Bitcoin developers seem to feel much th same way. Even if patches are released, holes are fixed, etc, past mistakes are permanently written into Bitcoin's long blockchain. Unjustices (due to stealing, hacking, wallet problems, etc) will never be undone. 

And besides, Bitcoin is a mature project with many users. Radical change in core functionality or structure will not occur in the project's foreseeable future. It is unclear to me why Bitcoin developers continue to hack on this project under these conditions, but one imagines that ideological or political motivations play some role.



Title: Reaching out to Bitcoin's elusive community. 
Date: 2013-09-16 12:20
Category: assignment
Tags: bitcoin
Slug: nmerrill-assign1
Author: Nick 
Summary: Nick reaches out to Bitcoin's community. It's weird.

> “It’s very attractive to the libertarian viewpoint if we can explain it properly. I’m better with code than with words though.”

-Satoshi Nakamoto, 14 Nov 2008

There's not a lot of talk on Bitcoin's github page. Despite the repository's 136 contributors and 2,864 stars, its issues page is unbelievably sparse. Technical, to-the-point. In fact, there's not a lot of talk anywhere on Bitcoin's channels for official development.

Bitcoin bills itself as a "cryptocurrency" - an alternative to government-minted currencies, with no central regulatory authority. The value of the currency is assured by the computational difficulty of cracking each bitcoin's (BTC) cryptographic key. The authenticity of coins are verified by other peers in the network via a massively distributed verification system, making man-in-the-middle attacks near impossible.

One BTC is currently valued at $128.79 USD.

Perhaps it's the money that's at stake, or maybe it's the tin-foil-hat tendencies of the people who naturally flock to a project like Bitcoin, but most contributors are anonymous. Some (like Nakamoto, the pseudonym of the project's creator) identify themselves only by their PGP keys.

And the publicly visible development channels are quiet.

A "foundation forum" is accessible to "founding members," but not to normal contributors. A wiki is open to developers, but little discussion takes place here, and shockingly few edit wars.

IRC was my sole channel for an introduction. Here's an excerpt.

> **[11:45] <csmpls> Hi, I'm interested in contributing to the official bitcoin project. Is there a mailing list I can join?**
> [11:45] <Monday> if obama can get the Noble Peace Prize for waging war on countries like Libya and Syria, those propagandist who give the prize should give hitler the All-Time Noble Peace Prize Award
> [11:48] <michagogo> csmpls: There *is* a mailing list
> [11:48] <michagogo> ;;google bitcoin-dev mailing list
[…] 
> [11:49] <michagogo> I don't know how active it is, though
> [11:49] <michagogo> There's also the #bitcoin-dev channel
> [11:49] <neo2> csmpls, there's a #tor chan in irc.oftc.net
> [11:49] <Monday> the problem with Tor is that it started as a US military project and currently gets almost all of its funding from the US goverment

The conversation then turned to conspiracy theories surrounding the widespread use of high-fructose corn syrup.

Further discussions with the IRC channel introduced me to a few key pointers about the BTC project:

- The most holy rule in the project is that all contributors truly understand the BTC protocol, which is outlined [here](http://webchat.freenode.net/?channels=bitcoin&uio=d4).
- All relevant issues are on the Github page. If you think an issue is relevant, take it up on the Github page before you do anything else.

In the immediate future, I plan to attack a [bug](https://github.com/bitcoin/bitcoin/issues/2545) that prevents certain properties of a user's [wallet](https://en.bitcoin.it/wiki/Wallet) from being stored in OSX's keychain.

Email archives are found [here](http://sourceforge.net/mailarchive/forum.php?forum_name=bitcoin-development).

And [here](https://github.com/csmpls/bitcoin) is my fork of the BTC repo.




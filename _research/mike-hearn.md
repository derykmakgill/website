---
layout: post
title: Mike Hearn 
date: 2020-10-26
---

## [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009726.html)

> "It was _well_ .... understood that the users of Bitcoin would wish to protect its decenteralization by limiting the size of the chain to keep it verifyable on small devices."
>
>No it wasn't. That is something you invented yourself much later. "Small
devices" isn't even defined anywhere, so there can't have been any such
understanding.
>
>The actual understanding was the opposite. Satoshi's words:
>
>"At first, most users would run network nodes, but as the network grows
beyond a certain point, it would be left more and more to specialists with
server farms of specialized hardware."
>
>That is from [2008.](http://satoshi.nakamotoinstitute.org/emails/cryptography/2/#selection-75.16-83.14)
>
>Then he went on to talk about Moore's law and streaming HD videos and the
like. At no point did he ever talk about limiting the system for "small
devices".
>
>I have been both working on and using Bitcoin for longer than you have been
around, Gregory. Please don't attempt to bullshit me about what the plan
was. And stop obscuring what this is about. It's not some personality cult...the reason I keep beating you over the head with Satoshi's words is
because it's that founding vision of the project that brought everyone
together, and gave us all a shared goal.
>
>If Satoshi had said from the start, "Bitcoin cannot ever scale. So I intend it to be heavily limited and
used only by a handful of people for rare transactions. I picked 1mb as an
arbitrary limit to ensure it never gets popular."
>
>... then I'd have not bothered getting involved. I'd have said, huh, I
don't really feel like putting effort into a system that is intended to NOT
be popular. And so would many other people.
>
>Don't think you can claim otherwise, because doing so is flat out wrong.

## [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009726.html)

>Gregory, you are getting really crazy now. Stop it. The trend towards
mining centralisation is not the fault of Gavin or myself, or anyone else.
And SPV is exactly what was always intended to be used. It's not something
I "fixated" on, it's right there in the white paper. Satoshi even
encouraged me to keep working on bitcoinj before he left!
>
>Look, it's clear you have decided that the way Bitcoin was meant to evolve
isn't to your personal liking. That's fine. Go make an alt coin where your
founding documents state that it's intended to always run on a 2015
Raspberry Pi, or whatever it is you mean by "small device". Remove SPV
capability from the protocol so everyone has to fully validate. Make sure
that's the understanding that everyone has from day one about what your alt
coin is for. Then when someone says, gee, it'd be nice if we had some more
capacity, you or someone else can go point at the announcement emails and
say "no, GregCoin is meant to always be verifiable on small devices, that's
our social contract and it's written into the consensus rules for that
reason".
>
>But your attempt to convert Bitcoin into that altcoin by exploiting a
temporary hack is desperate, and deeply upsetting to many people. Not many
quit their jobs and created companies to build products only for today's
tiny user base.

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009711.html)

>The highest Bitcoin tx fees can possibly go is perhaps a
little higher than what our competition charges. Too much higher than that,
and people will just say, you know what .... I'll make a bank transfer.
It's cheaper and not much slower, sometimes no slower at all.
>
>And now consider that in many parts of the world bank transfers are free.
>
>They aren't actually free, of course, but they *appear* to be free because
the infrastructure for doing them is cross subsidised by the fees on other
products and services, or hidden in the prices of goods sold.
>
>So that's a market reality Bitcoin has to handle. It's already more
expensive than the competition sometimes, but luckily not much more, and
anyway Bitcoin has some features those other systems lack (and vice versa).
So it can still be competitive.
>
>But your extremely vague notion of a "fee market" neglects to consider that
it already exists, and it's not a market of "Bitcoin users buying space in
Bitcoin blocks". It's "users paying to move money".

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009711.html)

>Fees were added as a way to get money to miners in a fair and decentralised
way.
>
>Attaching fees directly to all transactions is certainly one way to use
that, but it's not the only way. As noted above, our competitors prefer a
combination of price-hiding and cross subsidisation. Both of these can be
implemented with tx fees, but not necessarily by trying to artificially
limit supply, which is economically nonsensical.

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009709.html)

>Satoshi did not ever
postulate economic constraints on growth. Back then the talk was (quite
sensibly) how to grow faster, not how to slow things down!

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009709.html)

>The one megabyte limit was nothing to do with anti spam. It was a quick
kludge to try and avoid the user experience degrading significantly in the
event of a "DoS block", back when everyone used Bitcoin-Qt. The fear was
that some malicious miner would generate massive blocks and make the wallet
too painful to use, before there were any alternatives.
>
>The plan was to remove it once SPV wallets were widespread. But Satoshi
left before that happened.

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009709.html)

>As is so often the case with Bitcoin Core these days, someone who came
along much later has retroactively decided that the work done so far fails
to meet some arbitrary and undefined level of perfection. 

#### [[bitcoin-dev] Why Satoshi's temporary anti-spam measure isn't temporary](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009709.html)

>Outside of serving lightweight P2P wallets there's no purpose in running a
P2P node if you aren't mining, or using it as a trusted node for your own
operations.
>
>And if one day there aren't enough network nodes being run by volunteers to
service all the lightweight wallets, then we can easily create an incentive
scheme to fix that.

#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009828.html)

>...you can't have a tiny high-value-transactions only currency AND
all the useful infrastructure that the Bitcoin community is making. It's a
contradiction. And without the infrastructure bitcoin ceases to be
interesting even to people who are willing to pay huge sums to use it.

#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009818.html)

>Quite possibly bigger blocks == more users == more nodes
and more miners.
>
>To repeat: it's not obvious to me at all that everything wrong with Bitcoin
can be solved by shrinking blocks. I don't think that's going to suddenly
make everything magically more decentralised.
>
>Centralization is not a single floating point value that is controlled by
block size. It's a multi-faceted and complex problem. You cannot "destroy
Bitcoin through centralization" by adjusting a single constant in the
source code.
>
>What people like you are Pieter are doing is making a single number a kind
of proxy for all fears and concerns about the trend towards outsourcing in
the Bitcoin community. Everything gets compressed down to one number you
feel you can control, whether it is relevant or not.

#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009818.html)

>Setting up an exchange is a lot of risky and expensive work. The motivation
is profit, and profits are higher when there are more users to sell to.
This is business 101.
>
>If you remove the potential for future profit, you remove the motivation to
create the services that we now enjoy and take for granted. Because if you
think Bitcoin can be useful without exchanges then let me tell you, I was
around when there were none. Bitcoin was useless.

#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009815.html)

>I see constant assertions that node count, mining centralisation,
developers not using Bitcoin Core in their own businesses etc is all to do
with block sizes. But nobody has shown that. Nobody has even laid the
groundwork for that. Verifying blocks takes milliseconds and downloading
them takes seconds everywhere except, apparently, China: this resource
usage is trivial.
>
>Yet developers, miners and users even outside of China routinely delegate
validation to others. Often for quite understandable technical reasons that
have nothing to do with block sizes.
>
>So I see no reason why arbitrarily capping the block size will move the
needle on these metrics. Trying to arrest the growth of Bitcoin for
everyone won't suddenly make Bitcoin-Qt a competitive wallet, or make
service devs migrate away from chain.com, or make merchants stop using
BitPay.

#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009815.html)

>A decentralised currency that the vast majority can't use doesn't
   change the amount of centralisation in the world. Most people will still
   end up using banks, with all the normal problems. You cannot solve a
   problem by creating a theoretically pure solution that's out of reach of
   ordinary people: just ask academic cryptographers!
   
#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009815.html)   
   
   >Growth is a part of the social contract. It always has been.
>
   >The best quote Gregory can find to suggest Satoshi wanted small blocks
   is a one sentence hypothetical example about what *might* happen if
   Bitcoin users became "tyrannical" as a result of non-financial transactions
   being stuffed in the block chain. That position makes sense because his
   scaling arguments assuming payment-network-sized traffic and throwing DNS
   systems or whatever into the mix could invalidate those arguments, in the
   absence of merged mining. But Satoshi did invent merged mining, and so
   there's no need for Bitcoin users to get "tyrannical": his original
   arguments still hold.
   
#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009815.html)   

>All the plans for some kind of ultra-throttled Bitcoin network used
   for infrequent transactions neglect to ask where the infrastructure for
   that will come from. The network of exchanges, payment processors and
   startups that are paying people to build infrastructure are all based on
   the assumption that the market will grow significantly. It's a gamble at
   best because Bitcoin's success is not guaranteed, but if the block chain
   cannot grow it's a gamble that is guaranteed to be lost.
>
  > So why should anyone go through the massive hassle of setting up
   exchanges, without the lure of large future profits?   
   
   
#### [[bitcoin-dev] Block size following technological growth](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-July/009815.html)     
   
>Bitcoin needs users, lots of them, for its political survival. There
   are many people out there who would like to see digital cash disappear, or
   be regulated out of existence. They will argue for that in front of
   governments and courts .... some already are. And if they're going to lose
   those arguments, the political and economic damage of getting rid of
   Bitcoin must be large enough to make people think twice. That means it
   needs supporters, it needs innovative services, it needs companies, and it
   needs legal users making legal payments: as many of them as possible.
>
>   If Bitcoin is a tiny, obscure currency used by drug dealers and a
   handful of crypto-at-any-cost geeks, the cost of simply banning it outright
   will seem trivial and the hammer will drop. There won't be a large scale
   payment network OR a high-value settlement network. And then the world is
   really screwed, because nobody will get a second chance for a very long
   time.   



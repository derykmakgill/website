---
layout: page
title: Bitcoin, Broken!
---

or

## A timeline history of Bitcoin: lies, propaganda, censorship, and more


## FAQ (maxis read this first)

**bcash is dead. Bitcoin moon. You lose. Why are you writing this?** I'll be the first person to admit in 2020 that the big-block Bitcoin fork experiment may be dead. Drama, network splits, bad decisions, and failure to grow quickly enough have made me less bullish on the success of Bitcoin Cash or Bitcoin SV than ever. But the failure of these experiments does not mean that Bitcoin itself shouldn't have continued along its intended scaling path, it only means that bootstrapping a minority chain may be impossible. Regardless, it is not my intention to prove that Bitcoin should not have changed to become something different than what Satoshi Nakamoto intended. It is only to document the history of how it changed, and to demonstrate that it was not technical or economic arguments that captured Bitcoin, but a social attack of lies, propaganda, threats, censorship, state action, and more.

**Are you a shitcoiner?** No, I believe only one coin can "win" and that the coin that wins will almost certainly be some version Bitcoin with the same database going back to the genesis block. I would not be surprised if BTC is that coin. I would however, be disappointed unless I saw serious improvements over the next few decades. Bitcoin promised to be a lot more than what BTC has thus far delivered. This document, essay, timeline—whatever you want to call it—will show that.

**Who the hell even are you?** Armchair researcher. I have no special qualifications whatsoever other than that I read a lot more than most people and have, not to flatter myself too much, a *very* good memory. But all more sources are cited and you can judge them for yourself. 

## Methods and Disclaimers

**Not for goldfish.** This is not a short narrative or listicle. It's a *very* long data-dump covering over a decade of history. It is organised chronologically and can be read straight through or by jumping around to dates that interest you. There is a *lot* of material here which has never before appeared together, and if I suspect the main criticism of this paper will be that I was rather not selective enough. If you want shorter essays, I can recommend John Blocke's fantastic essay on the [censorship of r/bitcoin](https://medium.com/@johnblocke/a-brief-and-incomplete-history-of-censorship-in-r-bitcoin-c85a290fe43) and Daniel Morgan's excellent [scaling debate timeline](https://hackernoon.com/the-great-bitcoin-scaling-debate-a-timeline-6108081dbada). If you're new to the history of Bitcoin, those are also good places to start before wade through this.

**No narrative claims.** I'm deliberately leaving out editorializing about grand conspiracies to co-opt Bitcoin. I have my own thoughts on that but in my own experience, starting with those claims tends to make people ignore the well-documented facts that show, whether the effort was intentional, coordinated, or not, it was corrupt, coercive, and effective. Instead I invite readers to form their own conclusions from the timeline of evidence and I hope people may see patterns that I did not. All of that said, I won't leave out information just because it lends itself to a particular theory. If I believe it is true, I have included it.

**Always incomplete.** I may add new material to this document in the future or edit existing material. If the edits are trivial—spelling, dates, typos, etc, I won't make a note of them. If the edits are because a piece of information I included as true was fundamentally wrong, I will do a strikethrough and add a linked footnote with a correction.

## 2010

**14 July 2010:** A <code>max_block_size</code> [value of 1MB](https://github.com/bitcoin/bitcoin/commit/a30b56ebe76ffff9f9cc8a6667186179413c6349#diff-118fcbaaba162ba17933c7893247df3aR2614) set on the client, effectively limiting the amount of transactions that could ever be processed on the Bitcoin network in a ten minute period.

It's important to understand that the 1MB block size limit was considered a temporary hack by Satoshi and everybody involved in Bitcoin at the time, as this fact would soon be swept under the rug.

**19 September 2010:** After some discussion, Hal Finney, Satoshi (Bitcoin’s creator), and the user ‘Cryddit,’ who is Ray Dallingerr, on Bitcointalk imposed a [1MB default block size](https://github.com/bitcoin/bitcoin/commit/172f006020965ae8763a0610845c051ed1e3b522) to reduce the chance of spam transactions hijacking blockspace, or the possibility of cheap DoS attacks. [Cryddit below explains why this limit was put in place:](https://bitcointalk.org/index.php?topic=946236.msg10388435#msg10388435)

>I'm the guy who went over the blockchain stuff in Satoshi's first cut of the bitcoin code.  Satoshi didn't have a 1MB limit in it. The limit was originally Hal Finney's idea.  Both Satoshi and I objected that it wouldn't scale at 1MB.  Hal was concerned about a potential DoS attack though, and after discussion, Satoshi agreed.  The 1MB limit was there by the time Bitcoin launched.  But all 3 of us agreed that 1MB had to be temporary because it would never scale.
>
>Several attempted "abuses" of the blockchain under the 1MB limit have proved Hal right about needing the limit at least for launching purposes.  A lot of people wanted to piggyback extraneous information onto the blockchain, and before miners (and the community generally) realized that blockchain space was a valuable resource they would have allowed it.  The blockchain would probably be several times as big a download now if that limit hadn't been in place, because it would have a lot of random 1-satoshi transactions that exist only to encode information for altcoins etc.
>
>At this point I don't think random schmoes who would allow just any transaction are getting a  lot of blocks. The people who have made a major investment in hashing power are doing the math to figure out which tx are worthwhile to include because block propagation time (and therefore the risk of orphan blocks) is proportional to block size. So at this point I think blockchain bloat as such is no longer likely to a problem, and the 1MB limit is no longer necessary.  It has been more-or-less replaced by a profitability limit that motivates people to not waste blockchain bandwidth, and miners are now reliably dropping transactions that don't pay fees. 

## 2011: The beginnings of censorship

**16 June 2011:** The original threads about the Silk Road on BitcoinTalk are [revealed to have been deleted,](https://bitcointalk.org/index.php?topic=17872.0) one of the earlier examples of censorship in Bitcoin. 

**29 June 2011:** One early Bitcoiner comments that the Bitcoin [forums are becoming a horrible place to discuss things](https://bitcointalk.org/index.php?topic=17872.msg304289#msg304289) because of moderators censoring old threads and trolls.

>forum.bitcoin.org is the single worst place on the internet to talk about bitcoin. Dissenting voices are regularly shouted down or dismissed as trolls. Moderators are now deleting longstanding threads of great interest. The worst part is, in bitcoin-forumland, the internet is nothing but America.

**19 July 2011:** r/bitcoin moderator u/AtlasLGo is [accused](https://bitcointalk.org/index.php?topic=30211.0) of trying to sell r/bitcoin. In the ensuing drama, someone contacts Reddit and he is removed along with three other mods we can see on the [WayBack Machine](https://web.archive.org/web/20110530125818/https://www.reddit.com/r/Bitcoin/new/) as late as May 2011.

Theymos becomes the new sole [moderator](https://bitcointalk.org/index.php?topic=30211.msg381922#msg381922) and refuses to allow the old ones back in. We see him as the sole moderator on the WayBack machine in [September 2011.](https://web.archive.org/web/20110927021847/https://www.reddit.com/r/Bitcoin/new/)

Now former moderator u/edzillion [recounted](https://www.reddit.com/r/btc/comments/84djb8/did_theymos_purchase_rbitcoin_in_2011/dvqcdvp?utm_source=share&utm_medium=web2x) the story years later: 

>Atlas was basically inactive - it seemed the modding was going just fine (it was a very positive community in those early days) but then one day without any warning we were all kicked. It seems atlas was chatting with people over IRC and they were like how can you sell it? and he booted all the other mods in preparation for a sale.
>
>This caused a total shitstorm, as you can imagine, and the community basically shouted loud enough that the orig mod backed down and agreed to hand it over to whoever the community decided, which was theymos.
>
>Theymos wasn't much better - wouldn't re-add any of the kicked mods and held it alone himself on some kind of power trip. Things got quite unfriendly after that - partially because theymos is a typical angry asshole libertarian, and partially because the scene grew so much that it was hard to maintain a close community.
>
>After a while of lobbying to get back in and failing, I gave up on it but I still feel disabused by that situation. I put a lot of good work into making bitcoin and r/bitcoin what it is today. We were all crazy wide-eyed zealots back then shouting it from the rooftops. I figured I at least deserved some kind of explanation, let alone my modship (which, let's face it is a somewhat useful position in the btc world).

## 2013

**18 April 2013:** Someone by the name of John Dillon (john.dillon892@googlemail.com) emails the bitcoin-development email list offering a $500USD reward to anyone who implements a transaction replacement-by-fee patch for Bitcoin.

John Dillon claimed in [leaked private emails](https://archive.is/PK1I1) that his day job is high up in a US intelligence agency. He says that he doesn't like what the government is doing and wants to make up for it by helping Bitcoin.

Peter Todd writes on BitcoinTalk that he is [considering claiming the bounty himself.](https://bitcointalk.org/index.php?topic=179612.msg1873593#msg1873593)

**17 May 2013:** Peter Todd releases a highly downvoted video on why the [blocksize limit keeps Bitcoin free and decentralized](https://bitcointalk.org/index.php?topic=208200.0) that is [paid for](https://bitcointalk.org/index.php?topic=208200.msg2292636#msg2292636) by the psuednonymous US intelligence agent John Dillon according to [leaked emails.](https://archive.is/PK1I1)

<script src="https://fast.wistia.com/embed/medias/j58llpj0w6.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div style="margin-bottom: 15px;" class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative; margin-bottom: 15px;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%; margin-bottom: 10px;"><div class="wistia_embed wistia_async_j58llpj0w6 videoFoam=true" style="height:100%;position:relative;width:100%; margin-bottom: 10px;"><div class="wistia_swatch" style="height:100%;left:0;opacity:0;overflow:hidden;position:absolute;top:0;transition:opacity 200ms;width:100%; margin-bottom: 10px;"><img src="https://fast.wistia.com/embed/medias/j58llpj0w6/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%; margin-bottom: 15px;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;" /></div></div></div></div>

The YouTube responses are mostly negative and some are worth looking more at.

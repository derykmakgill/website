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

**14 July 2010:** A <code>max_block_size</code> [value of 1MB](https://github.com/bitcoin/bitcoin/commit/a30b56ebe76ffff9f9cc8a6667186179413c6349#diff-118fcbaaba162ba17933c7893247df3aR2614) set on the client.

**19 September 2010:** After some discussion, Hal Finney, Satoshi (Bitcoin’s creator), and the user ‘Cryddit,’ who is Ray Dallingerr, on Bitcointalk imposed a [1MB default block size](https://github.com/bitcoin/bitcoin/commit/172f006020965ae8763a0610845c051ed1e3b522) to reduce the chance of spam transactions hijacking blockspace, or the possibility of cheap DoS attacks. [Cryddit below explains why this limit was put in place:](https://bitcointalk.org/index.php?topic=946236.msg10388435#msg10388435)

>I'm the guy who went over the blockchain stuff in Satoshi's first cut of the bitcoin code.  Satoshi didn't have a 1MB limit in it. The limit was originally Hal Finney's idea.  Both Satoshi and I objected that it wouldn't scale at 1MB.  Hal was concerned about a potential DoS attack though, and after discussion, Satoshi agreed.  The 1MB limit was there by the time Bitcoin launched.  But all 3 of us agreed that 1MB had to be temporary because it would never scale.
>
>Several attempted "abuses" of the blockchain under the 1MB limit have proved Hal right about needing the limit at least for launching purposes.  A lot of people wanted to piggyback extraneous information onto the blockchain, and before miners (and the community generally) realized that blockchain space was a valuable resource they would have allowed it.  The blockchain would probably be several times as big a download now if that limit hadn't been in place, because it would have a lot of random 1-satoshi transactions that exist only to encode information for altcoins etc.
>
>At this point I don't think random schmoes who would allow just any transaction are getting a  lot of blocks. The people who have made a major investment in hashing power are doing the math to figure out which tx are worthwhile to include because block propagation time (and therefore the risk of orphan blocks) is proportional to block size. So at this point I think blockchain bloat as such is no longer likely to a problem, and the 1MB limit is no longer necessary.  It has been more-or-less replaced by a profitability limit that motivates people to not waste blockchain bandwidth, and miners are now reliably dropping transactions that don't pay fees. 

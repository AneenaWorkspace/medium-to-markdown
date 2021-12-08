
> medium-to-markdown@0.0.3 convert
> node index.js "https://senatusspqr.medium.com/the-history-of-nano-part-1-from-founding-to-faucets-406192de643f"

The history of Nano: Part 1 — from founding to faucets.
=======================================================

[![Senatus](https://miro.medium.com/fit/c/56/56/1*dmbNkD5D-u45r44go_cf0g.png)](https://medium.com/?source=post_page-----406192de643f-----------------------------------)[

Senatus

](https://medium.com/?source=post_page-----406192de643f-----------------------------------)[

Sep 29·6 min read

](https://medium.com/the-history-of-nano-part-1-from-founding-to-faucets-406192de643f?source=post_page-----406192de643f-----------------------------------)

With Nano becoming ever more well known, the time seems right for a short history of Nano. For those that haven’t been around since the start it might add some colour, while for those that have been around since the very beginning it might bring back memories.

I generally try to make my articles tight — I can’t promise that for this series. I will be using both RaiBlocks, XRB, and Nano in this series, RaiBlocks being Nano’s old name before the [rebrand on 31st January 2018](https://medium.com/hackernoon/nano-rebrand-announcement-9101528a7b76), XRB being the old trade ticker. I added in as many links as possible, so that anyone interested can click through. With that said, let me start from the very beginning in this first part of Nano’s history.

![](https://miro.medium.com/max/1400/0*xUjFg6BHxR9Dqgyn.gif)

The start of RaiBlocks
======================

In 2014 Colin LeMahieu began development on a new distributed network with a novel architecture, [called the block lattice](https://bitcointalk.org/index.php?topic=928860.msg10198743#msg10198743).

> _The issue I was trying to solve was scalability: transactions per second and confirmation speed \[…\] With the account owner having authoritative control over their own chain, transactions don’t need to be mined for validity so confirmation time drops to near zero and transactions speed is as fast as they can be published._

After a few more months of developing while still working at his regular job at Qualcomm, [Colin made a new post to Bitcointalk](https://bitcointalk.org/index.php?topic=1208830.msg12689858#msg12689858), bringing the name RaiBlocks into the world for the first time.

> _We’ve been developing a system called RaiBlocks focusing on solving engineering problems of cryptocurrency specifically around transaction speed, eliminating transaction fees, and dropping the energy footprint i.e. removing mining._

Similar to Satoshi’s initial posts, not much attention was paid to Colin’s project at the time, with many of the replies expressing [skepticism](https://bitcointalk.org/index.php?topic=928860.msg10199658#msg10199658). Regardless, the threads provided valuable feedback and allowed Colin to further refine RaiBlocks.

> _From what I have understood so far, this is not really a blockchain, or even crypto related concept, in fact it sounds to me like you have proposed a new standalone transaction system. I don’t really see why you think that this concept is similar to sidechains, it rather sounds like a disitributed transaction server, with no need of a native currency. I saw you don’t have comments in the source code, so I won’t be spending much time for now to figure out what goes where._

During these early times, RaiBlocks moved from [a first commit to Github](https://github.com/nanocurrency/nano-node/commit/e387c894861f4d04dab24e2d230ef394e58eaffa) on May 1st 2014, to the [Dev Alpha version 1](https://github.com/nanocurrency/nano-node/releases/tag/VERSION_1) on November 11th 2014, to [Release Candidate 1 Version 7.0.1](https://github.com/nanocurrency/nano-node/releases/tag/V7.0.1) on September 20th 2015. This Release Candidate was the first version intended for more general usage.

Distributing RaiBlocks
======================

<img alt="" class="ef es eo ex w" src="https://miro.medium.com/max/1400/0\*L6VK5F8uNq1m5Nz8.png" width="700" height="131" srcSet="https://miro.medium.com/max/552/0\*L6VK5F8uNq1m5Nz8.png 276w, https://miro.medium.com/max/1104/0\*L6VK5F8uNq1m5Nz8.png 552w, https://miro.medium.com/max/1280/0\*L6VK5F8uNq1m5Nz8.png 640w, https://miro.medium.com/max/1400/0\*L6VK5F8uNq1m5Nz8.png 700w" sizes="700px" role="presentation"/>

With a year of work on RaiBlocks done and feedback gathered, RaiBlocks was released to the world. In October 2015, the [Genesis Block](https://nanolooker.com/block/991CF190094C00F0B68E2E5F75F6BEE95A2E0BD93CEAA4A6734DB9F19B728948) was created, bringing into existence 2¹²⁸ — 1 raw. Fully written out this amounts to 340,282,366,920,938,463,463,374,607,431,768,211,455 raw. To simplify this immense number, the decision was made to move the decimal 30 places to the left, leading to a total supply of 340,282,366.9 RaiBlocks.

The next challenge was to fairly distribute RaiBlocks. Nano’s consensus mechanism, Open Representative Voting, [depends on holdings-based voting](https://senatus.substack.com/p/the-basics-of-nano-why-its-such-an) where 1 Nano = 1 vote. Because of this, a broad distribution is essential in Nano. Traditionally, crypto distribution happens through either Proof of Work mining, or an [Initial Coin Offering](https://www.investopedia.com/terms/i/initial-coin-offering-ico.asp) (ICO). Both have cons — PoW means that those with strong mining machines gain most coins and PoW has a [negative environmental impact](https://senatus.substack.com/p/fight-the-climate-crisis-usenano-6e7c22d45b0e), while an ICO might get a coin into trouble with [securities laws](https://www.sec.gov/ICO) while favoring the rich with deep pockets.

> [_I worry about the legal grey-area that is ICOs and it’s not really a personal risk I want to take._](https://www.reddit.com/r/CryptoCurrency/comments/70wy52/im_colin_lemahieu_the_developer_of_raiblocks_a/dn6k6d9/)

The solution chosen instead was a [captcha faucet](https://medium.com/nanocurrency/the-nano-faucet-c99e18ae1202). Anyone with access to a computer or phone could solve captchas, and be rewarded with RaiBlocks.

Captcha faucets
===============

The captcha faucets almost warrant a post by themselves. Many different sorts of captchas were used. There were [audio captchas](https://www.youtube.com/watch?v=usnqk7p3wYw&t=11s&ab_channel=TutosLGLG) & [semi-manual captchas,](https://www.youtube.com/watch?v=IeQW_H7pf4A) people tried to develop software to [solve captchas faster,](https://www.youtube.com/results?search_query=raiblocks+captcha&sp=CAE%253D) people [hired others](https://bitcointalk.org/index.php?topic=1844032.0) to do captchas, and supposedly at one point the RaiBlocks captchas were using [10% of ALL Google captchas](https://imgur.com/qsnLN3o) per day.

The number of RaiBlocks you got per solved captcha varied over time. At some point, 1000 XRB were given out per solved captcha. The site hosting the captchas was open source, and included a paywall example integration where, for the low price of 1000 XRB, you could see a picture of.. a panda.

While this might seem like a ludicrously high price for a picture of a panda now, back then [Raiblocks were being sold](https://groups.google.com/g/raiblocks/c/K2VALKiP65w) for 300 [Satoshi’s](https://en.bitcoin.it/wiki/Satoshi_(unit)) each. At [historical prices](https://coinmarketcap.com/historical/20160424/), this amounted to a whopping $0.0000046 per RaiBlocks. That panda picture would only cost you $0.0046, and was a nice demonstration of the power of micropayments.

<img alt="" class="ef es eo ex w" src="https://miro.medium.com/max/1400/0\*iXo9dqKZHpNgCJaJ.png" width="700" height="394" srcSet="https://miro.medium.com/max/552/0\*iXo9dqKZHpNgCJaJ.png 276w, https://miro.medium.com/max/1104/0\*iXo9dqKZHpNgCJaJ.png 552w, https://miro.medium.com/max/1280/0\*iXo9dqKZHpNgCJaJ.png 640w, https://miro.medium.com/max/1400/0\*iXo9dqKZHpNgCJaJ.png 700w" sizes="700px" role="presentation"/>

Because anyone could participate, many users from developing countries such as Venezuela and Indonesia claimed RaiBlocks, which they then went on to either hold, use or resell, providing them with income.

For those wanting to dive deeper into the faucet distribution, the [RaiBlocks Google board](https://groups.google.com/g/raiblocks) allows you to scroll back to the discussions taking back at the time of the distribution. There is also this [captcha distribution audit](https://np.reddit.com/r/nanocurrency/comments/h7fmge/the_nano_faucet_distribution_visualized_and/) that was done by u/hanzyfranzy on Reddit. The captcha distribution process was very open, through an open-source website, allowing anyone to verify the sends on-chain, and with RaiBlocks’s founder posting both [updates and on-chain references](https://groups.google.com/g/raiblocks/c/FgCtvcPQQXY).

The first wallet, [RaiWebWallet](https://github.com/jaimehgb/RaiWebWallet), later known as Raiwallet, later known as Nanowallet, was officially introduced by Jaime Herrero during the faucet distribution, offering RaiBlocks users an easier way to transfer RaiBlocks.

<img alt="" class="ef es eo ex w" src="https://miro.medium.com/max/1392/0\*vUZsJi27A2DoGZov.png" width="696" height="504" srcSet="https://miro.medium.com/max/552/0\*vUZsJi27A2DoGZov.png 276w, https://miro.medium.com/max/1104/0\*vUZsJi27A2DoGZov.png 552w, https://miro.medium.com/max/1280/0\*vUZsJi27A2DoGZov.png 640w, https://miro.medium.com/max/1392/0\*vUZsJi27A2DoGZov.png 696w" sizes="696px" role="presentation"/>

[The faucet eventually closed](https://www.reddit.com/r/RaiBlocks/comments/76lhf6/ending_raiblocks_distribution/), after roughly two years, with 126,248,297 RaiBlocks distributed via captcha faucets. The initial plan had been to fully distribute all 340 million RaiBlocks, [over a 5-year period](https://groups.google.com/g/raiblocks/c/PSbX_onjLfU). There were several reasons for the early closure. Amongst others, current holders felt like the distribution (for ~2 years) led to a constant sell pressure. Many also felt like RaiBlocks wouldn’t start being taken more seriously until distribution was done and RaiBlocks was truly decentralized.

Following the closure of the faucet, 7,000,000 RaiBlocks were [sent](https://nanolooker.com/block/4270F4FB3A820FE81827065F967A9589DF5CA860443F812D21ECE964AC359E05) from the Genesis account to a [development fund](https://www.nanolooker.com/developer-fund), leading to a total supply of 133,248,297. The remaining, undistributed 207,034,069 Raiblocks were sent to the [burn account](https://nanocrawler.cc/explorer/account/nano_1111111111111111111111111111111111111111111111111111hifc8npp/history), an account that is mathematically inaccessible. In a video that due to Nano’s current price seems like a massive waste, you can see the RaiBlocks being sent to the burn account.

> The burn address was chosen because when decoded to hex, it is all zeroes. Mathematically, it is guaranteed that no one can know the private key. Additionally, in the ledger code, the burn address is coded to not be able to send or receive transactions, rendering the account useless. [Source](https://blog.nano.org/the-nano-faucet-c99e18ae1202).

When the faucet closed, RaiBlocks’s market cap was roughly $15 million. The end of distribution meant a further shift in focus towards development of the protocol. As a mark of this, Colin announced [he would start working on RaiBlocks fulltime](https://www.reddit.com/r/RaiBlocks/comments/7jch9q/colin_the_lead_developer_of_xrb_goes_fulltime_on/) on December 12th 2017, marking the start of the Nano Foundation.

This also marks the end of the first phase of Nano — its founding and distribution phase. The next articles will dive deeper into the subsequent pieces of history, starting with the frantic period of the 2017/2018 bullrun and the story of BitGrail.

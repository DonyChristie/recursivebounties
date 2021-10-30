## Recursive Bounties: More Powerful Than Normal Bounties

A standard [bounty](https://en.wikipedia.org/wiki/Bounty) is where you put out money for a thing to be done. For instance:
- _I will pay $150 for someone to house sit while I'm on vacation, or $20 if you refer me to someone who house sits for me while on vacation._
- _I will pay $1000 if you find a programmer I end up hiring._
- _I will pay $20000 if you find my missing child!_

A **recursive bounty** is a bounty that pays out not just to whoever fulfills the terms of the bounty, but fractally pays out to whoever referred them, whoever referred whoever referred them, whoever referred whoever referred whoever referred them, et cetera, up to 2x the cost of the original bounty in the limit.

As a bounty hunter, even if you don't have the means to fulfill the original request, you can refer the bounty to people in your network who are more likely to either fulfill the bounty, or know someone else who is either likely to fulfill the bounty, or continue the referral chain.

This means that, in the case of a bounty for a missing child, people will be much more incentivized to mobilize others to search for the child, because even if they don't find them directly and get $20000, they could refer someone who referred someone who referred someone who found them and you can get, let's see, 20000/2/2/2 is... $2500! Then it goes $1250, $625, $312.50... That kid is *much more likely* to be found when an entire country is tapping their network.

For more info, read here: [How Red Balloons On A Blockchain Will Change The World](https://hackernoon.com/how-red-balloons-on-a-blockchain-will-change-the-world-14c1c912e85b). That article is by the nCent project, who were working on this, but it seems like they dropped off the face of the Earth (e.g. their Telegram is dead and they haven't posted any updates). I think this is a really valuable idea so we should work on it.

I am interested in working on bounty infrastructure for communities of people who trust each other. However, I am guessing recursive bounties work best at scale rather than within small social trust graphs.

### Technical Challenges

1. Sybil-resistance. How to prove unique humanity and minimize fraud? (Important for lots of other crypto projects too.) Maybe import whatever GitCoin Grants is doing?
2. Even if everyone involved in a referral chain is a unique human: how to prevent someone from sharing the bounty with more people in their network than is necessary? Though I'd guess that is balanced out by the fact you'll get less of a payout if your referral chain actually succeeds? Unless your friends give you the money. How likely is that to happen, given that people like holding onto their money? Maybe there could be a recursive bounty put in place to report people who try this?
3. Should an MVP for this be built on a blockchain or web2 to start?
4. If/when blockchain: which one? Ethereum, Solana?

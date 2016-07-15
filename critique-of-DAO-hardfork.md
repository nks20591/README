
# About hard forks...

## Background

So I'm pretty much just a nobody in the Ethereum space, but I'm a bit of a purist.  Please keep that in mind, and if you're going to critique something in here, please make sure to read the whole things first.

Thanks.

I'm a really big fan of Ethereum, and the potential it opens.  I'm a huge fan of the idea of "code is law", and all the implications that come with the phrase.  It definitely opens the door to a huge number of issues, but I believe the issues that come with it are the sorts of things that can be solved through the maturation of the platform.  Tools can be developed for validating smart contracts, and utilities created that allow developers to write solid smart contracts without worry.  These are the sorts of things that come with age--and with necessity.

We find ourselves facing that necessity now.

## About principles

Ethereum is built on a few simple principles:  the immutability of the blockchain, the impartial governance of code, the finality of transactions, and the lack of centralized human governance.  All of these things come with significant penalties and drawbacks, as has recently become extruciatingly obvious.

Smart contracts that transact in a currency that holds significant amounts of value are the ultimate expressions of _caveat emptor_--as they should be.  It's the wild west out here, and it's up to the individual to make sure they're not being sold a vial of snake oil with their Ether.

These principles are the greatest strengths of the Ethereum ecosystem.  They guarantee that the things you do today will be engraved in a permanent record for all time (or, at least until the system fails and people stop caring).  This is the mechanism that drives one of the greatest benefits of blockchains: censorship resistance.

## About motivations

Today, I find myself in what appears to be the vocal minority about what to do in the Ethereum world.  My motiviation is to maintain the purity of those fundamental principles, by preventing the forking of Ethereum.  The loss of 15% of the total supply of Ethereum is a huge tragedy, yes--but if the goal is for Ethereum to be a long-lived platform, it's a sacrifice we _must_ be willing to make.  Breaking those principles, even once, sets a precedent--both legal and social.  I am not a lawyer, so I can't speak to the legal aspect, but I can speak to the social.

People like myself, those who feel the most strongly about the values that drive Ethereum--we're the ones who will leave if a hard fork happens.  Either we'll follow the uncompromising chain--or we'll move to another blockchain entirely.  When this happens, it won't become harder for fork again.  It will become vastly easier.  Without the voices advocating the loss of _value_ over the loss of _values_, the next time a non-protocol hard fork is proposed, it will be even easier to reach consensus on executing it.

The potential of this outcome alone is enough to nullify a lot of the arguments in favor of a hard fork.  To be fair, the "it'll be harder to fork in the future" argument should already be ignored outright--if it's possible for 15% of the stakeholders to successfully pass a hardfork, it's already far too easy.  That, and the argument is too hand-wavey.  It might be a very well-educated guess, but it's still a guess.

## On voting

Speaking of that 15%...  The passage of the soft-fork reveals a potentially fatal flaw in Ethereum's consensus mechanism already.

Let's take a step back.  Blockchain consensus rules generally state that the fork (soft or hard) with the greater hashpower wins.  This is the genesis of the term "51% attack"--the one with more than half the hashpower wins.

Consensus rules also generally state that a non-vote is a vote for the status quo--not updating your node (mining or otherwise) is a vote for things to stay how they are.  This is important:  there needs to be enough incentive for more than half the network to even care enough to vote, much less vote for a fork to happen.

However, with the advent of mining pools, some of these assumptions have fallen apart a bit.  With control over the vote being centralized to the pool operators, it becomes possible for a highly-motivated minority to influence the apathetic majority.  Some might argue that that's the fault of the apathetic members--but that's the whole point of the default vote being a vote against change.  The incentive structure needs to make it hard to change, requiring the _active_ participation of a majority to make a sweeping change to the protocol.

The second failing was putting the fork to a "vote" among the pools, and then making the decision off the results of that "vote".  The flaw here is subtle, but important: by splitting votes against change into "no voters" and "non-voters", it allows a highly-motivated minority to seize control of the network.  This is compounded by the nature of the vote itself, in which the majority of the incentives to vote _at all_ are incentives to vote yes.  In fact, my only incentive to vote "no" was on principle.

Unfortunately, "principle" is a poor motivator compared to monetary gain.

## On gains

Which leads me to my next topic nicely:  Economic outcomes of the hard fork.

Proponents of a fork will tell you that the hard fork will make DTHs "whole" (more or less).  Anyone who holds DAO tokens will obviously want to vote for a fork--it gives them the ability to turn their DAO tokens back into ETH, possibly even at a small profit.

For others, the incentive is the fact that the promised exchange rate in a post-fork world is < 100 DAO tokens for every ETH.  Given that the current exchange rate is > 100 DAO for every ETH, there is also incentive for people to amass DAO tokens and push the hard fork through.  Gambling on the success of the hard fork provides the opportunity for upwards of 30% profit in ETH (at current rates).

Unfortunately, the two above incentives for a fork care nothing about the long-term value of ETH.  As long as ETH's price relative to some other currency (BTC/fiat) remains stable enough, many of these people will cash out their DAO to ETH--and then immediately to BTC or fiat, to lock in their profits outside of the Ethereum ecosystem entirely.

This, of course, is bad for Ethereum as a system.

Furthermore, given the above exchange mechanics, this opens the door to "the attacker" successfully obtaining a bag of ETH in both the fork and non-fork outcomes.  We're reasonably certain he shorted ETH with a massive amount of BTC and leverage, meaning he already has won from an economic standpoint.  He could then compound this win by investing some (or all) of those earnings back into ETH by way of buying DAO tokens--and then cashing them out for ETH again when the fork passes.  Not only will he escape with a 30+% multiplier on his investment in DAO tokens--it'll also be impossible to link it back to the original attack, meaning he's free to use it however he wants.

If this is a desirable outcome to "the attacker", you can guarantee he's one of the ones advocating the passage of the hard fork.

## On shills

Which brings us to an interesting point.  The Ethereum reddit has been inundated with all forms of trolls... but most notable are the ones who claim that anyone with an anti-fork standpoint is a troll out to destroy Ethereum.

Interestingly, given the above economic incentives... it's most likely that the ones who are pro-fork are the real shills.  A guaranteed 30% profit (in ETH) is going to be a stronger motivator than the (potential) survival of Ethereum as a technology.

Also remember that money is an extremely powerful motivator--and the thought of losing/gaining a large quantity of money taints a person's judgement.  We're all human here, after all.  This isn't to say that people who hold DAO tokens and are proponents of a hard fork have bad arguments.  What is important is to remember that they're the ones who have the most to lose in this situation, and thus aren't the best suited for making a decision that has far-reaching and long-lasting effects on the ecosystem as a whole.  The thing that is top of mind for them is regaining what they've lost (or acquiring an opportunistic abitrage profit), not the health of the ecosystem.

After all, pro-fork DTHs have the opportunity to exit the ecosystem entirely--potentially at a profit.

Those of us who are here because it's something we believe in?  Not so much.

Source: https://gist.github.com/DeviateFish/936e02171b4d98eecf234e86a828cb4e#background

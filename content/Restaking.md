---
title: Restaking Everything, Everywhere, All at Once
---

Staking started as a way to secure networks. Now it’s becoming a market.

From proof-of-stake to liquid staking to restaking, we’ve seen a steady evolution in how blockchains source and coordinate trust. But the core problem of how to make security fully & simultaneously scalable, flexible, and risk-aware still hasn’t been solved.

ReSquared is building the next layer in that progression: programmable, cross-chain restaking infrastructure with risk analytics. This isn’t just about reusing stake across applications - it’s about turning staking into a fluid, interchain collateral layer, with visibility and control baked in.

Here’s how we got here, and where we’re taking it next.


# 0. The Entropy of Trust
Trust has always been expensive. In PoW, we paid for it with energy. In PoS, we pay with capital and lock it up. Either way, the cost to trust has been the bottleneck - an entropy tax on coordination.

Staking, over PoW, was supposed to fix that: a cleaner, leaner form of security. But the early iterations were naive. Tokens locked in chains, with no real visibility into the risks beneath the surface. Liquid staking helped with the unavailability of that capital, but didn’t solve the fundamentals. And restaking? A step forward, but a partial one. It reused security across apps, sure, but stayed anchored to specific chains and just as opaque in risk.

ReSquared expands the design space. We’re building cross-chain restaking infrastructure that’s token-agnostic, chain-agnostic, and quantitatively risk-aware. Stake anything, secure anywhere, and actually see what you’re exposed to. We’re not just building another restaking protocol, we’re building crypto’s programmable security rails.


# 1. Staking Began as a Monolith
In the beginning, there was Proof-of-Work: expensive, brute-force trust via raw energy expenditure. It worked, but coordination was hard, and environmental costs were harder. Proof-of-Stake upped the game. It replaced energy with economic skin-in-the-game: stake tokens, earn rewards, get slashed if you cheat. Simple.

Ethereum’s Merge marked the end of PoW’s reign. PoS became hegemonic. But early staking systems were still parochial - validator sets lived in silos, and capital was locked to a single chain. There was no mobility, no interoperability, no composability. Staking had gone green, but it hadn’t yet become what it could.


# 2. Staking’s Awkward Adolescence
The first phase of PoS was dead simple: stake, sit, earn. No abstractions, no flexibility. Liquid staking changed that. Protocols like Lido unshackled capital from lockups, enabling yield while keeping assets liquid. Staking became composable, but also, to some extent, more fragile.

The abstraction of validator behavior meant that, in certain cases, delegators often had no clue who they were trusting. Validators with wildly different performance and risk profiles were flattened into fungible tokens. Risk became more uniform and mispriced - no one was modeling exposure, and almost no one cared to do so publicly.

And even with all this innovation, staking remained confined. Your token could move across chains, but your trust couldn’t. Capital flowed, but security stayed stuck. Staking v2 was more efficient, but still fragmented, still blind.


# 3. Restaking and Its Limits
Restaking reframed the staking conversation. Instead of securing just a base chain, validators could now extend their security to applications, providing crypto-economic guarantees to new services without those applications having to spin up new validator sets. It was a breakthrough, championed by Eigenlayer.

But current restaking infrastructure has serious limits. It’s contained to single chains, with the vast majority of activity only on Ethereum. It’s semi-centralized, with AVS onboarding bottlenecked by core teams. And most importantly, it’s still blind to risk.

Slashing, in many cases, is treated like a switch: either it happens or it doesn’t. But in practice, validator behavior is (from the 3rd party perspective) probabilistic and interdependent. Failures cluster. Slashing events cascade. A system that can’t observe that in real time isn’t secure.


# 4. ReSquared: Staking Becomes Interchain Collateral
ReSquared breaks the single-chain paradigm. We’re building a restaking layer that’s chain-agnostic and token-agnostic. If it has value and can be locked, it can be restaked.

We don’t touch slashing logic. That belongs to the AVSs. We provide the rails: asset routing, validator coordination, trust accounting. Clean abstraction boundaries. Validators, AVSs, and delegators all plug into the same interchain trust layer, but retain flexibility over how they define and price risk.

The result? Validators can offer their services across chains. AVSs can source security from anywhere without spinning up their own validator sets. Delegators can restake across ecosystems. And ReSquared coordinates it all, without becoming a chokepoint.


# 5. Modeling Risk: What Others Ignore, We Quantify
Slashing isn’t binary, it’s a distribution. Validator behavior varies across chains, AVSs, market conditions. Some risks are structural. Some are economic. Some are self-induced by leverage or bad incentives.

ReSquared brings that complexity into focus. We analyze validator behavior across ecosystems and quantify exposure to correlated risk. We track looping, both through lending markets (e.g. restake–borrow–restake loops) and direct recursive restaking. We surface systemic tail risks that others might hand-wave.

We’re building a validator credit score that accounts for uptime, slashing history, economic leverage, and how widely restaked a validator is across chains and AVSs. Delegators will no longer be flying blind.

On top of that, our upcoming vault product will let both retail and institutional allocators allocate capital across risk bands, choosing their risk appetite without having to manage their own. Dashboards are planned to show exposure graphs, correlation matrices, and simulated stress tests. We don’t see visibility as a bonus, we see it as the baseline.


# 6. What’s Next: Programmable Security Coordination
If staking is becoming a market, restaking is becoming a pricing layer. On ReSquared, AVSs will be able to define their own slashing parameters - customized security requirements based on what they actually need. 

ReSquared helps to mediate that market. Validators can opt into AVS slashing terms with competitive rates. Delegators can allocate to validators based not just on returns, but on quantified risk.

Over time, this becomes a full security coordination layer. Validators evolve into yield-bearing oracles of trust. AVSs become programmable risk consumers. And ReSquared makes the whole system composable and transparent.

We’re not guessing at the future of restaking, we’re building its price discovery mechanism.


# 7. Conclusion: Security Is a Network Primitive
Staking’s final form isn’t monolithic. It’s fluid. Security should move as freely as value does. Capital and trust shouldn’t be locked into single chains - they should flow, reconfigure, and scale with demand.

ReSquared makes that possible. We’re building the pipes and the rating agency.
The Moody’s of modular security. The Bloomberg Terminal of restaking. The liquidity layer for trust itself.

Because in a world of interoperable apps and modular execution, security can’t stay static.
It has to become programmable infrastructure. That’s what we’re here to build.
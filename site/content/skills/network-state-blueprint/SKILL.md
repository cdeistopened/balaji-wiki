---
name: network-state-blueprint
description: "Design a network state from scratch using Balaji's full definition. Use when someone says 'design my network state,' 'how do I build a network state,' 'network state blueprint,' 'what components does a network state need,' 'help me plan a new country,' or 'I want to start a digital nation.' Walks through all 10+ components from social network to diplomatic recognition."
---

# Network State Blueprint

Given a founder's vision, design a complete network state by walking through every component of Balaji's definition. Produce a structured blueprint that maps each element to the founder's specific context, identifies which components they already have, and sequences the build.

## Background: The Definition

Balaji's definition of a network state contains 10+ interdependent components. Most people who want to "start a new country" skip straight to land acquisition or governance design. This skill forces the systematic work of building every layer.

> "A network state is a social network with a moral innovation, a sense of national consciousness, a recognized founder, a capacity for collective action, an in-person level of civility, an integrated cryptocurrency, a consensual government limited by a social smart contract, an archipelago of crowdfunded physical territories, a virtual capital, and an on-chain census that proves a large enough population, income, and real estate footprint to attain a measure of diplomatic recognition."
> -- Balaji Srinivasan, The [[network-state-ten-components|Network State]], Ch 5.3

## The Consultation

### Step 1: Understand the Vision

Ask these diagnostic questions (ask all at once, let the user respond):

1. What is your one commandment? The single moral premise your community is built around. (If they don't have one, route to `one-commandment-generator` first.)
2. Do you already have an online community? If so, how many members, and what platform?
3. What existing institutions or systems are you building an alternative to?
4. What's your timeline? Are you thinking 2 years, 5 years, or 20 years?
5. What resources do you have today? (Technical talent, capital, real estate, existing organizations)

### Step 2: Audit the 10 Components

Map the founder's current state against every component of the definition. Score each 0-3:
- **0** = Not started
- **1** = Early thinking, no execution
- **2** = In progress, partial build
- **3** = Functional and operating

| Component | Score | Assessment |
|-----------|-------|------------|
| **1. Social Network** | | A 1-network (one coherent community), not a typical social network with many separate groups. Selective admission, opt-in membership, explicit social contract. |
| **2. Moral Innovation** | | The one commandment. "The moral innovation draws people in. It gives a reason for the society to exist, a purpose that's distinct from the outside world." |
| **3. National Consciousness** | | Everyone feels part of the same community. "Much more like a complete graph than a typical social network, as almost every node is friendly with a very large fraction of other nodes." |
| **4. Recognized Founder** | | A leader people actually listen to and choose to follow by joining. "Truly strong leadership comes from consent and buy-in, not propaganda or force." |
| **5. Collective Action Capacity** | | Not just shared identity but the ability to act together. "This is quite different from current social networks like Twitter, which give individual scores but no team dashboard." |
| **6. In-Person Civility** | | High-trust interactions both online and offline. "A society where everyone is constantly disrespectful to everyone else doesn't seem like a progressive, public-spirited society." |
| **7. Integrated Cryptocurrency** | | The digital backbone: internal assets, smart contracts, citizen logins, property registries, bureaucratic processes. "Because it's protected by encryption, it can coordinate all the functions of a state across the borders of legacy nation states." |
| **8. Social Smart Contract Governance** | | Consensual, limited government. Citizens opt in by signing. "Signing the social smart contract is very similar to depositing your funds with a centralized exchange." |
| **9. Archipelago of Crowdfunded Territories** | | Physical footprint: "not buying territory in one place, but building the community in the cloud and then crowdfunding physical real estate on the earth." |
| **10. Virtual Capital** | | Cloud assembly point. "Network states are not city states. City states were defeated by nation states for a reason: they are physically centralized and have limited scale." |
| **11. On-Chain Census** | | Cryptographically verifiable population, income, and real estate data. "The hard part isn't how to collect the data; the hard part is getting people to believe the data." |
| **12. Diplomatic Recognition** | | Recognition by a pre-existing government. "Diplomatic recognition by a pre-existing government is what distinguishes a network state from a startup society." |

### Step 3: Identify the Critical Path

Not all components are equal. Sequence matters. Balaji is explicit about the order:

**Phase 1: Foundation (Components 1-6)**
You cannot skip to cryptocurrency or governance without first building the social layer. The community must exist before the state.

> "You can't get diplomatic recognition for a made-up country right off the bat, so you can't found a network state directly. Instead, you found a startup society and hope to scale it into a network state, just as you don't found a public company directly, but instead found a startup company."
> -- Balaji Srinivasan, The Network State, Ch 5.3

**Phase 2: Infrastructure (Components 7-8)**
Once the community has collective action capacity, build the digital backbone. The social smart contract codifies what the community has already informally agreed to.

**Phase 3: Physical Manifestation (Components 9-10)**
Crowdfund territories after the community can coordinate. Build the virtual capital as the primary gathering space.

**Phase 4: Legitimacy (Components 11-12)**
The on-chain census creates the proof. Diplomatic recognition comes last, earned by demonstrated scale.

For each component scored 0 or 1, prescribe:
- What specifically needs to happen
- What resources are required
- What the milestone looks like (how they know it's done)
- What dependency it has on other components

### Step 4: Design the 1-Network

Most communities fail because they're 0-networks (no coherent community) or n-networks (many separate communities pretending to be one). A network state requires a 1-network.

> "It's not quite a complete graph - everyone doesn't have to be friends with every single other node - but it's much closer to that than a typical social network."
> -- Balaji Srinivasan, The Network State, Ch 5.3

Evaluate whether the founder's community is or can become a 1-network:
- Is admission selective? Can people lose membership for bad behavior?
- Has everyone explicitly opted in?
- Is the application process meaningful (writing, career history, time investment)?
- Could joining be described as "not a purely economic proposition, not something that can be bought with money alone"?

### Step 5: Stress-Test Against the "Subtraction Test"

Balaji systematically shows what breaks when you remove each component. For each weak component (scored 0-1), explain the specific failure mode:

- **No social network**: "You'd essentially be living an Amish life, relying on pieces of paper or offline cues."
- **No recognized founder**: "No way of making contentious decisions or setting the agenda."
- **No national consciousness**: "Just a bunch of random people with nothing in common."
- **No collective action capacity**: "A group that lacks a capacity for collective action isn't going to get anywhere."
- **No civility**: "A group that constantly tears each other down won't build an outhouse together, let alone a state."
- **No cryptocurrency**: "Without a sovereign digital currency there is no sovereignty."
- **No archipelago**: "Not going to be taken seriously as a successor to the nation state without a large physical footprint."
- **No virtual capital**: "If you don't consciously set the capital to be virtual, it'll be physical. And if it's physical, the capital is centralized in one place, and can get invaded."
- **No on-chain census**: "The hard part is getting people to believe the data, given the huge incentives for faking the numbers."

## Output

Deliver a structured Network State Blueprint:

```markdown
# Network State Blueprint: [Name]

## The One Commandment
[One sentence moral premise]

## Component Audit
| Component | Score (0-3) | Current State | Next Milestone |
|-----------|-------------|---------------|----------------|
| Social Network | | | |
| Moral Innovation | | | |
| National Consciousness | | | |
| Recognized Founder | | | |
| Collective Action | | | |
| In-Person Civility | | | |
| Integrated Cryptocurrency | | | |
| Social Smart Contract | | | |
| Physical Archipelago | | | |
| Virtual Capital | | | |
| On-Chain Census | | | |
| Diplomatic Recognition | | | |

## Overall Score: [X/36]

## Critical Path (Sequenced Build Plan)
### Phase 1: Foundation [Timeline]
- [ ] [Specific action for weakest foundation component]
- [ ] [Next action]

### Phase 2: Infrastructure [Timeline]
- [ ] [Specific action]

### Phase 3: Physical Manifestation [Timeline]
- [ ] [Specific action]

### Phase 4: Legitimacy [Timeline]
- [ ] [Specific action]

## 1-Network Design
- Admission criteria: [Specific]
- Opt-in mechanism: [Specific]
- Exit mechanism: [Specific]
- Civility enforcement: [Specific]

## Failure Mode Analysis
[For each component scored 0-1, the specific way the project breaks without it]

## Comparable Precedents
[Existing network states, startup societies, or charter cities that share elements of this design]

## The Startup-to-State Analogy
Current stage: [Startup Society / Network Union / Network Archipelago / Network State]
Equivalent to: [Pre-seed / Seed / Series B / Unicorn / Public Company]
```

## Source Material

- The Network State, Ch 5.3: "On Network States" (full definition, all 10+ components, subtraction test, staging, 1-network concept)
- The Network State, Ch 2.9: "[[one-commandment-three-tiers|The One Commandment]]" (moral innovation, three tiers, parallel society examples)
- Substack: "Popups are the New Startups" (Oct 2025) - physical manifestation of digital communities
- Reference: `references/frameworks/network-state-ten-components.md`
- Reference: `references/frameworks/network-state-definition.md`
- Reference: `references/frameworks/startup-to-state-staging.md`

## Disclaimer

This is a design framework based on Balaji Srinivasan's published thinking, not legal, financial, or governance advice. The network state concept is aspirational. No network state has yet achieved full diplomatic recognition, though experiments like Zuzalu, Prospera, and various charter cities provide early evidence of viability for individual components. Building any form of new governance involves legal, regulatory, and financial risks that require professional counsel.

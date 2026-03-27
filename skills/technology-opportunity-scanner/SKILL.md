---
name: technology-opportunity-scanner
description: "Find startup opportunities by scanning for underexplored technology applications. Use when someone says 'where are the opportunities,' 'what should I build,' 'find me a startup idea,' 'what technologies are underappreciated,' or 'where hasn't technology moved in yet.' Applies Balaji's three-source framework for finding overlooked opportunities."
---

# Technology Opportunity Scanner

Identify startup opportunities by systematically scanning three sources: (a) technologies nobody knows about from the lab, (b) technologies people think are dead or have written off, and (c) industries where technology hasn't arrived yet. This is Balaji's contrarian approach to idea generation.

## The Consultation

### Step 1: Define the Search Space

Ask these questions:

1. What's your domain expertise? (What industries or technologies do you know deeply?)
2. What technologies have you personally written off as "dead" or "failed"?
3. What industries do you interact with that feel stuck in the past - where the tools haven't changed in decades?
4. Are you looking for a venture-scale opportunity ($1B+), a bootstrappable business, or something in between?

### Step 2: Apply the Three-Source Framework

Balaji identifies three specific places to look for startup opportunities that most people miss:

#### Source A: Lab Technologies Nobody Knows About

> "Set aside everything tech people are talking about, and look at the rest of human civilization."
> -- Balaji Srinivasan, The Anthology of Balaji

Scan for:
- Academic papers from the last 2-5 years in the user's domain
- Technologies that work in the lab but haven't been productized
- Research results that practitioners in the field haven't heard of
- Government-funded research that hasn't been commercialized

**Key question:** What do the researchers know that the industry doesn't?

#### Source B: "Dead" Technologies That Aren't Actually Dead

> "Look for things people think of as dead or as not having worked and find out why."
> -- Balaji Srinivasan, The Anthology of Balaji

Scan for:
- Technologies that failed 5-10 years ago but whose prerequisites have since been met
- Companies that died not because the idea was wrong but because the timing was wrong
- Technologies in the "trough of disillusionment" on the Gartner Hype Cycle
- Ideas that smart people have written off with confidence

**Apply the Idea Maze test:** Why did it fail before? Has something fundamental changed since then?

> "Virtual reality was an abject failure right up to the moment it wasn't. In this way, it has followed the course charted by a few other breakout technologies. They don't evolve in an iterative way, gradually gaining usefulness. Instead, they seem hardly to advance at all, moving forward in fits and starts, through shame spirals and bankruptcies and hype and defensive crouches - until one day, in a sudden about-face, they utterly, totally win."
> -- Quoted in The Network State, Ch 2.3

**Key question:** What's different now that would reverse the previous failure?

#### Source C: Industries Where Technology Hasn't Moved In

Scan for:
- Industries where the core workflow is still manual or paper-based
- Sectors where the "technology" is really just a digitized version of the old process (the "scanned PDF" stage)
- Fields where practitioners complain about their tools
- Markets where the existing software was built 15+ years ago and never meaningfully updated

**Key question:** Why hasn't technology penetrated this industry? Is it because of:
- Regulation (may change)
- Culture (may be disrupted)
- Complexity (may be solved by AI)
- Small market (may be growing)
- Incumbent lock-in (may be breakable)

### Step 3: Evaluate Each Opportunity

For each candidate opportunity identified, score on:

| Criterion | Score (1-5) | Notes |
|-----------|-------------|-------|
| **Technology readiness** | | Is the underlying tech mature enough? |
| **Market size** | | Is this a large or rapidly growing market? |
| **Contrarian angle** | | Do most smart people disagree this will work? |
| **Founder-market fit** | | Does this user have unique insight or access? |
| **Timing** | | Is this the right moment (trough, not peak)? |
| **Physical-to-digital gap** | | Is the industry stuck at "scanned version"? |

### Step 4: Apply the Stated vs. Expressed Preference Filter

For the top opportunities, apply Balaji's preference arbitrage test:

> "The gap between stated preference (what is praised) and expressed preference (what is bought) is an inexhaustible source of startup ideas. You can condemn hypocrisy. Or you can arbitrage inconsistency."
> -- Balaji Srinivasan, The Anthology of Balaji

Ask: In this market, is there a gap between what people *say* they value and what they *actually pay for*? If so, which side should you build for?

### Step 5: Map to the Physical-Digital Spectrum

For the strongest candidates, map where the industry sits on Balaji's physical-to-digital spectrum (see `skills/physical-to-digital-mapper/SKILL.md`):

| Stage | Description | Opportunity |
|-------|------------|-------------|
| **Physical** | No digital component at all | Massive opportunity but requires industry expertise |
| **Scanned** | Digitized version of old process | The sweet spot - digitize natively |
| **Intermediate Digital** | Some digital, some physical | Optimize the remaining physical parts |
| **Native Digital** | Born digital | Opportunity is in creating entirely new categories |

## Output

Deliver a structured Opportunity Scan:

```markdown
# Technology Opportunity Scan

## Search Parameters
- Domain expertise: [User's domain]
- Opportunity scale: [Venture / Bootstrap / Either]
- Time horizon: [How soon they need to start]

## Opportunities Identified

### Opportunity 1: [Name]
- **Source:** [Lab / "Dead" tech / Untouched industry]
- **The insight:** [What most people miss]
- **Why now:** [What changed to make this possible]
- **Physical-digital stage:** [Physical / Scanned / Intermediate / Native]
- **Preference gap:** [Stated vs. expressed preference arbitrage, if any]
- **Score:** [X/30]

### Opportunity 2: [Name]
[Same structure]

### Opportunity 3: [Name]
[Same structure]

## Recommended Deep Dive
[Which opportunity to explore first and why]

## Idea Maze Entry Point
[For the top opportunity, the first 3 turns in the idea maze]
```

## Source Material

- The Anthology of Balaji, pp. 193-197 (three sources of startup opportunities, Gartner Hype Cycle application, "set aside everything tech people are talking about")
- The Anthology of Balaji, p. 196 (stated vs. expressed preference, physical-to-digital spectrum)
- The Network State, Ch 2.3 (Idea Maze model, "unlike the laws of physics, society is not time invariant")
- Reference: `references/frameworks/idea-maze-deep-dive.md`
- Reference: `references/frameworks/physical-digital-native-spectrum.md`
- Reference: `references/frameworks/stated-vs-expressed-preference.md`

## Disclaimer

This is an idea generation framework based on Balaji Srinivasan's published thinking. Identifying an opportunity is the beginning, not the end. Every opportunity requires deep validation through customer discovery, technical feasibility assessment, and market analysis before committing resources.

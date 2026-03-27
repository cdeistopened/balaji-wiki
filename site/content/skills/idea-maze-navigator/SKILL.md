---
name: idea-maze-navigator
description: "Map the full idea maze for any startup concept. Use when someone says 'evaluate my startup idea,' 'what's the idea maze for X,' 'who else has tried this,' 'why hasn't this been done before,' or 'help me think through my startup.' Walks through dead companies, live competitors, technology shifts, and the specific path forward."
---

# Idea Maze Navigator

Given a startup idea, map its full idea maze: the dead companies that tried before, the live competitors, the technology shifts that opened or closed doors, and the specific path the founder proposes to take. Evaluate whether the founder has the bird's-eye view that separates winners from losers.

## The Consultation

### Step 1: Understand the Idea and the Founder's Map

Ask these diagnostic questions (ask all at once, let the user respond):

1. What's the startup idea in one sentence?
2. What do you know about previous companies that tried something similar? (Dead ones and live ones.)
3. What changed recently (technology, regulation, market, culture) that makes this possible now?
4. What's your specific path through the maze - which turns are you making that others didn't or won't?

**Why this matters:** Balaji extends Chris Dixon's original idea maze concept into a litmus test for founder quality. The maze is the landscape of all possible paths a startup could take, including the ones that lead to failure. A good founder has walked the maze in their mind before walking it with their company.

> "A good founder is capable of anticipating which turns lead to treasure and which lead to certain death. A bad founder just has a vague idea of 'treasure somewhere in the maze' without understanding the full landscape."
> -- Balaji Srinivasan, The Anthology of Balaji

### Step 2: Map the Maze

Using the founder's answers and your own knowledge, construct the full idea maze:

**Layer 1: The Graveyard (Dead Companies)**
- List companies that tried this or adjacent ideas and failed
- For each: what specific turn killed them? (Too early, wrong business model, wrong market, wrong technology bet, regulation, couldn't scale, ran out of money)
- Key question: Are any of these deaths now *reversible* due to changed conditions?

**Layer 2: The Battlefield (Live Competitors)**
- List current companies in adjacent space
- For each: what's their specific path through the maze? What turns have they made?
- Key question: Where is there white space the competitors haven't explored?

**Layer 3: The Doors (Technology & Market Shifts)**
- What doors were previously closed that are now open?
- What doors are currently closing?
- Apply Balaji's Idea Maze heuristic from Ch 2.3 of The Network State:

> "Just because a business proposition didn't work in the past doesn't necessarily mean it won't work today. The technological and social prerequisites may have dramatically changed, and doors previously closed may now have opened. Unlike the laws of physics, society is not time invariant."
> -- Balaji Srinivasan, The Network State, Ch 2.3

**Layer 4: The Hype Cycle Position**
- Where is the core technology on the Gartner Hype Cycle?
- Is this at trigger, peak, trough, slope, or plateau?
- Balaji's insight: the best time to enter is during the trough of disillusionment, when everyone has given up but the technology is actually maturing

> "Trigger event -> people get amped -> they try and find it's hard -> trough of disillusionment -> those who stick with it make things happen."
> -- Balaji Srinivasan, The Anthology of Balaji

### Step 3: Evaluate the Founder's Path

Score the founder's proposed path on these five dimensions:

| Dimension | Score (1-5) | What to Look For |
|-----------|-------------|-----------------|
| **Graveyard Knowledge** | | Can they name specific dead companies and explain why each died? |
| **Competitor Awareness** | | Do they know the specific turns competitors have made? |
| **Door Identification** | | Can they articulate what changed to make this possible now? |
| **Path Specificity** | | Is their proposed path through the maze specific or vague? |
| **Contrarian Clarity** | | Is their thesis genuinely contrarian, or consensus dressed as contrarian? |

**Scoring interpretation:**
- 20-25: Exceptional maze knowledge. This founder has done the work.
- 15-19: Solid but gaps. Identify which dimensions need deepening.
- 10-14: Dangerous gaps. They may be walking into a dead end they can't see.
- Below 10: They haven't walked the maze yet. They need to do research before building.

### Step 4: Identify the Contrarian Thesis

Every successful path through the idea maze requires a contrarian thesis - something the founder believes that most people (including smart people) disagree with.

Apply the "stated vs. expressed preference" test (see `references/frameworks/stated-vs-expressed-preference.md`):

> "The gap between stated preference (what is praised) and expressed preference (what is bought) is an inexhaustible source of startup ideas."
> -- Balaji Srinivasan, The Anthology of Balaji

Ask: Is there a gap between what people *say* they want and what they *actually do* that your startup exploits?

### Step 5: Prescribe Next Steps

Based on the maze map, prescribe:

1. **Research gaps**: Specific dead companies or competitors the founder needs to study
2. **Technology bets**: Which technology shifts to monitor or bet on
3. **Path adjustments**: Specific turns in the maze to reconsider
4. **Timing assessment**: Is this the right time, or should they wait for a specific trigger?

## Output

Deliver a structured Idea Maze Report:

```markdown
# Idea Maze Report: [Startup Name/Concept]

## The Maze Map
### Dead Companies
- [Company]: Died because [specific reason]. Relevant today because [changed condition].

### Live Competitors
- [Company]: Taking the [specific path] through the maze. Vulnerable at [specific point].

### Open Doors (What Changed)
- [Technology/market/regulatory shift]: Opens the door to [specific opportunity]

### Closing Doors
- [Trend]: This window is narrowing because [reason]

## Hype Cycle Position
[Technology] is at [stage]. This means [implication for timing].

## Founder Maze Score: [X/25]
| Dimension | Score | Notes |
|-----------|-------|-------|
| Graveyard Knowledge | X/5 | |
| Competitor Awareness | X/5 | |
| Door Identification | X/5 | |
| Path Specificity | X/5 | |
| Contrarian Clarity | X/5 | |

## The Contrarian Thesis
[One sentence: what this founder believes that most people disagree with]

## Stated vs. Expressed Preference Gap
[If applicable: the specific gap this startup exploits]

## Recommended Next Steps
1. [Specific research to do]
2. [Specific technology to monitor]
3. [Specific path adjustment]
4. [Timing recommendation]
```

## Source Material

- The Network State, Ch 2.3: "Political Power and Technological Truth" (Idea Maze model, Hype Cycle application, "unlike the laws of physics, society is not time invariant")
- The Anthology of Balaji, pp. 189-197 (Founding > Researching, idea maze deep dive, full-stack startup concept)
- Reference: `references/frameworks/idea-maze-deep-dive.md`
- Reference: `references/frameworks/stated-vs-expressed-preference.md`

## Disclaimer

This is an analytical framework based on Balaji Srinivasan's published thinking, not personalized investment or business advice. The idea maze is a thinking tool, not a prediction engine. Market conditions change, and past failures don't guarantee future success (or failure).

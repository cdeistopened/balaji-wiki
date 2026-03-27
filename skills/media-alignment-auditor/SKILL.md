---
name: media-alignment-auditor
description: "Evaluate a media outlet's incentive alignment between reader benefit and revenue model. Use when someone says 'is this media outlet trustworthy,' 'media bias analysis,' 'who funds this publication,' 'media incentive alignment,' 'is this journalism or propaganda,' 'media business model analysis,' 'why does this outlet publish what it publishes,' or 'how to evaluate a news source.' Maps the gap between what readers need and what the business model rewards."
---

# Media Alignment Auditor

Given a media outlet, publication, or information source, evaluate the alignment (or misalignment) between what benefits the reader and what benefits the outlet's business model. Identify structural incentives that push content toward or away from truth. Recommend realignment strategies.

## Background: Media Misalignment

Balaji argues that the central problem with modern media is structural, not individual. Journalists may be well-intentioned, but the business model rewards attention over accuracy. The incentive misalignment between reader benefit and revenue generation is the root cause of media dysfunction.

The Anthology of Balaji (Part II) lays out the diagnosis: media is misaligned with truth because the economic incentives point away from it. Creating "high-value media" requires restructuring incentives, not just hiring better journalists.

The core insight: media outlets are businesses. Understanding what the business model rewards tells you more about the content than reading the content itself.

## The Consultation

### Step 1: Identify the Outlet

Ask:

1. What media outlet, publication, or information source do you want to evaluate?
2. What's your relationship to this outlet? (Reader, advertiser, competitor, subject of coverage, investor)
3. What specific content from this outlet prompted your concern?
4. What decision are you trying to make? (Whether to trust their reporting, whether to advertise with them, whether to build a competing publication)

### Step 2: Map the Business Model

Identify how the outlet makes money. The revenue model determines the content strategy.

| Revenue Source | Incentive Created | Alignment Risk |
|---------------|-------------------|----------------|
| **Advertising (attention-based)** | Maximize pageviews, clicks, time on site | Content optimized for engagement, not accuracy. Outrage and controversy generate more revenue. |
| **Advertising (brand-based)** | Maintain prestige audience for premium advertisers | Content must not offend advertisers. Self-censorship on topics affecting major ad buyers. |
| **Subscription** | Retain subscribers, justify ongoing payment | Must produce content subscribers feel validates their subscription. Risk of echo chamber. |
| **Donor/Foundation funded** | Serve donor agenda | Content aligned with donor ideology, regardless of evidence. |
| **Government funded** | Serve government narrative | Content aligned with state interests. Censorship of inconvenient truths. |
| **Pay-per-article/micropayment** | Each piece must justify its price | Closer alignment with reader value, but incentive toward sensationalism for individual pieces. |
| **Community/membership** | Serve community interests | Closest alignment with reader benefit, but risk of groupthink. |

### Step 3: Evaluate the Five Alignment Dimensions

Score each 1-5 (1 = severely misaligned, 5 = strongly aligned):

**Dimension 1: Truth Incentive**
Does the business model reward publishing accurate information?

- Advertising model: Low. Corrections get fewer clicks than errors. Retractions are buried.
- Subscription model: Medium. Subscribers care about accuracy but also about confirmation.
- On-chain model: High. Cryptographically verified claims create accountability.

**Dimension 2: Correction Incentive**
When the outlet publishes something wrong, does the business model reward correcting it?

- How prominently are corrections displayed relative to original claims?
- Is there any financial penalty for publishing false information?
- Does the outlet track its prediction accuracy over time?

**Dimension 3: Reader-Revenue Alignment**
Does the outlet make more money when readers benefit?

- Is there a direct feedback loop between reader value and revenue?
- Can readers pay for what they find valuable, or are they the product being sold to advertisers?
- Would the outlet survive if it only published information that genuinely helped readers?

**Dimension 4: Source Independence**
Is the outlet financially independent from the subjects it covers?

- Does it accept advertising from companies it covers?
- Is it funded by foundations or governments whose activities it reports on?
- Are journalists' careers advanced by access to powerful sources (creating capture)?

**Dimension 5: Verifiability**
Does the outlet make it easy to verify its claims?

- Are primary sources linked?
- Is data downloadable?
- Are methodology decisions transparent?
- Could a reader independently verify the key claims?

Balaji's solution to media misalignment is ultimately technological: on-chain shadow statistics, cryptographically verified claims, and prediction market-backed journalism that has "skin in the game."

### Step 4: Identify the "Political Mascot" Dynamic

Balaji's concept from Ch 2.3 applies directly to media:

> "The political mascot model: history is written by winners pretending to be acting on behalf of losers."
> -- Balaji Srinivasan, The Network State, Ch 2.3

For the outlet being evaluated:
- Does it claim to serve a specific population (the poor, minorities, workers, consumers)?
- Does its actual coverage and business model benefit that population?
- Or does it use that population as a "mascot" to justify coverage that actually serves the outlet's own interests (engagement, political influence, advertiser relationships)?

### Step 5: Apply the Tripolar Media Lens

Map the outlet onto the NYT/CCP/BTC framework (see `tripolar-world-analyzer`):

- **NYT-aligned media**: Source of truth is institutional authority. Revenue from prestige advertising and elite subscriptions. Content reinforces the American establishment worldview.
- **CCP-aligned media**: Source of truth is party authority. Revenue from state funding. Content reinforces CCP narrative.
- **BTC-aligned media**: Source of truth is protocol/data. Revenue from community/crypto. Content is decentralized, often unedited.

Each has characteristic blind spots:
- NYT-aligned: Ignores stories that embarrass the American establishment
- CCP-aligned: Ignores stories that embarrass the Chinese party-state
- BTC-aligned: Ignores coordination failures of decentralization

### Step 6: Prescribe Realignment Strategies

Based on the audit, recommend strategies for consuming or building better-aligned media:

**For readers:**
- Diversify across all three poles (read NYT, Chinese sources, and crypto-native media)
- Weight sources that have skin in the game (prediction markets, short sellers, on-chain analysts)
- Apply truth-type classification (see `truth-type-classifier`) to every claim

**For media builders:**
- Align revenue with reader value (subscriptions > advertising, micropayments > attention metrics)
- Build in correction incentives (public prediction track records, correction prominence equal to claim prominence)
- Use cryptographic verification where possible (on-chain timestamps, verifiable data sources)
- Create "pre-narrative news" that presents facts before editorial framing

**For subjects of coverage:**
- Understand the outlet's business model before engaging
- Recognize that your story will be shaped by the outlet's incentives, not by accuracy
- Build direct communication channels (Substack, social media) that bypass media gatekeepers

## Output

Deliver a structured Media Alignment Audit:

```markdown
# Media Alignment Audit: [Outlet Name]

## Business Model
- Primary revenue: [Source]
- Secondary revenue: [Source]
- Estimated annual revenue: [If available]
- Ownership: [Who owns it and their other interests]

## Alignment Score: [X/25]

| Dimension | Score (1-5) | Evidence |
|-----------|-------------|----------|
| Truth Incentive | | |
| Correction Incentive | | |
| Reader-Revenue Alignment | | |
| Source Independence | | |
| Verifiability | | |

## Alignment Assessment: [Strongly Aligned / Moderately Aligned / Misaligned / Severely Misaligned]

## Incentive Map
- What the business model rewards: [Specific behaviors]
- What readers need: [Specific information]
- The gap: [Where these diverge]

## Political Mascot Analysis
- Claimed constituency: [Who the outlet says it serves]
- Actual beneficiary: [Who actually benefits from the coverage]

## Tripolar Position: [NYT-aligned / CCP-aligned / BTC-aligned / Mixed]
- Characteristic blind spots: [What this outlet systematically misses]

## Realignment Recommendations
[Specific recommendations for the user based on their role]

## Alternative Sources
[2-3 sources with better alignment for the topics this outlet covers]
```

## Source Material

- The Anthology of Balaji, Part II: "Modern Media Is Misaligned with Truth" (pp. 117-130), "How to Realign Media" (pp. 131-144), "Creating High-Value Media," "Aligning Incentives for Writers," "Building a Fact-Based Media"
- The Network State, Ch 2.3: "Political Power and Technological Truth" (political mascot model, atrocity stories, NYT as source of truth for American establishment, on-chain shadow statistics)
- The Network State, Ch 3.1: "NYT, CCP, BTC" (tripolar media landscape)
- Reference: `references/frameworks/media-realignment-strategies.md`
- Reference: `references/frameworks/five-truth-types.md`

## Disclaimer

This is an analytical framework based on Balaji Srinivasan's published analysis of media incentive structures. It is designed to encourage critical evaluation of information sources, not to dismiss all media as untrustworthy. All media outlets contain a mix of valuable journalism and structural biases. The framework does not assess individual journalists' integrity, only the structural incentives of the business model. It does not constitute media, legal, or investment advice.

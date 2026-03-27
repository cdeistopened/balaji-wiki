---
name: "Billion-Dollar Functions: The Atomic Unit of Startup Value"
description: "Catalog of billion-dollar functions from Balaji's examples, with the reduction method for identifying the single function that creates the most value in any company. Surface when someone asks about core competency, value creation, what makes a company defensible, or reducing a business to its essence."
type: framework
domain: startup-strategy
source: Balaji Srinivasan
chapters:
  - anthology p. 198
  - anthology pp. 200-202
---

## When to Use

You're trying to identify what actually makes a company valuable - not the mission statement, not the brand, not the headcount, but the single function that creates almost all the value. Or you're building a startup and need to decide what to focus on. Or you're evaluating a company and want to cut through the complexity to find the core.

## The Framework

### The Reduction Method

Balaji's approach is brutally reductive. Strip away everything about a company until you find the single function that, if removed, would destroy most of its value.

> "What's your billion-dollar function? For Facebook, it's arguably the function that allows advertisers to put ads in front of users."
> -- Balaji Srinivasan, The Anthology of Balaji

The billion-dollar function has a specific form:

```
output = f(input)
```

One input, one output. If you can't express it this way, you haven't found the atomic unit yet. Keep stripping.

### The Catalog

Balaji provides several canonical examples. Each reduces a company worth billions to a single function:

#### Google: Search Ranking
- **Function:** Given a text query, return an ordered list of the most relevant web pages.
- **Input:** User's search query (text string)
- **Output:** Ranked list of URLs with snippets
- **Why it's worth billions:** Every other Google product (ads, maps, shopping, YouTube recommendations) derives from the ability to rank relevance. The company that ranks best wins the attention, and attention is the currency of the internet.
- **Defensibility:** The ranking function improves with more data (search queries, click patterns, web crawl data). This creates a flywheel that makes the function harder to replicate over time.

#### Facebook: Ad Targeting
- **Function:** Given a user profile and advertiser targeting criteria, place the right ad in front of the right user.
- **Input:** User profile data + advertiser's target audience specification
- **Output:** Ad placement decision
- **Why it's worth billions:** The targeting function converts Facebook's social graph (which has no direct revenue) into advertising revenue. Everything else - the news feed, groups, messaging, the social graph itself - exists to generate the data that makes this function work.
- **Defensibility:** The function improves with more users (more targeting data) and more advertisers (more ad inventory optimization). Dual-sided network effects.

#### Geocoding Company: Address Resolution
- **Function:** Given a street address, return latitude/longitude coordinates.
- **Input:** Street address (text)
- **Output:** Geographic coordinates (lat/long pair)
- **Why it's worth billions:** Every location-based service (ride-sharing, delivery, mapping, real estate) depends on converting human-readable addresses to machine-readable coordinates. This is infrastructure.
- **Defensibility:** Requires a comprehensive, constantly updated database of addresses worldwide. The dataset is the moat.

#### Face Recognition: Identity Matching
- **Function:** Given a photograph of a face, identify the person.
- **Input:** Image (photograph)
- **Output:** Person identity (name, ID, confidence score)
- **Why it's worth billions:** Security, authentication, photo organization, surveillance, and social media tagging all depend on this function.
- **Defensibility:** The function improves with more training data (labeled face images). Quality depends on the dataset.

#### Machine Translation: Language Conversion
- **Function:** Given text in language A, produce equivalent text in language B.
- **Input:** Text in source language
- **Output:** Text in target language
- **Why it's worth billions:** Removes the language barrier for commerce, communication, content, and diplomacy across 7,000+ languages.
- **Defensibility:** Quality depends on parallel corpus data (matched sentences across languages). More data = better translation.

#### Counsyl: Genetic Risk Scoring
- **Function:** Given a DNA sample, determine carrier status for genetic conditions.
- **Input:** DNA sample (biological material)
- **Output:** Carrier status report (list of conditions with risk levels)
- **Why it's worth billions:** Enables prospective parents to understand genetic risks before pregnancy. Actionable, high-stakes medical information.
- **Defensibility:** Unlike the pure-software examples above, this function required the full stack to deliver - the DNA sample had to be collected, processed in a lab, sequenced, and analyzed. The function alone wasn't defensible; the full-stack operation was. This is why Counsyl went full-stack.

### The 1-2 Person Test

Balaji adds a crucial second test:

> "The billion-dollar function is the single function that, if a startup of one or two people could replicate it, would be worth a billion dollars."
> -- Balaji Srinivasan, The Anthology of Balaji

This test reveals what the actual moat is:

| If 1-2 people can replicate the function... | Then the moat is... |
|---------------------------------------------|---------------------|
| No, it requires massive infrastructure | The infrastructure itself (cloud computing, lab equipment, satellite networks) |
| No, it requires proprietary data | The dataset (user behavior, training data, proprietary measurements) |
| Yes, with current open-source tools | Distribution and brand (not technology) |
| Yes, with current AI capabilities | The moat is eroding - find a new one |

### The Support Infrastructure Distinction

Everything that isn't the billion-dollar function is support infrastructure. Balaji's framework forces you to categorize:

**Necessary support** (without this, the function can't operate):
- Data pipeline that feeds the function
- Distribution channel that delivers the function's output to users
- Trust/compliance layer that makes users willing to use it
- Customer support for edge cases

**Potential bloat** (exists for organizational rather than functional reasons):
- Features built before the billion-dollar function was identified
- Internal tools that serve politics rather than product
- Legacy systems that could be replaced
- Middle management layers that don't touch the function

### Three Strategic Implications

**1. Sharpen the Function**
If you've identified your billion-dollar function and it's not yet world-class, stop everything else. Every engineer, every dollar, every meeting should be in service of making this function better. Balaji's view is that most companies are distracted from their core function by organizational entropy.

**2. Full-Stack or Single-Layer**
The function determines the stack decision. If the function can stand alone and customers can access it directly (Google Search), stay single-layer. If the function needs surrounding infrastructure to deliver value (Counsyl's genetic scoring), go full-stack. See the full-stack framework for the detailed decision process.

**3. AI Displacement Risk**
In the current AI era, any billion-dollar function that can be expressed as `output = f(input)` where both input and output are text, images, or structured data is at risk of AI replication. The question is whether your function's quality advantage comes from:
- **Proprietary data** (hard to replicate - your moat holds)
- **Algorithmic innovation** (replicable within months - your moat erodes)
- **Scale/infrastructure** (expensive to replicate - your moat holds for now)
- **Regulatory barriers** (protected by law - your moat holds until law changes)

## Example

**Reducing Uber to its billion-dollar function:**

Strip away the app, the branding, the driver onboarding, the payment processing, the customer support, the mapping, the routing. What remains?

`driver_assignment = match(pickup_location, destination, available_drivers)`

That's it. The function that matches a rider's pickup location and destination with the nearest available driver. Everything else is support infrastructure. The matching function is what creates the marketplace efficiency that makes Uber possible.

The moat isn't the function itself (anyone can write a matching algorithm). The moat is the data: real-time driver locations, historical demand patterns, and the network effects of having enough drivers and riders in every city to make the matching function useful.

## Output

After reading this framework, you should be able to:
1. Reduce any company to its billion-dollar function using the `output = f(input)` test
2. Apply the 1-2 person test to identify the actual moat
3. Distinguish necessary support infrastructure from bloat
4. Assess AI displacement risk for any function
5. Connect the function to the full-stack decision

> Source: The Anthology of Balaji p. 198, pp. 200-202

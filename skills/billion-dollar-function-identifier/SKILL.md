---
name: billion-dollar-function-identifier
description: "Identify the single function that creates the most value in a business. Use when someone says 'what's the core of my business,' 'how do I find my billion-dollar function,' 'what should I focus on,' 'can my company be reduced to one function,' or 'what creates the most value in my startup.' Reduces a company to its essential value-creating operation."
---

# Billion-Dollar Function Identifier

Reduce any company or startup to the single function that creates the most value. Test whether that function can be built by 1-2 people, and if so, identify the moat that protects it from being replicated.

## The Consultation

### Step 1: Understand the Business

Ask these diagnostic questions:

1. What does your company do? (Not the mission statement - the actual operations.)
2. If you had to reduce your entire company to a single software function - one input, one output - what would it be?
3. How many people does it currently take to perform this core function?
4. What would happen if a competitor could replicate this function tomorrow?

### Step 2: Identify the Function

Balaji's framework is brutally reductive. Every great company can be reduced to a single function that creates almost all its value. Everything else is support infrastructure.

> "What's your billion-dollar function? For Facebook, it's arguably the function that allows advertisers to put ads in front of users."
> -- Balaji Srinivasan, The Anthology of Balaji

**Canonical examples from Balaji:**

| Company | Billion-Dollar Function | Input -> Output |
|---------|----------------------|-----------------|
| Google | Search ranking | Query -> Ordered list of results |
| Facebook | Ad targeting | User profile + advertiser criteria -> Ad placement |
| Uber | Ride matching | Pickup location + destination -> Driver assignment |
| Counsyl | Genetic risk scoring | DNA sample -> Carrier status report |
| A geocoding company | Address resolution | Street address -> Lat/long coordinates |
| Face recognition | Identity matching | Photo -> Person identity |
| Machine translation | Language conversion | Text in language A -> Text in language B |

**The test:** Can you express the core value creation as:

```
output = f(input)
```

If you can't reduce it to a single function, you haven't found the core yet. Keep stripping away until you get to the atomic unit of value creation.

### Step 3: Apply the 1-2 Person Test

Balaji's insight is that the most powerful functions can often be built by remarkably small teams:

> "The billion-dollar function is the single function that, if a startup of one or two people could replicate it, would be worth a billion dollars."
> -- Balaji Srinivasan, The Anthology of Balaji

Evaluate:

| Question | Answer | Implication |
|----------|--------|------------|
| Could 1-2 engineers build this function today? | Yes/No | If yes: the moat is data, not code |
| Could they build it with current open-source tools? | Yes/No | If yes: the moat is distribution, not technology |
| Could they build it with current AI capabilities? | Yes/No | If yes: the moat is eroding fast |
| What makes your version better than a fresh build? | | This is your actual moat |

### Step 4: Evaluate the Support Infrastructure

Everything that isn't the billion-dollar function is support infrastructure. Some of it is necessary, some is bloat. Map it:

**Necessary support** (enables the function to work):
- Data collection (feeds the function)
- Distribution (gets the function to users)
- Trust/compliance (makes users willing to use the function)
- Customer support (handles edge cases the function can't)

**Potential bloat** (exists for historical or organizational reasons):
- Functions that existed before the billion-dollar function was identified
- Features that serve internal politics rather than user value
- Legacy systems that could be replaced

### Step 5: Determine Strategy

Based on the function identification, prescribe one of three strategies:

**Strategy A: Sharpen the Function**
If the function is identified but not world-class, focus all resources on making it better. Everything else is a distraction.

**Strategy B: Build the Full Stack**
If the function alone isn't defensible (because anyone can replicate it), you may need to go full-stack. This is the Counsyl lesson:

> "You cannot automate something until you've done it manually many times."
> -- Balaji Srinivasan, The Anthology of Balaji

See the Full-Stack Startup Evaluator (`skills/full-stack-startup-evaluator/SKILL.md`) for the complete framework on when and how to go full-stack.

**Strategy C: Sell the Function**
If the function is powerful but you don't need to own the full stack, package the function as an API or service and sell it to others who do own the stack.

## Output

Deliver a structured Billion-Dollar Function Analysis:

```markdown
# Billion-Dollar Function Analysis: [Company Name]

## The Function
**In plain English:** [What it does]
**As code:** output = f(input)
- Input: [What goes in]
- Output: [What comes out]
- Value created: [Why this output is worth money]

## The 1-2 Person Test
| Question | Answer | Implication |
|----------|--------|------------|
| Could 1-2 engineers replicate this? | | |
| With open-source tools? | | |
| With current AI? | | |
| Actual moat: | | |

## Support Infrastructure Map
### Necessary
- [Function]: [Why it's necessary]

### Potential Bloat
- [Function]: [Why it may be unnecessary]

## Recommended Strategy: [A/B/C]
**Rationale:** [Why this strategy fits]

## Action Items
1. [Specific next step]
2. [Specific next step]
3. [Specific next step]
```

## Source Material

- The Anthology of Balaji, p. 198 (billion-dollar function concept, Google/Facebook/geocoding examples)
- The Anthology of Balaji, pp. 200-202 (full-stack startup, Counsyl case study)
- Reference: `references/frameworks/billion-dollar-functions-examples.md`
- Reference: `references/frameworks/full-stack-vs-layer-analysis.md`

## Disclaimer

This is a strategic analysis framework based on Balaji Srinivasan's published thinking. Company valuations depend on market conditions, execution, timing, and many factors beyond the scope of any single framework.

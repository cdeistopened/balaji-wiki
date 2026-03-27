---
name: full-stack-startup-evaluator
description: "Evaluate whether a startup should go full-stack (vertically integrated) or sell a single layer. Use when someone says 'should I vertically integrate,' 'full stack vs. API,' 'should I own the whole stack,' 'build vs. partner,' or 'Counsyl model.' Walks through the build-buy-partner decision for each layer of the stack."
---

# Full-Stack Startup Evaluator

Assess whether a startup should go full-stack (vertically integrated, controlling every layer from technology to customer delivery) or sell one layer of the stack to other companies. Identify the upgrade sequence and staging plan.

## The Consultation

### Step 1: Map the Stack

Ask these diagnostic questions:

1. What's the end-to-end process for delivering value to your customer? Walk me through every step from when they first discover you to when they receive value.
2. Which of these steps do you currently own vs. rely on partners/vendors for?
3. Have you tried selling just your technology/software to other companies who own the rest of the stack? What happened?
4. What's the biggest bottleneck or quality problem in your stack right now?

### Step 2: The Counsyl Lesson

Balaji's canonical example of the full-stack startup is Counsyl, the genetic testing company he co-founded. The lesson is fundamental:

> "Counsyl couldn't survive selling bioinformatics alone. It had to build the full clinical lab, the software, the sales force - the entire stack from sample collection to report delivery."
> -- Balaji Srinivasan, The Anthology of Balaji

**Why Counsyl went full-stack:**
1. The bioinformatics alone wasn't defensible (anyone could replicate the algorithm)
2. The existing labs had no incentive to adopt new software (it threatened their workflow)
3. Quality control required owning every step (a single weak link ruined the output)
4. The customer experience required end-to-end ownership (doctors needed one throat to choke)

**The general principle:**

> "You cannot automate something until you've done it manually many times."
> -- Balaji Srinivasan, The Anthology of Balaji

This means: before you can build the elegant software layer, you need to understand every manual step in the process by doing it yourself.

### Step 3: Apply the Full-Stack Decision Framework

For each layer of the user's stack, evaluate:

| Layer | Own It? | Key Question |
|-------|---------|-------------|
| **Technology/Algorithm** | | Is this defensible on its own? |
| **Data Collection** | | Do you need proprietary data the technology layer depends on? |
| **Operations/Fulfillment** | | Does quality require controlling this step? |
| **Sales/Distribution** | | Can you reach customers without owning this? |
| **Customer Experience** | | Does the end-user need a single integrated experience? |
| **Compliance/Trust** | | Does the regulatory environment require vertical integration? |

**Decision triggers for going full-stack:**

1. **Layer rejection**: When you try to sell your technology layer to incumbents and they won't adopt it (because it threatens their existing workflow or business model)
2. **Quality dependency**: When the output quality depends on controlling every step, and a single weak partner ruins the product
3. **Customer expectation**: When the customer expects one provider, not a patchwork of vendors
4. **Regulatory mandate**: When compliance requires end-to-end auditability

**Decision triggers for staying single-layer:**

1. **Layer adoption**: Incumbents eagerly adopt your technology (Stripe's model - payments layer only)
2. **Quality independence**: Your layer's quality doesn't depend on other layers
3. **Market efficiency**: Other layers are well-served by existing providers
4. **Capital efficiency**: You can't afford to build every layer simultaneously

### Step 4: Balaji's Full-Stack Examples

Apply these proven patterns:

| Industry | Full-Stack Version | What "Full Stack" Means |
|----------|-------------------|------------------------|
| **Healthcare** | Counsyl, One Medical | Own the lab AND the software AND the clinical workflow |
| **Law** | Full-stack law firm | Own the technology AND the legal practice AND client management |
| **Accounting** | Full-stack accounting firm | Own the software AND the bookkeeping AND the advisory |
| **Architecture** | Full-stack architecture firm | Own the design software AND the design practice AND construction management |
| **Food** | Full-stack restaurant | Own the supply chain AND the kitchen AND the delivery |
| **Education** | Full-stack school | Own the curriculum AND the teaching AND the credentialing |

### Step 5: Design the Upgrade Sequence

If going full-stack, the order matters. You can't build everything at once. Map the staging plan:

**Phase 1: Own the Core Function**
Start with the layer that contains your billion-dollar function (see `skills/billion-dollar-function-identifier/SKILL.md`). Build this first and prove it works.

**Phase 2: Own the Adjacent Bottleneck**
Identify which adjacent layer is the biggest quality bottleneck or adoption barrier. Build or acquire that next.

**Phase 3: Expand to Customer-Facing Layers**
Once the core and adjacent layers work, expand toward the customer. This is when you go from B2B (selling to other companies) to B2C (serving end customers directly).

**Phase 4: Optimize the Full Stack**
With the complete stack under your control, optimize end-to-end. This is where the real competitive advantage emerges - you can make tradeoffs across layers that no single-layer company can.

## Output

Deliver a structured Full-Stack Assessment:

```markdown
# Full-Stack Assessment: [Company Name]

## Current Stack Map
| Layer | Status | Owner | Quality Rating |
|-------|--------|-------|---------------|
| [Layer] | Own/Partner/Missing | [Who] | 1-5 |

## Full-Stack Decision
**Recommendation:** Go Full-Stack / Stay Single-Layer / Hybrid
**Primary reason:** [Layer rejection / Quality dependency / Customer expectation / Regulatory mandate]

## If Full-Stack: Upgrade Sequence
### Phase 1: [Layer to build first]
- Why first: [Reason]
- Timeline: [Estimate]
- Investment: [Rough order of magnitude]

### Phase 2: [Next layer]
- Why next: [Reason - usually the bottleneck]

### Phase 3: [Customer-facing expansion]
### Phase 4: [Full optimization]

## Risks
- [Risk 1]: [Mitigation]
- [Risk 2]: [Mitigation]

## Comparable Full-Stack Companies
- [Company]: [How they staged their full-stack build]
```

## Source Material

- The Anthology of Balaji, pp. 200-202 (full-stack startup concept, Counsyl case study, "you cannot automate something until you've done it manually many times")
- The Anthology of Balaji, p. 198 (billion-dollar function, relationship between function and stack)
- Reference: `references/frameworks/full-stack-vs-layer-analysis.md`
- Reference: `references/frameworks/billion-dollar-functions-examples.md`
- Reference: `references/frameworks/founder-vs-inheritor.md`

## Disclaimer

This is a strategic framework based on Balaji Srinivasan's published thinking. The full-stack decision depends heavily on specific market conditions, available capital, team capabilities, and timing. Building a full-stack company requires significantly more capital and operational complexity than selling a single layer.

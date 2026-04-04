---
name: truth-type-classifier
description: "Classify any claim as scientific, technical, political, economic, or cryptographic truth and identify the appropriate verification method. Use when someone says 'how do I verify this claim,' 'is this actually true,' 'what kind of truth is this,' 'truth type classification,' 'how to check this,' 'what evidence would prove this,' or 'scientific vs political truth.' Applies Balaji's five truth types taxonomy."
---

# Truth Type Classifier

Given any claim, assertion, or piece of information, classify it into one of Balaji's five truth types and identify the appropriate verification method. Reveal why most arguments fail: the participants disagree not about the facts but about which TYPE of truth applies.

## Background: The Five Truth Types

Balaji argues that the fundamental problem in public discourse is that people treat all claims as if they are the same kind of truth. They are not. A scientific claim and a political claim require completely different verification methods, and confusing the two leads to endless unresolvable arguments.

The five types, drawn from The Anthology of Balaji and The [[network-state-ten-components|Network State]]:

### 1. Scientific Truth
**Definition:** Truths verified by reproducible experiment. True regardless of who believes them.

**Verification method:** Design an experiment. Run it. Get the same result. Have others replicate it.

**Examples:** The speed of light, the value of pi, the boiling point of water, the efficacy of a drug in a double-blind trial.

**Key property:** Doesn't depend on consensus. If every person on Earth believes pi equals 4, it's still 3.14159...

> "Tesla is more powerful than the New York Times because technological truths are ultimately more durable than political truths."
> -- Balaji Srinivasan, The Network State, Ch 2.3

### 2. Technical Truth
**Definition:** Truths verified by engineering outcomes. The bridge holds or it doesn't. The code compiles or it doesn't.

**Verification method:** Build it and test it. Does it work?

**Examples:** This airplane design can fly. This software algorithm sorts in O(n log n). This material can withstand 500 degrees.

**Key property:** Falsified by failure. If the bridge falls, the engineering was wrong, regardless of how many engineers believed it was sound.

### 3. Political Truth
**Definition:** Truths that are true BECAUSE enough people believe them. These are social constructs that depend on collective belief.

**Verification method:** Consensus. If enough people agree, it becomes operationally true. If they stop agreeing, it becomes operationally false.

**Examples:** Money has value. This border is legitimate. This person has authority. This behavior is socially acceptable.

> "Political truths are things like money, status, and borders. They're real because people collectively believe in them, and they stop being real when people stop believing."
> -- Balaji Srinivasan, The Network State, Ch 2.3 (paraphrased from discussion)

**Key property:** Can be changed by changing beliefs. A revolution doesn't change the laws of physics, but it does change which political truths are operative.

### 4. Economic Truth
**Definition:** Truths verified by the market. The price is the signal.

**Verification method:** Are people willing to pay for it? Does the market clear? What does the price say?

**Examples:** This company is worth $X. There is demand for this product. This asset will appreciate. This labor market is tight.

**Key property:** Verified by revealed preference (what people actually do with money), not stated preference (what they say they want). Balaji's "stated vs. expressed preference" gap is a corollary.

### 5. Cryptographic Truth
**Definition:** Truths verified by mathematical proof, typically via blockchain or cryptographic protocol. True because the math is true.

**Verification method:** Run the computation. Check the hash. Verify the signature. Audit the blockchain.

**Examples:** This transaction occurred at this timestamp. This wallet holds this amount. This message was signed by this key. This proof-of-work was computed correctly.

**Key property:** Cannot be faked, altered, or censored by any authority. "A timestamp is more powerful than Macron" because it doesn't require trusting any institution.

> "A timestamp is more powerful than Macron because cryptographic truths don't require trust in any institution."
> -- Balaji Srinivasan, The Network State, Ch 2.3 (paraphrased from discussion)

## The Consultation

### Step 1: Receive the Claim

Ask:

1. What is the specific claim you want to evaluate?
2. Who is making this claim?
3. What evidence is being offered to support it?
4. What decision are you trying to make based on this claim?

### Step 2: Classify the Truth Type

For the claim, determine which truth type it belongs to. Many claims are mixtures, so identify the primary type and any secondary types.

**Classification Decision Tree:**

1. **Can it be tested by a reproducible experiment?**
   - Yes -> Scientific Truth
   - No -> Continue

2. **Can it be tested by building something and seeing if it works?**
   - Yes -> Technical Truth
   - No -> Continue

3. **Is it true because enough people believe/agree it's true?**
   - Yes -> Political Truth
   - No -> Continue

4. **Is it verified by market prices or economic transactions?**
   - Yes -> Economic Truth
   - No -> Continue

5. **Is it verified by mathematical proof or cryptographic protocol?**
   - Yes -> Cryptographic Truth

**Common Misclassifications:**

| Claim | Often Treated As | Actually Is | Why It Matters |
|-------|-----------------|-------------|----------------|
| "This diet works" | Political (influencer consensus) | Scientific (clinical trials) | People follow popular diets, not tested ones |
| "This company is overvalued" | Economic (market truth) | Often Political (consensus opinion) | Until someone shorts it, it's just an opinion |
| "Inflation is transitory" | Scientific (data-based) | Political (institutional consensus) | Government statistics are political, not scientific |
| "This is misinformation" | Scientific (fact-checking) | Political (authority assertion) | "Misinformation" labels are often political truths dressed as scientific ones |
| "The election was fair" | Political (institutional consensus) | Could be Cryptographic (if on-chain verification existed) | The verification method determines credibility |

### Step 3: Identify the Verification Method

For the classified truth type, prescribe the specific verification method:

| Truth Type | Verification Method | Red Flag (Wrong Method) |
|-----------|-------------------|------------------------|
| Scientific | Reproducible experiment, peer review, replication studies | "Experts say" without citing experiments |
| Technical | Build it, test it, measure it | "In theory it should work" without testing |
| Political | Consensus measurement, voting, exit/voice metrics | Treating political consensus as scientific fact |
| Economic | Market price, revealed preference, transaction data | "It should be worth X" vs. actual market price |
| Cryptographic | Hash verification, signature check, on-chain audit | "Trust us, the data is correct" without cryptographic proof |

### Step 4: Detect Truth-Type Confusion

The most common source of bad reasoning is applying the wrong verification method. Identify if this is happening:

**Political truths being presented as scientific truths:**
This is the most dangerous confusion. When someone says "the science is settled" about a claim that is actually political, they are using the authority of science to enforce a political consensus. Test: Is there an actual reproducible experiment, or is it "expert consensus"?

**Scientific truths being treated as political truths:**
Sometimes genuine scientific findings are rejected because they are politically inconvenient. Test: Is the rejection based on counter-evidence, or on political/social consequences?

**Economic truths being overridden by political truths:**
Governments setting prices (rent control, minimum wage, drug price caps) treats economic truths as if they were political truths that can be changed by decree. The market will reassert economic truth eventually.

**Cryptographic truths being ignored:**
On-chain data is treated as less credible than institutional assertions. This is backwards: the cryptographic truth is more reliable because it doesn't require trust.

### Step 5: Prescribe the Action

Based on the classification and verification method:

1. **What evidence would change your mind?** Define the falsification criteria before looking at evidence.
2. **Who should you NOT trust for this truth type?** (Governments for scientific truth, markets for political truth, etc.)
3. **What verification infrastructure exists?** (Labs for scientific, markets for economic, blockchains for cryptographic)
4. **What's the cost of being wrong?** Higher cost requires higher verification standards.

## Output

Deliver a structured Truth Type Classification:

```markdown
# Truth Type Classification: [The Claim]

## The Claim
[Exact statement being evaluated]

## Classification: [Scientific / Technical / Political / Economic / Cryptographic]
**Confidence:** [High / Medium / Low]
**Secondary type:** [If mixed]

## Why This Classification
[Specific reasoning for why this truth type applies]

## Correct Verification Method
[Specific method for this truth type]

## Current Verification Status
- Evidence offered: [What evidence exists]
- Method used: [How it was verified]
- Method appropriate: [Yes/No - is the right verification method being used?]

## Truth-Type Confusion Detected?
[If the claim is being verified using the wrong method, explain what's happening]

## Falsification Criteria
[What evidence would prove this claim false?]

## Recommendation
[What the user should do to verify this claim for their specific decision]

## Verification Infrastructure
[Specific tools, institutions, or protocols that can verify this type of truth]
```

## Source Material

- The Network State, Ch 2.3: "Political Power and Technological Truth" (political truth vs. technological truth, Tesla > NYT, timestamp > Macron, atrocity stories as political truth enforcement)
- The Anthology of Balaji, Part II: "Truth" (pp. 93-116) - full taxonomy of truth types with examples
- Reference: `references/frameworks/five-truth-types.md`

## Disclaimer

This is an epistemological framework based on Balaji Srinivasan's published thinking. Classifying truth types is an analytical exercise, not a definitive determination of what is true or false. Many real-world claims contain elements of multiple truth types. This framework is designed to improve reasoning about evidence, not to dismiss claims or justify predetermined conclusions. It does not constitute scientific, legal, or policy advice.

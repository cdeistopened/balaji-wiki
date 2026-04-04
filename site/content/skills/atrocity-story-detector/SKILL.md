---
name: atrocity-story-detector
description: "Evaluate whether a narrative is being used as a 'founding murder' to justify expansion of political power. Use when someone says 'is this narrative being weaponized,' 'atrocity story analysis,' 'is this a power grab,' 'founding murder pattern,' 'is this crisis real or manufactured,' 'who benefits from this narrative,' or 'is the government using fear to expand power.' Checks for the pattern: bad event -> expansion of state force -> ignoring deaths caused by that force."
---

# Atrocity Story Detector

Given a narrative about a crisis, threat, or bad event that is being used to justify expanded government power or institutional control, evaluate whether it follows the "atrocity story" pattern. Identify whether the narrative is genuine, exaggerated, or fabricated, and whether the proposed response causes more harm than the original problem.

## Background: The Atrocity Story Pattern

Balaji draws on the concept of the "atrocity story" (from political science) and Rene Girard's "founding murder" to identify a pattern used throughout history to justify expansions of political power.

> "One of the most time-honored techniques to mobilize public animosity against the enemy and to justify military action is the atrocity story. This technique, says Professor Lasswell, has been used 'with unvarying success in every conflict known to man.'"
> -- Quoted in The [[network-state-ten-components|Network State]], Ch 2.3

Balaji extends this beyond wartime to peacetime governance:

> "The concept is as useful in peacetime as it is in war. Even in peacetime, the state is predicated on force. And this use of force requires justification. The atrocity story is the tool used to convince people that the use of state force is legitimate."
> -- Balaji Srinivasan, The Network State, Ch 2.3

The pattern:
1. A bad event occurs (sometimes real, sometimes fake, sometimes exaggerated)
2. The event is used to justify expanded state force or institutional control
3. The deaths or harms caused by that expanded force are ignored
4. Anyone who questions the narrative is accused of being indifferent to the original atrocity

> "Indeed, almost everything in politics is backed by an atrocity story. There's a sometimes real, sometimes fake, sometimes exaggerated Girardian founding murder behind much of what the government does."
> -- Balaji Srinivasan, The Network State, Ch 2.3

## The Consultation

### Step 1: Define the Narrative

Ask:

1. What is the crisis, threat, or bad event being cited?
2. What expanded power or policy is being justified by this narrative?
3. Who is promoting this narrative? (Government, media, NGOs, corporations)
4. Who benefits from the expanded power?
5. Is anyone questioning the narrative? What are they saying, and how are they being treated?

### Step 2: Apply the Atrocity Story Diagnostic

Evaluate the narrative against 6 tests:

**Test 1: Is the Underlying Event Real?**
Not all atrocity stories are fake. Balaji is explicit about this:

> "Just because there is an incentive to fake (or exaggerate) atrocities does not mean that all atrocities are fake or exaggerated."
> -- Balaji Srinivasan, The Network State, Ch 2.3

Score the evidence:
- Is the event documented by multiple independent sources?
- Is there physical/cryptographic evidence, or only testimonial?
- Have previous claims by the same actors been verified or debunked?
- Is the evidence proportional to the claim?

**Test 2: Is the Response Proportional?**
Even when the event is real, the response may be wildly disproportionate. Balaji's canonical example:

> "When the FDA 'prevented' deaths by cracking down on drug approvals after thalidomide, it caused many more deaths via Eroom's Law and drug lag."
> -- Balaji Srinivasan, The Network State, Ch 2.3

Ask: Does the proposed response cause more harm than the original problem? What are the second-order effects?

**Test 3: Are Deaths from the Response Being Counted?**
The most telling sign: proponents count the deaths from the original event but refuse to count the deaths from their response.

- FDA counts thalidomide victims but not drug lag victims
- TSA counts prevented attacks but not the cost of delayed medical transport, economic disruption, or privacy loss
- Content moderation counts prevented "harm" but not the cost of censoring legitimate speech

Ask: Is there an accounting of harms caused by the response? If not, why not?

**Test 4: Is the Narrative Being Used as a "Founding Murder"?**
In Girard's framework, a founding murder creates the moral foundation for a new institution or power structure. The institution then maintains its legitimacy by periodically re-invoking the founding murder.

> "Rene Girard would call this a 'founding murder.' Once you see this technique, you see it everywhere."
> -- Balaji Srinivasan, The Network State, Ch 2.3

Ask: Is this event being treated as a permanent justification for ongoing power, or as a one-time problem to solve?

**Test 5: Has This Exact Pattern Been Used Before?**
Balaji cites specific historical examples of fabricated or exaggerated atrocity stories:

- **Iraq WMD**: "Before Iraq was falsely accused of holding WMD, it was falsely accused of tossing babies from incubators."
- **The Holodomor coverup**: The New York Times' Pulitzer-winning Walter Duranty covered up Stalin's Ukrainian famine (the inverse: using media power to suppress a real atrocity)

Ask: Are there historical precedents where the same type of narrative was used to justify the same type of power expansion, and the narrative later turned out to be false or exaggerated?

**Test 6: What's the "Flopping" Dynamic?**
Balaji uses the basketball analogy of "flopping" (exaggerating a foul to get a favorable call):

> "You should be aware that states are always 'flopping,' exaggerating the severity of the fouls against them or the mascots they claim to represent, trying to bring in the public on their side, whether they are Chinese or American or Russian."
> -- Balaji Srinivasan, The Network State, Ch 2.3

Ask: Is the severity of the event being exaggerated relative to comparable events? Is the emotional framing disproportionate to the factual evidence?

### Step 3: Navigate Between Credulity and Cynicism

Balaji warns against overcorrection in both directions:

> "The next goal is to guard against both the Scylla and the Charybdis, against being too credulous and too cynical. Because just as the atrocity story is a tool for political power, unfortunately so too is genocide denial."
> -- Balaji Srinivasan, The Network State, Ch 2.3

Apply the balance test:
- **Too credulous**: Accepting the narrative at face value because the claimed victims are sympathetic
- **Too cynical**: Dismissing the narrative entirely because "all atrocity stories are fake"
- **Calibrated**: Evaluating the evidence independently, counting all harms (from both the event and the response), and resisting the pressure to pick a side without evidence

### Step 4: Identify the Verification Method

Balaji's solution to atrocity stories is not more argumentation but better verification technology:

- **Cryptographic verification**: Can the claims be verified on-chain or through independent data?
- **On-chain shadow statistics**: Are there independent, censorship-resistant metrics that contradict or confirm the official narrative?
- **Reproducible analysis**: Can the data be independently analyzed, or does verification require trusting the same institutions promoting the narrative?

### Step 5: Prescribe a Response

Based on the diagnostic:

**If genuine and proportional**: Support the response. Not everything is manipulation.

**If genuine but disproportionate**: Acknowledge the real event. Propose a response that addresses the actual harm without creating larger second-order harms. Demand an accounting of response-caused harms.

**If exaggerated**: Identify the exaggeration. Point to the evidence that doesn't match the narrative. Resist the social pressure to accept the exaggeration ("you don't care about X!").

**If fabricated**: Document the fabrication. Compare to historical precedents. Be prepared for severe social consequences, as questioning a founding murder is always taboo.

## Output

Deliver a structured Atrocity Story Assessment:

```markdown
# Atrocity Story Assessment: [Narrative]

## The Narrative
- Claimed event: [What supposedly happened]
- Promoted by: [Who is pushing this narrative]
- Proposed response: [What expanded power is being justified]
- Who benefits: [Who gains from the expanded power]

## Diagnostic Results

| Test | Result | Evidence |
|------|--------|----------|
| 1. Is the event real? | [Confirmed / Uncertain / Fabricated] | |
| 2. Is the response proportional? | [Yes / No / Unknown] | |
| 3. Are response harms counted? | [Yes / No] | |
| 4. Founding murder pattern? | [Yes / No] | |
| 5. Historical precedent? | [Yes: (cite) / No] | |
| 6. Flopping dynamic? | [Yes / No] | |

## Credulity-Cynicism Calibration
[Where the evidence places this on the spectrum from genuine crisis to pure fabrication]

## The Harms Accounting
| Harm Source | Documented Deaths/Harms | Source |
|-------------|------------------------|--------|
| Original event | [Number] | [Source] |
| Proposed/enacted response | [Number] | [Source] |

## Verification Method
[How this narrative could be independently verified or debunked]

## Assessment: [Genuine Crisis / Genuine but Disproportionate / Exaggerated / Fabricated]

## Recommended Response
[What to do given the assessment]

## Historical Parallel
[The most relevant historical case and what it teaches]
```

## Source Material

- The Network State, Ch 2.3: "Political Power and Technological Truth" (atrocity story concept, founding murder, FDA drug lag, Iraq WMD, babies-from-incubators, NYT/Holodomor coverup, Scylla and Charybdis balance, "flopping" analogy)
- Reference: `references/frameworks/atrocity-story-patterns.md`
- Reference: `references/frameworks/five-truth-types.md` (verification methods for claims)

## Disclaimer

This is an analytical framework based on Balaji Srinivasan's published thinking, drawing on political science and Rene Girard's mimetic theory. It is designed to encourage critical thinking about narratives used to justify power expansion. It is NOT a tool for dismissing genuine crises or denying real atrocities. Balaji himself warns against overcorrection into cynicism. Every narrative should be evaluated on its evidence, not assumed to be fake. This framework does not constitute legal, political, or policy advice.

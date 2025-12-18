# Copy Architect - Usage Examples

This file demonstrates how to use the Copy Architect skill for different scenarios.

## Example 1: Marketing Email Enhancement

### Input

```
Use the copy-architect skill to enhance this email:

Subject: New Feature Available

Hi there,

We've added a new dashboard feature that helps you track your metrics better.
It has charts and graphs and is very user-friendly.

Check it out today!

Thanks,
The Team

---
AUDIENCE: Product managers at B2B SaaS companies
GOAL: Click through to view feature
MEDIUM: email
TONE: conversational
RISK_MODE: balanced
```

### Expected Output Structure

The skill will provide:
1. Side-by-side comparison (original vs. enhanced)
2. Key improvements (4-10 bullets explaining changes)
3. Engagement techniques used
4. Expected impact analysis
5. Ratings (Impact, Readability, Persuasiveness)
6. Governance findings (if any flags raised)
7. Suggested A/B tests

## Example 2: Landing Page Hero Section

### Input

```
Use the copy-architect skill:

Our AI platform uses advanced machine learning to help businesses optimize
their operations. We have over 50+ features including automation, analytics,
and reporting. Trusted by companies worldwide.

---
AUDIENCE: CTOs at mid-market companies ($10M-$100M revenue)
GOAL: Schedule demo
MEDIUM: landing page
TONE: authoritative but approachable
RISK_MODE: aggressive
```

## Example 3: Internal Proposal

### Input

```
Use the copy-architect skill:

I think we should migrate our database to PostgreSQL. It's better than what
we're using now and will solve some problems we've been having with performance.

---
AUDIENCE: Engineering leadership + CTO
GOAL: Get approval for migration project
MEDIUM: internal memo/Slack
TONE: formal
RISK_MODE: conservative
```

## Example 4: LinkedIn Post

### Input

```
Use the copy-architect skill:

Just launched our new product! It's been 6 months in the making and we're
really proud of what we built. Check it out and let me know what you think.

---
AUDIENCE: Startup founders and early-stage investors
GOAL: Drive traffic to product launch page
MEDIUM: LinkedIn
TONE: conversational but credible
RISK_MODE: balanced
```

## Example 5: Quick Enhancement (No Metadata)

### Via Slash Command

```
/copy-enhance

Our service is fast, reliable, and affordable. We've been in business for
10 years and have helped thousands of customers. Sign up today!
```

The skill will infer defaults:
- AUDIENCE: General professional audience
- GOAL: Increase engagement
- MEDIUM: Digital content
- TONE: Professional but approachable
- RISK_MODE: Balanced

## Example 6: High-Risk Domain (Healthcare)

### Input

```
Use the copy-architect skill:

Our supplement helps reduce joint pain and inflammation. Customers have
reported feeling better within just 2 weeks. Doctor-formulated and 100% natural.

---
AUDIENCE: Adults 40+ with joint pain
GOAL: Purchase supplement
MEDIUM: landing page
TONE: authoritative
RISK_MODE: conservative
```

### Expected Behavior

The skill will:
- Auto-escalate to EDUCATIONAL_ADVISORY_MODE
- Require governance posterior > 0.85
- Flag any unsupported health claims
- Add disclaimer about professional review requirement
- Soften prescriptive language
- Focus on transparency and user agency

## Example 7: Iteration After Initial Enhancement

### Follow-up Request

After receiving the initial enhanced version:

```
Make it more aggressive - we need higher urgency
```

Or:

```
Shorten to 50 words maximum
```

Or:

```
Remove the urgency language - testing if it affects conversion negatively
```

Or:

```
Target technical audience instead of business audience
```

## Metadata Field Guide

### AUDIENCE
Be specific about:
- Role/title
- Company size/stage
- Expertise level
- Decision-making authority
- Pain points/motivations

**Examples:**
- "Enterprise security engineers at Fortune 500 companies"
- "First-time startup founders (technical background)"
- "Marketing managers at B2B SaaS companies ($5M-$50M ARR)"

### GOAL
Define the specific behavioral outcome:
- Click link
- Schedule demo
- Purchase product
- Download resource
- Share with team
- Approve budget
- Change belief/understanding

**Examples:**
- "Book 30-minute discovery call"
- "Download API documentation"
- "Forward to engineering team for evaluation"

### MEDIUM
Specify the channel and constraints:
- Email (subject line + body)
- Landing page (hero section)
- LinkedIn post (character limits)
- Twitter/X (280 chars)
- Internal memo (formal structure)
- Slack message (informal, scannable)
- Ad copy (character limits, platform)

### TONE
Choose voice characteristics:
- **Authoritative:** Expert, credible, data-driven
- **Conversational:** Friendly, approachable, casual
- **Playful:** Creative, humorous, unexpected
- **Minimalist:** Sparse, understated, focused
- **Formal:** Professional, structured, traditional
- **Urgent:** Time-sensitive, action-oriented, direct

Can combine: "Conversational but credible" or "Formal but approachable"

### RISK_MODE
- **Conservative:** No hype, minimal urgency, heavy proof requirements
- **Balanced:** Strategic tension, grounded claims, measured urgency
- **Aggressive:** Strong hooks, urgency (if honest), compelling CTAs

## Common Patterns

### Pattern 1: Feature → Outcome Translation

**Original:**
"We have 24/7 customer support"

**Enhanced:**
"Sleep soundly knowing help is 2 clicks away, any time"

### Pattern 2: Vague → Specific

**Original:**
"Fast processing times"

**Enhanced:**
"Process 10,000 transactions in under 2 seconds"

### Pattern 3: Passive → Active Voice

**Original:**
"The report can be generated automatically"

**Enhanced:**
"Generate reports automatically with one click"

### Pattern 4: Buried Lede → Hook First

**Original:**
"Our company was founded in 2015 to solve enterprise data problems. We now offer a platform that helps you manage analytics."

**Enhanced:**
"Stop losing deals to data chaos. Your team spends 12 hours weekly hunting for metrics—we compress that to 12 minutes."

## Interpreting Output

### Ratings Scale

**Impact (1-5):**
- 1: Cosmetic changes only
- 3: Moderate improvement in persuasiveness
- 5: Significant leverage on behavioral outcome

**Readability (1-5):**
- 1: Dense, hard to parse, unclear flow
- 3: Acceptable but requires effort
- 5: Flows naturally, highly scannable

**Persuasiveness (1-5):**
- 1: Unchanged or weaker than original
- 3: Better audience alignment
- 5: Compelling, hard to resist, addresses objections

### Governance Posterior

- **0.85+:** Very safe, approved
- **0.75-0.84:** Safe with minor flags
- **0.65-0.74:** Proceed with disclaimers/caveats
- **<0.65:** Escalate to human review

### A/B Test Ideas

The skill provides specific, executable experiments:
- Subject line variants with predicted impact
- CTA button text alternatives
- Structure reordering tests
- Urgency language on/off tests

## Tips for Best Results

1. **Be specific with AUDIENCE:** "Developers" is vague; "Senior backend engineers at Series B startups" is actionable
2. **Define clear GOAL:** "Increase engagement" is fuzzy; "Click CTA to schedule demo" is measurable
3. **Provide context:** If there are constraints (character limits, brand voice, regulatory), mention them
4. **Iterate thoughtfully:** Use the A/B test suggestions; don't just accept the first version
5. **Validate claims:** If the skill flags governance issues, address the root concern (don't just rephrase)
6. **Test assumptions:** The skill states assumptions when metadata is missing—verify they're correct

## Anti-Patterns to Avoid

❌ **Vague request:** "Make this better"
✅ **Specific request:** "Make this more compelling for technical buyers; increase urgency without being manipulative"

❌ **Missing context:** No AUDIENCE, GOAL, or TONE specified
✅ **Rich context:** All metadata fields filled with specific, actionable details

❌ **Ignoring governance flags:** Pushing through LEG/ETH violations
✅ **Addressing root issues:** If skill flags overclaiming, verify claims or soften language

❌ **Accepting first output blindly:** Not testing or iterating
✅ **Human-in-loop:** Review, test A/B variants, refine based on results

## Advanced Usage

### Counterfactual Exploration

Ask the skill to explain causal mechanisms:

```
Explain why changing the hook from "We help you manage data" to "Stop losing
deals to data chaos" is predicted to increase engagement. What's the causal
mechanism?
```

### Confidence Calibration

Request epistemic confidence levels:

```
For each claim in the enhanced version, show confidence intervals and explain
how you calibrated the language.
```

### Variant Generation

Request multiple strategic frames:

```
Generate 3 variants:
1) Story-led (customer narrative)
2) Proof-led (data/social proof)
3) Urgency-led (time-sensitive offer)
```

## Troubleshooting

### "Governance posterior too low"
- Review LEG/ETH/SEC/RG findings
- Address root concerns (verify claims, remove dark patterns, add context)
- Consider requesting conservative mode

### "Output doesn't match tone"
- Check if TONE was specified clearly
- Request regeneration with explicit tone constraint
- Provide example of desired voice

### "Enhancement lost the original message"
- Flag to the skill that intent wasn't preserved
- Request regeneration with CONSTRAINT: PRESERVE_CORE_MESSAGE
- Provide clearer explanation of core message/offer

### "Too generic / not specific enough"
- Add more AUDIENCE details (expertise, pain points, context)
- Specify concrete GOAL (not just "engagement" but "click CTA to download whitepaper")
- Provide industry context or jargon that should be used

## Integration with Other Tools

### With A/B Testing Platforms
1. Use Copy Architect to generate variants
2. Deploy suggested A/B experiments to Optimizely, VWO, etc.
3. Measure actual performance
4. Feed results back: "Variant B performed 23% better; generate 3 more in that direction"

### With Content Calendars
1. Draft rough copy
2. Use Copy Architect to enhance
3. Review governance findings
4. Schedule variants for A/B testing
5. Track performance over time

### With Brand Guidelines
1. Specify TONE based on brand voice
2. Add CONSTRAINT: [your brand guidelines summary]
3. Request variants that stay within brand parameters
4. Use for consistency across campaigns

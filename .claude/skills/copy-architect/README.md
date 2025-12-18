# X.∞ Copy Architect Skill

Advanced copywriting enhancement using multi-agent causal analysis, epistemic governance, and strategic optimization.

## What It Does

The Copy Architect skill transforms text through:

1. **Causal Diagnosis** - Identifies root causes of weaknesses, not just surface symptoms
2. **Multi-Agent Governance** - Legal, ethical, security, and resource validation (non-overridable)
3. **Strategic Enhancement** - Hook optimization, flow improvement, benefit articulation, tone calibration
4. **Transparent Analysis** - Every edit justified with causal reasoning and confidence intervals
5. **Iteration Support** - A/B test ideas and specific next experiments

## How to Use

### Via Skill (Recommended for complex tasks)

```
Use the copy-architect skill to enhance this text:

[Your text here]

AUDIENCE: [Who is this for?]
GOAL: [What should readers do?]
MEDIUM: [email | landing page | LinkedIn | memo]
TONE: [authoritative | conversational | playful | formal]
RISK_MODE: [conservative | balanced | aggressive]
```

### Via Slash Command (Quick enhancement)

```
/copy-enhance

[Your text here]
```

The slash command will use default assumptions (general professional audience, balanced mode).

## Output Structure

You'll receive 7 sections:

1. **Side-by-Side Text** - Original vs. Enhanced (+ optional variant)
2. **Key Improvements** - 4-10 bulleted changes
3. **Engagement Techniques Used** - Frameworks applied
4. **Expected Impact** - Predictions on attention, comprehension, motivation
5. **Ratings** - Impact (1-5), Readability (1-5), Persuasiveness (1-5)
6. **Governance Findings** - Legal/ethical/security flags (if any)
7. **Suggested Next Experiments** - 2-4 specific A/B tests

## Governance Architecture

The skill runs a Bayesian cascade through four gates:

- **LEG (Legal):** Regulatory compliance, overclaiming, unsupported claims
- **ETH (Ethical):** Dark patterns, manipulation, harm prevention
- **SEC (Security):** Prompt injection, model jailbreak detection
- **RG (Resource):** Feasibility vs. stated budget/timeline

**Posterior Belief Scoring:**
- ≥ 0.80: APPROVE (proceed)
- 0.65-0.79: PROCEED_WITH_FLAGS (add disclaimers)
- < 0.65: ESCALATE (suggest reframing or defer to human)

Governance failures are **non-negotiable** - the skill will not override safety gates.

## Special Cases

### High-Risk Domains
For health, finance, legal, or safety-critical content:
- Auto-escalates to EDUCATIONAL_ADVISORY_MODE
- Requires posterior > 0.85
- Adds disclaimer: "Review required by qualified professionals before deployment"

### Iteration Examples
After initial enhancement, you can request:
- "Make it more aggressive" (increases RISK_MODE, recomputes governance)
- "Shorten to 50 words" (maximum compression while preserving message)
- "Target CTOs instead of marketers" (recomputes psychological leverage)
- "Remove urgency language" (regenerates without scarcity/time pressure)

## Key Principles

### Non-Negotiable Constraints
1. **Preserve Intent** - Never silently change core message
2. **No Fabrication** - Never invent testimonials, data, or facts
3. **No Dark Patterns** - No fake scarcity, guilt trips, fear-mongering
4. **Privacy First** - Anonymize any PII in output
5. **Governance First** - If a gate fails, escalate (never override)

### Epistemic Confidence
Every claim is calibrated:
- **High confidence (0.9+):** Declarative language ("X is Y")
- **Medium confidence (0.7-0.9):** Qualified language ("X tends to be Y")
- **Low confidence (<0.7):** Remove or heavily caveat

### Causal Reasoning
Improvements are justified by causal mechanisms, not correlation:
- ❌ "Weak headline" → "Make it stronger"
- ✅ "Headline uses abstract benefit ('efficient'); readers need concrete outcome ('reclaim 12 hours weekly') to activate motivation"

## Examples

### Marketing Email

**Input:**
```
AUDIENCE: SaaS founders
GOAL: Book demo call
MEDIUM: email
TONE: conversational
RISK_MODE: balanced

Our platform helps you manage your sales pipeline more efficiently.
```

**Output:** 7-section analysis with enhanced version like:
```
Reclaim 8 hours weekly from pipeline chaos.

SaaS founders tell us their #1 bottleneck isn't hiring—it's tracking who said what, when, and what happens next. [Enhanced body with proof points, social proof, clear CTA, and objection handling]
```

### Internal Memo

**Input:**
```
AUDIENCE: Executive team
GOAL: Approve budget increase
MEDIUM: internal memo
TONE: formal
RISK_MODE: conservative

We need more resources for the Q2 product roadmap.
```

**Output:** 7-section analysis with enhanced version like:
```
Q2 Product Roadmap: Resource Gap Analysis & Mitigation Plan

Our current Q2 commitments to enterprise clients require 3 additional engineers to meet contractual deadlines. [Enhanced body with financial justification, risk analysis, clear ask]
```

## Technical Architecture

### Internal Agents (Silent Operation)
Five specialized agents run internally without roleplay noise:

1. **Causal Diagnostician** - Root-cause analysis using Pearl's causal hierarchy
2. **Intent Architect** - Audience decision-tree mapping
3. **Governance Cascade** - LEG/ETH/SEC/RG sequential validation
4. **Linguistic Optimizer** - Sentence-level constraint-driven rewrites
5. **Recursive Reflection** - Post-generation validation & failure mode detection

### Latent-Space Steering
- Verb-first priming (ACT framework)
- Constraint injection (FACTGROUNDED, DETERMINISTIC, READER_CENTRIC)
- Attention redirection via high-decision-density tokens

### Cognitive Budget Allocation
- Budget 5: Fast diagnosis (low-stakes content)
- Budget 10-15: Balanced analysis (standard marketing)
- Budget 20+: Deep causal analysis (high-stakes, regulated content)

## Limitations

- **Not a replacement for human judgment** - Especially in high-stakes domains
- **Requires clear goals** - Vague objectives ("make it better") produce generic enhancements
- **English-optimized** - May not transfer patterns to other languages
- **Context-dependent** - Industry jargon and norms vary; skill uses general heuristics

## Support & Iteration

The skill is designed for **human-in-the-loop iteration**, not autonomous deployment:
1. Review the 7-section output
2. Assess governance findings and ratings
3. Try suggested A/B experiments
4. Request specific refinements
5. Validate with domain experts before deploying

For questions or issues, refer to the main SKILL.md file or the Claude Code documentation.

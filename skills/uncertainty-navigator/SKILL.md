---
name: uncertainty-navigator
description: >
  Apply the Rumsfeld Matrix and PREP Framework to any decision, initiative, or challenge under uncertainty.
  Use this skill whenever the user wants to think through what they know vs. don't know, map out a PREP
  action plan (Perform / Research / Explore / Prepare), navigate organizational change, assess team readiness,
  structure scenario planning, or frame a strategic decision under incomplete information. Also trigger when
  the user describes a specific situation and asks how to approach it, what to do next, or how to structure
  their thinking. Good trigger phrases include "what do we know", "help me think through this", "we are
  navigating X", "I need to plan for uncertainty", "help me apply PREP", "let's map the knowns and unknowns",
  "Rumsfeld matrix", or when discussing any major initiative with unclear variables such as a new product,
  GTM motion, org change, platform expansion, or acquisition.
---

# Uncertainty Navigator

Helps the user apply two complementary frameworks — the Rumsfeld Matrix and the PREP Framework — to any decision, initiative, or challenge involving uncertainty.

---

## Step 1: Clarify the Situation

If the user hasn't described a specific situation, ask:
- What decision or challenge are you navigating?
- Who is the primary actor — you personally, your team, or the broader organization?
- What's the time horizon or urgency?

If the user has already described a situation, extract the context from their message and proceed directly.

---

## Step 2: Apply the Rumsfeld Matrix

Categorize everything relevant to the situation into four quadrants. Be specific — use the user's actual context, not generic placeholders.

| Quadrant | Definition | What to do with it |
|---|---|---|
| **Known Knowns** | Facts we know and understand | Optimize and act on these with confidence |
| **Known Unknowns** | Gaps we're aware of but haven't filled | Research, investigate, consult experts |
| **Unknown Knowns** | Insights we have but aren't leveraging | Surface and apply hidden expertise/data |
| **Unknown Unknowns** | Risks/factors we can't anticipate | Build resilience, contingency plans, diverse advisory input |

Present this as a filled-in 2x2 table using the user's situation. Be concrete. For each quadrant, list 2-4 specific items drawn from the context, not generic examples.

**Framing note for output:** Lead with known knowns (what we can act on now), then known unknowns (what we need to find out), then unknown knowns (what we're underutilizing), then unknown unknowns (how we stay resilient).

---

## Step 3: Apply the PREP Framework

Map the quadrants to actions using PREP. Each letter maps to a quadrant:

| PREP Element | Rumsfeld Quadrant | Action Focus |
|---|---|---|
| **Perform** | Known Knowns | Execute and reinforce current strengths. Deliver high-quality work. Establish clear roles and documented processes. |
| **Research** | Known Unknowns | Fill knowledge gaps. Sharpen business acumen. Conduct targeted investigation to reduce uncertainty. |
| **Explore** | Unknown Knowns | Surface and leverage hidden expertise. Cross-functionally network. Identify underutilized data, skills, or relationships. |
| **Prepare** | Unknown Unknowns | Build resilience. Create contingency plans. Diversify your advisory network. Foster psychological safety on the team. |

For each PREP element, generate 3-5 specific, actionable bullets tailored to the user's situation. Avoid generic advice.

---

## Step 4: Identify the Top Pitfall to Watch

Based on the situation, call out the single most likely FP&A / leadership pitfall from this list:

1. Over-reliance on historical data
2. Poor communication during change
3. Ignoring early warning signs
4. Inflexible planning and budgeting
5. Short-term focus at the expense of long-term
6. Weak risk management and business insight

State it plainly and give one concrete mitigation action.

---

## Step 5: Strategic Influence Check (optional, for organizational challenges)

If the situation involves influencing stakeholders or driving org-level change, add a brief action sequence:

1. **Challenge existing perspectives** — What assumption needs to be questioned?
2. **Understand stakeholder realities** — What does each key stakeholder actually care about?
3. **Leverage existing relationships** — Who can accelerate alignment?
4. **Provide evidence aligned with strategic goals** — What data or narrative will resonate?

---

## Output Format

Structure the full output as:

```
## Situation Summary
[1-2 sentence restatement of what the user is navigating]

## Rumsfeld Matrix
[2x2 table with 2-4 bullets per quadrant, specific to their situation]

## PREP Action Plan
[4 sections — Perform / Research / Explore / Prepare — each with 3-5 actionable bullets]

## Top Pitfall to Watch
[Named pitfall + one mitigation action]

## Strategic Influence Actions (if applicable)
[4-step sequence with specifics]
```

Keep the tone executive and direct. No filler. Bullets over prose. Use the user's own language and context throughout.

---

## Common Contexts to Watch For

These situations are high-value triggers for this skill:

- **New product or market entry** — Map what's validated vs. assumed
- **GTM motion changes** — Direct vs. channel, new buyer persona, pricing uncertainty
- **Platform or BU expansion** — What capabilities exist vs. what needs to be built
- **Org restructuring or leadership transitions** — Known impact vs. unknown dynamics
- **Competitive threats** — What we know about the competitor vs. what we're assuming
- **Budget uncertainty** — Locking in commitments vs. staying flexible

In each case, the Rumsfeld Matrix structures the information; PREP converts it to action.

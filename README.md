# Creator Outreach Engine

An AI-built pipeline for managing brand partnerships as a content creator. It finds qualified brand leads, vets them against a scoring rubric, and produces warm, human-sounding outreach drafts. Nothing is ever sent without my approval.

Built by Irving Torres ([@irvingtorresyc](https://www.instagram.com/irvingtorresyc), San Diego creator, ~55K followers) with an AI coding agent: I designed the system and directed the architecture, the agent wrote the implementation with me.

## How it works

1. **Find creators.** Per content lane, identify active creators with engaged mid-tier audiences and mine their recent posts for brand partnerships (#ad, #sponsored, paid partnership labels).
2. **Vet.** Confirm each brand is a real company with real products. Anything fake or scammy is flagged "suspected scam, no draft" and gets no outreach.
3. **Fit-check.** Two questions: would this brand plausibly pay $1,000+ for one sponsored post, and does it fit a content lane? Anything below the bar is cut.
4. **Find contacts.** Partnerships, influencer-marketing, PR, or media emails from official sources. Never invented. If nothing real turns up, record the best alternate route.
5. **Draft.** One warm, human outreach message per brand, specific to why the brand fits the audience. Short, no price upfront.
6. **Pipeline.** Every lead tracked with brand, lane, product, contact, fit note, status, and draft link. Cut lists kept so nothing gets re-researched.

Runs monthly. Target 10-15 qualified brands per run. Quality over quantity.

## Standing rules

- Drafts only. Nothing is sent without explicit approval.
- $1,000+ floor. Free-product and $60-150 UGC offers are out.
- No price in outbound drafts. The rate comes up only if the brand replies.
- Suspected scams get flagged, never engaged.

## Techniques

- Agentic coding workflows: human-directed architecture, AI-written implementation.
- Prompt engineering for consistent draft voice.
- Structured outputs: every lead recorded with the same metadata schema.
- Heuristic lead scoring: audience fit, budget floor, scam signals.

## Repo contents

- `SCORING-RUBRIC.md`: the vetting and fit-check criteria.
- `PITCH-FRAMEWORK.md`: the draft framework and voice rules.
- `EXAMPLE-DRAFT.md`: a redacted outreach template with placeholders.

The live lead list and sent drafts stay private. This repo documents the system.

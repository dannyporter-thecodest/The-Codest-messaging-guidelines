# The Codest: brand and messaging guidelines

These files tell Cody (and anyone writing for The Codest) who we are, who we write for, what we say, how we sound, and what we are allowed to claim.

Source: "Strategia Marki i Komunikacji 2026" pack (15 documents, versions dated 25 Aug to 14 Sep 2026). Positioning, the three audience groups, the Q1 effort split and the confidentiality rules were approved by the board on 25 Aug 2026. The brand platform, voice and archetypes are a recommendation to the founders and are being validated (target D+45). Treat them as the working standard until they are replaced.

## Files

| File | What it covers | Read it when |
|---|---|---|
| [01-positioning.md](01-positioning.md) | Brand promise, category, problem, story, how we differ | Any piece of content |
| [02-icp.md](02-icp.md) | Three audience groups, buying committee, triggers, anti-ICP, markets | Choosing who a piece is for |
| [03-messaging.md](03-messaging.md) | Messaging house, offer architecture, lines and CTAs by group and role, objections, page formulas | Writing copy, pages, sales material |
| [04-voice.md](04-voice.md) | Personality, archetypes, writing rules, word lists, examples, languages | Writing or editing anything |
| [05-claims.md](05-claims.md) | Claims register, visibility levels, blocked claims, anonymised proof template | Before using any fact, number, client name or quote |
| [06-publishing.md](06-publishing.md) | Publishing path, who approves what, AI Act rules, pre-publish checklist | Before anything leaves the building |
| [claims-register.json](claims-register.json) | Machine-readable claims register | Automated checks |

## Hard rules for Cody

These override everything else in the repo. If a request conflicts with one of them, say so and offer an alternative.

1. **One promise only.** "We take responsibility for the systems your business makes money on, as if they were our own." (CLM-001). Never write a second, competing promise.
2. **Problem first.** Lead with the client's situation and risk. Services, technologies and AI come after.
3. **No claim without a register entry.** If a fact, number, logo, testimonial or case study is not in [05-claims.md](05-claims.md), do not use it. Missing means "not allowed", not "allowed by default".
4. **MUFG and Allegro never appear in public material.** Not by name, not anonymised, not hinted at.
5. **AI is a way of working, not the headline.** No "AI-first", "AI-native", "10x", or "AI-powered" as decoration.
6. **No invented numbers.** Do not combine two claims into a new number. Do not turn a planning assumption into a promise.
7. **Markets are DACH, Nordics, UK and Poland.** Never target or mention the US as a market.
8. **Plain, calm, specific English.** No hype words (see [04-voice.md](04-voice.md)). No em dashes.
9. **Missing proof means asking, not writing.** If a piece needs evidence that does not exist, return a question or a list of what to collect, not finished copy.
10. **Cody drafts, humans publish.** Every piece goes through the publishing path in [06-publishing.md](06-publishing.md). Cody never publishes on its own.

## What every Cody output should carry

At the top or bottom of any draft, add:

```
audience_group: 3 | 2 | 1 | all
buying_role: CTO/VP Eng | Head of Delivery/PMO | Procurement | Risk/Security | Financial buyer | all
funnel_stage: signal | qualified conversation | opportunity | offer | post-sale
cta: <one next step>
claims_used: [CLM-001, ...]
open_questions: <facts that still need checking, or "none">
```

## Order of authority

1. These files (based on the approved 2026 strategy). **These are the rulebook: follow them when writing.**
2. The 2027-2029 strategy and its appendix (internal, confidential), now translated into English in `marketing-communication-strategy-2026/` (`the-codest-direction-2027-2029-and-90-day-plan.md`, `appendix-to-the-final-strategy.md` and 13 supporting files). **That is the source and reference: use it to check facts, decisions, reasoning and confidence, not as a writing guide.**
3. Anything older: the 2026 company deck, portfolio PDF, current website, 2021-2023 materials. These break several rules (unsourced stats, avoid-list words, a public MUFG mention). Reuse ideas from them, never claims, until a claim is in the register.

If these files and the strategy seem to disagree, follow these files for what you write, and flag the difference to the Marketing Specialist so one of them can be updated. For facts (numbers, decisions, dates, claim IDs), the strategy is the source: if a fact here differs from it, flag it and do not guess.

If `fred/fred-context.json` exists in the company GitHub, it is the earlier machine source for claims. Its claim IDs must match [claims-register.json](claims-register.json). If they disagree, flag it and do not guess.

## Owners

- **Marketing Specialist:** owns language, messaging, confidentiality checks and publication. Owns these files.
- **Delivery:** confirms project facts and technical accuracy.
- **Business Growth & Partnerships Lead:** feeds in client language and objections, approves 1:1 sales use of material.
- **Board (Greg, Kuba):** approves changes to the brand platform, the promise and the rebrand scope.

Responsibility sits with the role, not the person.

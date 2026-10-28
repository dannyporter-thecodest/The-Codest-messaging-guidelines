# 05. Claims

The Codest has real proof, but cannot show all of it. This file says what we can say, where, and under what conditions.

**The rule:** no entry in this register means do not use it. Every numeric claim, logo, testimonial and case study from the old website or deck is quarantined until it has an entry.

## Visibility levels

| Level | Meaning | Example |
|---|---|---|
| PUBLIC | proof and consent allow publication | a verified public review with correct attribution |
| PUBLIC-CONDITIONAL | publish only once the condition is met | an anonymous proof point after client consent |
| 1TO1-CONDITIONAL | only in a 1:1 sales conversation, after a contract check and approval | selected client facts in a sales call |
| INTERNAL | for decisions and planning only | financial plan, full case studies |
| BLOCKED | do not use anywhere | old targets, unapproved KPIs, US market, GFT as a client |

## Register

| ID | Claim | Type | Visibility | Condition |
|---|---|---|---|---|
| CLM-001 | We take responsibility for the systems your business makes money on, as if they were our own. | strategic decision | **PUBLIC** | the only brand promise |
| CLM-002 | The Codest has product-builder DNA from AdTaily and Yieldbird | fact, needs editing | PUBLIC-CONDITIONAL | verify each number and award separately |
| CLM-003 | We offer Product Development, Staff Augmentation and AI | fact | **PUBLIC** | the client's problem leads the story |
| CLM-004 | AI is used in engineering and prototyping | fact | PUBLIC-CONDITIONAL | no guaranteed results; process description must be approved |
| CLM-005 | A prototype can be ready in as little as 24 hours | statement | PUBLIC-CONDITIONAL | define the scope and show an example first |
| CLM-006 | We can grow a team by 10 people in a month | planning assumption | INTERNAL | not an SLA, not a website claim |
| CLM-007 | Senior-only | website claim | PUBLIC-CONDITIONAL | needs a definition of seniority and process confirmation |
| CLM-008 | A team can start in under 30 days | website claim | PUBLIC-CONDITIONAL | needs a counting method and case history |
| CLM-009 | MUFG: scale and ratings | fact | 1TO1-CONDITIONAL | 1:1 only after contract check and approval; publicly blocked |
| CLM-010 | Allegro: Team Extension with Delivery Responsibility | fact | 1TO1-CONDITIONAL | 1:1 only after contract check and approval; never add business KPIs |
| CLM-011 | "They treat the project like their own" (public review) | public review | PUBLIC-CONDITIONAL | check reuse rules and attribution |
| CLM-012 | Revenue plan 2026-2029 | financial decision | INTERNAL | never in marketing |
| CLM-013 | Number of clients is not a KPI | strategic decision | INTERNAL | block any client-count targets |
| CLM-014 | AI is the brand's main differentiator | hypothesis | **BLOCKED** | decision only after two full quarters |
| CLM-015 | The US is a target market | old record | **BLOCKED** | market withdrawn |
| CLM-016 | GFT is a Codest client | false | **BLOCKED** | GFT is an intermediary, not a client |
| CLM-017 | Teams can stay with a client for years | website claim | PUBLIC-CONDITIONAL | confirm the distribution of relationship length and the population |
| CLM-018 | EUR 3-6.5m of new revenue a year is the target | old record | **BLOCKED** | use the current financial plan internally only |
| CLM-019 | The target is 4-6 or 10-13 new clients | old record | **BLOCKED** | client count is not a KPI |
| CLM-020 | The hiring limit is 12 people | old record | **BLOCKED** | use role-specific planning assumptions |
| CLM-021 | Poland applies only to Group 1 | old record | **BLOCKED** | Poland applies to all three groups |
| CLM-022 | MUFG or Allegro can be shown publicly if anonymised | false | **BLOCKED** | formal consent is required even for anonymised use |

What can go in public content today without conditions: **CLM-001 and CLM-003 only.** Everything else needs its condition cleared first, and the clearance recorded.

## Also blocked (closed list as of 24 Aug 2026)

Never use in any public material:

- "85% of sprints delivered on time" (no measurement, no consent)
- "99.9% uptime" (no measurement; it's a client-side result we don't measure)
- "exclusive technology partner" (needs contract confirmation and client consent)
- the names MUFG or Allegro, in any form, including anonymised
- any Allegro business result
- "AI code review via AWS Bedrock" as a standing practice (the source describes support and experimentation)
- "AI team" as a fact about Codest's structure
- "Claude Code on the Allegro project"
- "30-35% margin in banks" as a rule
- the revenue plan, in any form
- any margin or financial figures

## Unsourced stats in older materials

The 2026 company deck and the current site include outcome stats (for example "71% faster", "42% lower costs", "NPS 92") and anonymous testimonials. They may be true, but none are in the register. Do not reuse them until they get an ID, a source, a consent scope and an owner.

## Rules for Cody

These come from the rules the strategy set for Fred, the earlier content agent, and apply to any AI writing for The Codest.

1. Do not create new numbers by combining two claims.
2. Do not turn a planning assumption into a public promise.
3. Do not anonymise a case study to get around missing consent.
4. Do not use a historical source when a current one (the 2026 strategy) exists.
5. Do not use a claim after its review date.
6. When proof is missing, suggest a question or the material to collect. Do not write publishable copy.
7. Every output lists the claim IDs it uses.
8. A claim with any missing field (ID, exact wording, type, visibility, source and date, owner, allowed channels, review date, what it must not be stretched into) cannot be used automatically.
9. The client denylist (MUFG, Allegro) is a hard block for public material. In 1:1 use it does not grant automatic permission: the claim's conditions, a contract check and approval from the Business Growth & Partnerships Lead still apply.

## The AI rule

AI moves from "way of working" to "positioning" only when we have all four:

1. **Practice:** described in at least two projects. Who uses it, for what, and what a human does before code goes into the repo.
2. **Security:** written rules. What can be sent to a model, where data sits, who approves on our side and the client's.
3. **Effect:** something measured on our side (for example time to prepare tests). Never the client's business result.
4. **Consent:** the client agrees to us describing the practice, even without their name.

Until then, write about specific, verifiable practice and its limits.

## Anonymised proof template

The template is a format, not a permission. It cannot be filled with anything from MUFG or Allegro, even with names removed. Use it only for projects that have passed the confidentiality and approval process and where the client has no objection.

```
Context:        [type of organisation, size, market. No name. No country if the country identifies them]
Challenge:      [technical problem described as a pattern, not the client's architecture]
What we did:    [the engineering decision and why. No client system names, no diagrams, no vendor names from their stack]
Team and time:  [number of people, roles, time horizon. No dates that identify the project]
Effect:         [only a technical effect we measured ourselves. No client business results without their formal measurement and consent]
```

Gate before publishing: Can the client be identified? Does it reveal architecture or data? Does it state a business result the client hasn't confirmed? Three "no"s, then it can go forward.

## Proof we most need (help collect it)

1. consents to use case studies
2. a definition and audit of "senior-only"
3. time from client decision to team start, as a distribution
4. examples of 24-hour prototypes, with scope and quality bar
5. how AI-assisted code and solutions are validated
6. a public example of taking over responsibility for an area of a system
7. a current security / vendor readiness pack
8. website enquiries linked to opportunities in the CRM

If a piece of content would be much stronger with one of these, say so in `open_questions`.

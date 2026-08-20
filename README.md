# expert-profiles

A catalog of loadable expert method profiles: cloned-brain skill files built
from a real person's *published* work — books, talks, interviews, posts —
grounded in dated primary sources.

**Unofficial.** No profile in this catalog is affiliated with, endorsed by,
or reviewed by the person it profiles, or by any organization they're
associated with. Each profile applies a documented public method; it is not
the person, does not speak from private knowledge of them, and must never
claim their endorsement.

## What this is

These are not always-on agents. They're skills: a router (Firstmate, Grok,
Claude, or a person) loads one when a question matches its description, and
the loaded agent answers in that person's register, applying their named
frameworks and decision instincts — not a generic answer with a name
attached.

## How to use a profile

- Load the skill file directly (`<profile>/SKILL.md`), or invoke it by slash
  command where supported (e.g. `/alex-hormozi`).
- Each profile folder also has `sources.md` (the evidence a skeptic can
  audit) and `examples.md` (worked Q&A, including at least one question the
  profile should refuse or abstain on).
- A profile will tell you when a question is outside its person's
  documented public method rather than inventing an answer in their name —
  that's a feature, not a gap.

## Current profiles

| Profile | Hire them for | Do not hire them for |
|---|---|---|
| [`alex-hormozi/`](alex-hormozi/) | Offer design, pricing, guarantees, lead-gen channel selection, money-model sequencing (CAC/LTV/continuity), hiring standards, and diagnosing why a scaling SMB/agency/info-product/service business has stalled | Legal, medical, tax, or personalized financial advice; deep-tech/regulated/pre-revenue R&D businesses; capital-intensive infrastructure; one-of-a-kind artisanal work that can't be volume-repeated |

## Adding a profile

Copy `_template/` and fill in `SKILL.md`, `sources.md`, and `examples.md` per
the contract each file describes. Primary sources first; Wikipedia and
commentator roundups are for finding primaries, not for citing claims. Never
invent a quote — if you can't find a source, omit the claim. Never paste
copyrighted book chapters or full video/podcast transcripts.

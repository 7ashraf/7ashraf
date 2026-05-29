# Open-Source Work

A running log of my contributions across the serverless-web / AI-native ecosystem. Public on purpose: it's the evidence that I show up consistently, not just once.

<!-- Maintenance: update this file the same day you ship a PR or triage an issue, while it's fresh. Two minutes now beats reconstructing it at month 12. Keep the "At a glance" counts current — they're what people skim first. -->

---

## At a glance

- **Merged PRs:** 0
- **Issues filed / triaged (with minimal repros):** 0
- **Focus repos:** `vercel/ai` (primary) · `supabase` ecosystem (secondary)
- **Current ladder rung:** Lurk + triage → *(updates as I climb)*
- **Profile:** [github.com/<username>](https://github.com/<username>)

---

## Focus repos & what I'm doing in each

**Primary — [`vercel/ai`](https://github.com/vercel/ai)**
I build on the AI SDK daily, so I contribute to the surfaces I actually hit: examples, docs, provider edge-cases, and — over time — deeper bug fixes as the codebase becomes familiar. This is where I aim for one substantial contribution.

**Secondary — Supabase** ([`supabase-js`](https://github.com/supabase/supabase-js), edge-function examples, CLI, docs)
Scoped to the light, focused surfaces for steady wins. Deliberately *not* diving into the platform monorepo core.

---

## Merged & open PRs

| Date | Repo | Contribution | Type | Status | Reviewer | What I learned |
|---|---|---|---|---|---|---|
| _2026-08-01_ | _`vercel/ai`_ | _[Fix streaming example typo in RSC docs](#)_ | _docs_ | _merged_ | _@reviewer_ | _How the RSC streaming examples are wired; first contact with the repo's CI._ |
| _2026-08-14_ | _`supabase-js`_ | _[Add missing return type on `from().select()` overload](#)_ | _bug_ | _open_ | _—_ | _Their generic inference pattern for query builders._ |

> _Italic rows are examples — delete them and add real entries. Keep `Contribution` as a linked PR title. `Type`: docs · bug · feature · test · triage._

---

## Issues filed & triage (reputation before code)

Minimal reproductions, related-issue links, and probable causes. This is how maintainers learn my name before I ship a line of code.

| Date | Repo | Issue / comment | What I added |
|---|---|---|---|
| _2026-07-20_ | _`vercel/ai`_ | _[#XXXX — tool-calling drops partial chunks on abort](#)_ | _Isolated minimal repro + linked two related issues + traced to the abort handler._ |

> _Delete the example. Log every solid repro or issue comment here, even when they don't lead to a PR — the trail of careful issue work is itself the signal._

---

## Notable contributions (the stories)

Longer write-ups for the contributions worth talking about in an interview. One short paragraph each: what was broken, what I did, what changed. These become résumé bullets and behavioral answers ("tell me about a hard bug") almost verbatim.

### _<Title of the contribution> — `<repo>`_
- **Problem:** _What was actually wrong, and why it mattered._
- **Approach:** _How I scoped it with the maintainer, what I tried, what I chose._
- **Outcome:** _Merged / impact / what shipped. Link the PR._
- **Learned:** _The transferable lesson._

> _Empty for now. The first entry here is the milestone — it means I've crossed from "doc fixes" into a real contribution._

---

## Ladder (where I'm headed)

A reminder of the arc, so I can see the next move at a glance:

1. **Lurk + triage** — reproduce bugs in isolation, comment with minimal repros. *(building reputation before any code)*
2. **Doc fixes + small bugs** — a handful of merged good-first-issue-tier PRs.
3. **One meaningful contribution** — pick a hard-ish open issue, confirm scope with a maintainer, deliver. *(this one is worth thirty doc fixes)*
4. **Be the helper** — answer in the tracker, help other contributors. *(this is what earns the referral)*

---

*Started <month year>. Updated continuously.*

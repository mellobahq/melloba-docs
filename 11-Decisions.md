# 11 — Decisions

> **Title:** 11 — Decisions
> **Purpose:** Append-only log of significant product and technical decisions and their rationale, so choices are not silently re-litigated.
> **Status:** Active
> **Last Updated:** 2026-07-18
> **Dependencies:** None (cross-cutting log).

---

## D-001 — Melloba is a quantitative measurement platform, not an AI parenting coach (PERMANENT / authoritative)

**Date:** 2026-07-18 · **Decided by:** Founder (Simanta)
**Status:** Authoritative project direction. Supersedes any prior framing of Melloba as a coaching/advice product. In force unless the founder explicitly changes it.

**Decision.** Melloba is **NOT** an AI parenting coach and **NOT** an app that gives parenting advice after listening to a conversation. Melloba **is an AI-powered quantitative measurement platform for evaluating and tracking the quality of parent–child interactions over time.** Its primary innovation and long-term IP is a **scientifically grounded quantitative framework** that measures interaction quality and visualizes growth across repeated, standardized observations. Long-term vision: become the standard method parents use to objectively understand and improve the quality of their everyday interactions with their children.

**Always prioritize:** scientific credibility · objective measurement · longitudinal tracking · privacy-first architecture · simplicity · non-judgmental feedback · evidence-based metrics.

**Must avoid:** arbitrary scoring · unsupported psychological claims · guilt-based engagement · addictive mechanics · gamification · unnecessary complexity · becoming a generic AI parenting-advice app.

**Canonical workflow (guiding principle for future decisions):**
Standardized ~5-minute parent–child interaction → upload video → automatic AI analysis → extraction of behavioral metrics → conversion into quantitative scores → personalized report → storage → longitudinal comparison → visualization of measurable growth. **Fully automated; no manual/Wizard-of-Oz review of videos.**

**MVP proves (only this):**
1. A standardized ~5-minute interaction can be analyzed automatically.
2. Meaningful behavioral metrics can be extracted.
3. Those metrics convert into *reliable* quantitative scores.
4. Parents find the scores understandable, trustworthy, and useful.
5. Repeated sessions show *measurable* improvement over time.

**Retained MVP principles (agreed):** keep it focused; build only the minimum; no unnecessary features; no overengineering; privacy-first; no parent judgment; no guilt-based engagement; no addictive mechanics; simplicity wherever possible.

**Scientific-integrity clause.** Every metric must eventually be supported by scientific literature (developmental psychology, language development, behavioral science). Where evidence is limited, **state the assumption explicitly rather than invent an unsupported metric.** Ambition: a framework that could become publishable and peer-reviewable, not merely a consumer feature.

**⚠ Conflict flagged with the Constitution (needs a founder ruling — see Open Questions).** D-001 is in tension with `01-Product-Vision.md` §8 ("No scores, rankings, or leaderboards for children") and with the North Star framing (measure the *parent's* behavior; do not turn interaction into a score; protect against rising parental anxiety). D-001 *narrows* the conflict — Melloba scores the **dyadic interaction**, not the child; tracks **within-family growth**, not cross-family ranking; uses **evidence-based** indices, not arbitrary scores — but does not fully remove it: a numeric quality score can still induce parental self-judgment/anxiety, which the guardrail exists to prevent. **Until the founder formally amends §8 and the North Star (per Vision §12), treat D-001 as governing product direction and the Vision's anti-scoring clauses as pending revision.**

---

## Decisions Made
- **D-001** — Melloba is a quantitative measurement platform, not a coach (2026-07-18, permanent).

## Open Questions
- Formally amend `01-Product-Vision.md` §8 ("no scores") and the North Star to reconcile with D-001? (Requires explicit founder decision per Vision §12.) **Pending founder ruling.**
- Confirm the anxiety guardrail is *preserved in scored form* (growth-framed, dyadic, non-ranking) rather than removed.

## Next Review
- When the founder rules on the §8 / North Star amendment above.

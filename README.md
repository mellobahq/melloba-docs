# Melloba — Product Documentation (`melloba-docs`)

**Melloba is an AI-powered platform that helps parents understand and improve their everyday conversations with their children — turning ordinary moments into deliberate development, privately and without judgment.**

> _Better conversations. Brighter futures._ · Motto: _Talk with, not just to._

## Purpose of this repository

This repo is the **single source of truth for building the Melloba MVP**. It is deliberately lean. Its only job is to help a solo founder **build, launch, validate, and improve the MVP as quickly as possible** — not to document a company. Everything here should be practical and actionable; if a document doesn't help ship or improve the MVP, it doesn't belong.

## How the documentation is organized

Nine primary documents, in a fixed reading order. Each begins with **Title · Purpose · Status · Last Updated · Dependencies** and ends with **Decisions Made · Open Questions · Next Review**. Several are still empty scaffolds — that is intentional; they will be filled as the MVP is defined.

## Reading order

```text
Vision Executive Summary   (fast overview)
        ↓
Product Vision             (the constitution — why we exist)
        ↓
Product Requirements       (what the MVP must do)
        ↓
User Journey               (how a parent experiences it)
        ↓
Features                   (what we build)
        ↓
AI Architecture            (how the AI works)
        ↓
Roadmap                    (in what order we build it)
        ↓
Decisions                  (why we chose what we chose)
        ↓
Ideas                      (what's parked for later)
```

## The documents

| # | Document | What it's for | Status |
|---|----------|---------------|--------|
| — | [01 — Vision: Executive Summary](01-Vision-Executive-Summary.md) | One-read summary of the vision for newcomers and collaborators. | ✅ Complete |
| 01 | [01 — Product Vision](01-Product-Vision.md) | The constitutional document: why Melloba exists, mission, principles, non-goals, and how success is measured. Everything else inherits from it. | ✅ Complete |
| 02 | [02 — Product Requirements](02-Product-Requirements.md) | What the MVP must do — scope, requirements, acceptance criteria. | ⬜ Scaffold |
| 03 | [03 — User Journey](03-User-Journey.md) | The step-by-step experience of a parent using the MVP. | ⬜ Scaffold |
| 04 | [04 — Features](04-Features.md) | The concrete features that deliver the MVP. | ⬜ Scaffold |
| 05 | [05 — AI Architecture](05-AI-Architecture.md) | How AI powers the MVP: transcription, conversation analysis, insight generation. | ⬜ Scaffold |
| 09 | [09 — Roadmap](09-Roadmap.md) | The order of work to build, launch, validate, and improve the MVP. | ⬜ Scaffold |
| 11 | [11 — Decisions](11-Decisions.md) | Append-only log of significant product/technical decisions and rationale. | ⬜ Scaffold |
| 12 | [12 — Ideas](12-Ideas.md) | Parking lot for out-of-scope and future ideas. | ⬜ Scaffold |

_Document numbers 06–08 and 10 (Technical Architecture, Database, UI/UX, Brand Guidelines) were removed in the July 2026 lean-refactor: they were empty, and their concerns are folded into AI Architecture (technical/data) and the Product Vision (brand) for MVP purposes. See `11-Decisions.md` if/when these are reintroduced._

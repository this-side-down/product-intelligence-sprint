# Product Intelligence Sprint

A documentation-first research system for deep product discovery on companies and markets.

This repository is the long-term home for **Product Intelligence Sprints** — structured research cycles that build durable understanding of how a company operates, where it is headed, and where product opportunity may exist.

## Purpose

Each sprint aims to understand a company deeply enough to inform product discovery:

- **Market** — category, dynamics, timing, and structural forces
- **Customers** — segments, jobs-to-be-done, adoption patterns, and unmet needs
- **Product strategy** — positioning, differentiation, and strategic bets
- **Product history** — major launches, pivots, and architectural/evolutionary patterns
- **Business trajectory** — growth model, revenue mix, and strategic inflection points
- **Competition** — direct and indirect alternatives, moats, and substitution risk
- **Likely roadmap** — evidence-based hypotheses about near- and mid-term direction
- **Workflow friction** — where users struggle inside existing products and workflows
- **Prototype opportunities** — concrete, testable product ideas grounded in research

## What this is not

This is **not** interview preparation. It is not a cheat sheet, talking points doc, or résumé exercise.

It is a **product discovery and research system** — designed to produce reusable intelligence that compounds over time.

## Repository layout

| Path | Role |
|------|------|
| [docs/](docs/) | Operating model, conventions, and how to run sprints |
| [research/](research/) | Cross-company themes, methods, and synthesis |
| [companies/](companies/) | One folder per company sprint |
| [artifacts/](artifacts/) | Source material — filings, screenshots, exports, references |
| [templates/](templates/) | Reusable templates for sprints and notes |
| [backlog/](backlog/) | Companies and topics queued for future sprints |

## Getting started

1. Read [docs/getting-started.md](docs/getting-started.md)
2. Read [docs/ai-collaboration.md](docs/ai-collaboration.md) if using an AI assistant
3. Copy [templates/sprint-template.md](templates/sprint-template.md) into `companies/<company-slug>/`
4. Capture sources in `artifacts/<company-slug>/`
5. Track queued work in [backlog/](backlog/)

## Principles

- **Documentation-first** — if it is not written down, it does not exist
- **Lightweight** — prefer markdown, small folders, and incremental commits
- **Continuous iteration** — sprints can be reopened, extended, and ingested over time
- **Evidence over narrative** — distinguish facts, observations, and hypotheses
- **Reusable output** — research should survive beyond a single session or use case

## Contributing

All changes go through pull requests. Open PRs squash-merge automatically once mergeable — see [docs/merge-policy.md](docs/merge-policy.md). Use draft PRs for work in progress.

## License

MIT — see [LICENSE](LICENSE).

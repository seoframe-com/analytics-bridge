# Analytics Bridge 🌉

**Privacy-first analytics router for the Next Generation Internet.**

Analytics Bridge is a lightweight middleware that decouples data collection from data processing. It allows developers to route organic search and user interaction data directly to sovereign, FOSS backends (Matomo, Plausible, or custom PostgreSQL) without letting third-party trackers "sit in the middle."

## Why Analytics Bridge?
Current analytics models force a trade-off: **Ease of use vs. Privacy.** - **The Problem:** Proprietary analytics routers often leak metadata to North American ad-tech stacks.
- **The Solution:** A sovereign, AGPL-v3 router that keeps data within the EU/FOSS ecosystem.

## Status
- [x] Concept & Architectural Design
- [ ] Pre-funding prototype (In Development)
- [ ] NGI0 Commons Fund Submission (Deadline: Feb 1, 2026)

## Technical Vision
- **Protocol Agnostic:** Ingests events via Webhooks, Server Logs, or lightweight JS signals.
- **Sovereign Routing:** Directs data to self-hosted Matomo, Plausible, or local CSV/SQL storage.
- **Privacy-by-Design:** Automated PII (Personally Identifiable Information) scrubbing at the router level.

## Docs
- [PRIVACY.md](./PRIVACY.md) - Our Zero-Knowledge commitment.
- 
## Proposal Status
![Status: Drafting](https://img.shields.io/badge/Status-Drafting-yellow)
The Technical R&D roadmap is currently under internal review for the NLnet/NGI submission.

## License
Licensed under **GNU Affero General Public License v3.0 (AGPL-3.0)** - Protecting the Digital Commons.

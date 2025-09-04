# CivicForge Developer Roadmap

This roadmap is a developer-facing view of CivicForge’s technical journey. While the root `ROADMAP.md` describes high-level milestones and pilots, this file provides more detail for contributors building and maintaining the system.

---

## Phase 1: Repository Foundation (Complete)
- [x] Public GitHub repo created under `Longlight-org`
- [x] Licensing established (AGPL + Commercial)
- [x] Governance docs added (README, CONTRIBUTING, CODE_OF_CONDUCT)
- [x] Documentation folder scaffolded (`/docs`)

---

## Phase 2: Core MVP Features (0–6 months)
- [ ] **Idea Submission API**: REST/GraphQL endpoint to submit proposals
- [ ] **Basic Web UI**: Form-based submission and display of ideas
- [ ] **Commenting System**: Threaded discussions with markdown support
- [ ] **Voting Mechanism**: Simple upvote/downvote or ranked choice
- [ ] **Transparency Log**: Store proposals, comments, and votes in append-only format
- [ ] **Initial AI Integration**: Basic clustering/summarization service for proposals

---

## Phase 3: Pilot-Ready Features (6–12 months)
- [ ] **User Authentication**: OAuth2 + SSO support for org use cases
- [ ] **Admin Dashboard**: Manage proposals, flag inappropriate content, export logs
- [ ] **Data Export**: CSV/JSON exports of proposals, votes, and decisions
- [ ] **Mobile-Responsive Frontend**
- [ ] **First Pilot Deployments**
  - Boise Tree Canopy Equity project
  - Treasure Valley Transportation Futures
  - Constellation Companies “Democracy of Ideas” pilot

---

## Phase 4: Extensibility & Integrations (12–24 months)
- [ ] **Plugin Architecture**: Allow external modules for new deliberation methods
- [ ] **API Integrations**: Slack, Teams, and Discord connectors
- [ ] **Advanced AI Features**: Consensus modeling, argument mapping, contradiction detection
- [ ] **Multi-language Support**
- [ ] **Moderation Toolkit**: Built-in conduct enforcement tools for admins

---

## Long-Term Developer Vision (2–5 years)
- **Federated Hosting**: Allow CivicForge nodes to interconnect while preserving local autonomy
- **Immutable Decision Records**: Explore blockchain or cryptographic logs for auditability
- **Ecosystem Services**: Shared services (translation, AI summarization, security) accessible to all CivicForge instances
- **Robust Developer Community**: Contributors across civic-tech, academia, and organizational design

---

## Contribution Pathways
- Open issues for feature requests or bugs
- Discuss proposals in GitHub Discussions or Issues
- Join Longlight Collective on [Open Collective](https://opencollective.com/longlight) to support financially and follow updates

---

**Note:** This developer roadmap will evolve as pilots begin and contributor feedback shapes the architecture.

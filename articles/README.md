# Articles — AI Implementation Reference Model

This folder contains the article series behind the [Enterprise AI Implementation Reference Model](../README.md). Each article examines one level of the progression, from portfolio strategy through runtime operations and value realization.

The articles explain the reasoning. The [reference model](../README.md) summarizes the structure, decision gates, and framework alignment.

## Series Index

| # | Article | Progression Level | Core Question | Version | Links |
|---|---|---|---|---|---|
| 1 | From AI Pilot to Enterprise Readiness | Series introduction | What has to be true for this particular AI capability to succeed in this particular enterprise? | v1.0 | [Reference model](../README.md) · [Substack](https://rwahai.substack.com/p/from-ai-pilot-to-enterprise-readiness) |
| 2 | Portfolio Strategy — Where Should We Invest, and Why? | Portfolio Strategy | Which AI investments deserve scarce enterprise capacity? | v1.0 | [GitHub](article-2-portfolio-strategy.md) · [Substack](https://rwahai.substack.com/p/portfolio-strategy-where-should-we) |
| 3 | Phase 0 — Enterprise Discovery and Readiness | Phase 0 — Enterprise Discovery & Readiness | Can this organization implement, govern, operate, and realize value from this AI capability under the conditions that actually exist? | v2.0 | [GitHub](article-3-phase-0-enterprise-discovery-and-readiness.md) · [Substack](https://rwahai.substack.com/p/phase-0-enterprise-discovery) |
| 4 | Enterprise Governance & AIMS | Enterprise Governance / AIMS | What policies, accountability, and risk-management environment apply? | — | *Coming soon* |
| 5 | Program Governance & Integration | Program Governance & Integration | How do we coordinate dependencies, resources, decision rights, risks, and organizational change? | — | *Coming soon* |
| 6 | Execution & Production Authorization | Execution & Production Authorization | How do we build, evaluate, and determine whether the enterprise should accept the remaining risk? | — | *Coming soon* |
| 7 | Runtime Operations & Value Realization | Runtime Operations & Value Realization | How do we operate, monitor, adapt, and determine whether the investment delivered the expected outcome? | — | *Coming soon* |

## Companion Articles

Companion articles examine topics that cut across several levels of the progression rather than a single level.

| # | Article | Levels Addressed | Core Question | Version | Links |
|---|---|---|---|---|---|
| C1 | Your AI Model Works. But Does the System? | Phase 0 — Enterprise Discovery & Readiness; Execution & Production Authorization; Runtime Operations & Value Realization | How do we evaluate a component, the boundaries around it and the resulting outcome as one AI-enabled system? | v1.0 | [GitHub](companion-1-your-ai-model-works-but-does-the-system.md) · [Substack](https://rwahai.substack.com/p/your-ai-model-works-but-does-the) |

## Article 3 at a Glance

[Phase 0 — Enterprise Discovery and Readiness](article-3-phase-0-enterprise-discovery-and-readiness.md) covers what happens after an initiative clears portfolio selection and before it becomes an implementation commitment:

- **Where a pilot fits** — A controlled pilot is built and run after an initial Phase 0 decision authorizes that work, not before.
- **Start with the business problem** — Define the outcome, baseline, accountable owner, and whether AI is the right intervention.
- **Readiness as connected conditions** — Leadership and decisions, process and people, data, technology and security, vendors and AI supply chain, risk and obligations, investment economics, and value and operations.
- **Deployment choices** — Keep logical architecture, deployment, and governance distinct; compare any distributed option with a centralized baseline and record the benefit that would justify the added complexity.
- **Test the economics** — A credible financial hypothesis with scenarios and an economic stop or reassessment threshold, not a falsely precise ROI.
- **Authority changes the decision** — Define what the AI may access, which tools it may use, and whether it recommends, prepares, or executes actions, and keep authority bounded when agents delegate work or call services in other environments.
- **Turn discovery into a decision** — Proceed, proceed with conditions, redesign, defer, or stop, supported by a concise executive brief.
- **Not production authorization** — A favorable Phase 0 decision authorizes the next level of work under defined conditions, not production risk acceptance.

## Companion Article 1 at a Glance

[Your AI Model Works. But Does the System?](companion-1-your-ai-model-works-but-does-the-system.md) looks at AI bias, risk, and business outcomes across the whole AI-enabled decision pathway, not only the model:

- **Follow the decision pathway** — Applicant Data → Model → Score → Decision Rule → Workflow → Recruiter → Hiring Manager → Outcome → Future Data.
- **Component → Boundary → Outcome** — Ask what could happen within each component, what could happen between components, and what actually happened.
- **The boundary may matter as much as the component** — Thresholds, workflows, integrations, and human overrides can introduce, amplify, or propagate bias as a technical output becomes a business action.
- **Who owns the risk when it crosses the boundary?** — Ownership often changes at each transition, so risk can become everybody's concern but nobody's responsibility.
- **Technical success is not business success** — Technical Function → System Behavior → Business Outcome are different levels of measurement.
- **Why Phase 0 comes first** — Scoping the AI-enabled system too narrowly narrows the risk assessment and the definition of success.

## Versions and Change Log

Articles are versioned. When an article is updated, for example to reflect a regulatory change, the previous version is archived unchanged and the change is logged.

- [Article Change Log](CHANGELOG.md): every published change, its reason and source, and when it was approved
- [Article Archive](archive/README.md): superseded versions and the versioning policy

## Related Repositories

| Repository | Relevance to the Series |
|---|---|
| [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) | System registration and documentation starting in Phase 0 |
| [AI Vendor Due Diligence Template](https://github.com/rcwah2/ai-vendor-due-diligence-template) | Vendor and AI supply chain readiness, procurement, and contract controls |
| [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) | NIST AI RMF, ISO/IEC 42001, and EU AI Act alignment |
| [AI Governance Portfolio](https://github.com/rcwah2/ai-governance-portfolio) | Case studies and governance reasoning |

## License

Copyright (c) 2026 Lissome Technology Consulting. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](../LICENSE).

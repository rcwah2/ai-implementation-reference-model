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
| C2 | Bias Does Not Begin or End With the Model | Phase 0 — Enterprise Discovery & Readiness; Execution & Production Authorization; Runtime Operations & Value Realization | Where did bias enter the decision pathway, how did the system reduce or amplify it, and what outcome did the complete process produce? | v1.0 | [GitHub](companion-2-bias-does-not-begin-or-end-with-the-model.md) · [Substack](https://rwahai.substack.com/p/bias-does-not-begin-or-end-with-the) |
| C3 | An AI Bias Assessment Found a Problem. What Happens Next? | Enterprise Governance / AIMS; Program Governance & Integration; Execution & Production Authorization; Runtime Operations & Value Realization | How does an organization turn assessment findings into operating governance — ownership, evidence, intervention triggers, and risk acceptance? | v1.0 | [GitHub](companion-3-an-ai-bias-assessment-found-a-problem-what-happens-next.md) · [Substack](https://rwahai.substack.com/p/an-ai-bias-assessment-found-a-problem) |

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

## Companion Article 2 at a Glance

[Bias Does Not Begin or End With the Model](companion-2-bias-does-not-begin-or-end-with-the-model.md) continues the system-level view of bias, distinguishing systemic, training-data, model, human-cognitive and system-level bias and describing how to assess each across the decision pathway:

- **Bias can exist before AI** — Institutional and historical practices produce a pattern that eventually becomes data; an accurate record of previous decisions is not necessarily an appropriate standard for future decisions.
- **How systemic bias becomes data bias** — Historical hiring and performance records already reflect the organization’s previous environment; proxy features can preserve that pattern without a protected characteristic.
- **Bias within the model** — Feature weighting, cross-domain interpretation and wrong prediction objectives can cause a technically accurate model to reproduce previous hiring preferences.
- **Human-cognitive bias** — Automation bias and anchoring mean a human in the loop does not by itself resolve the issue; workload, interface design and organizational expectations influence how AI output is used.
- **System-level bias** — A recurring, unjustified disadvantage can be produced by the combined operation of data, AI, business rules, workflows, people and organizational conditions, even when the model passes its fairness assessment.
- **Baseline, stages and reassessment** — Compare the existing-process baseline, the intended outcome and the actual result; find where a difference first appears across applicant pool → ranking → review → interview → offer → hire; reassess after deployment when the system or model changes.
- **Match the response to the source** — The correct fix depends on where the difference appeared and may be a job requirement, workflow, interface, human responsibility or organizational incentive rather than another model adjustment.
- **Assess the system, not only the model** — This work begins during Phase 0 and continues for as long as the system operates, asking where bias entered, how the system reduced or amplified it, and what outcome the complete process produced.

## Companion Article 3 at a Glance

[An AI Bias Assessment Found a Problem. What Happens Next?](companion-3-an-ai-bias-assessment-found-a-problem-what-happens-next.md) completes the companion series on AI bias, turning an assessment finding into ownership, action and evidence:

- **The assessment found something; it did not decide anything** — The organization needs to ask what the evidence shows, what remains uncertain and what to do while learning more; how many people are affected, how consequential the decision is and whether the outcome can be reversed should shape the response.
- **Match the response to where the difference appeared** — A difference that begins in the ranking may require a change to the data, model or prediction objective; a difference that grows after the ranking enters the workflow may require a change to the interface, business rules, workload or review process.
- **Three ownership responsibilities** — Who operates each control, who owns the complete AI-enabled system, and who has the authority to accept the remaining risk; these may be different people, but each must be named.
- **Responsibility without authority is not accountability** — The AI system owner needs a defined way to require evidence, coordinate corrective action, restrict or pause the system's use, escalate unresolved risk and approve continued use.
- **Monitoring needs a defined response** — Indicators such as review rates, independent sampling results and progression rates matter only when a meaningful signal leads to a defined action; otherwise monitoring is reporting.
- **Human in the loop is not enough** — Human review becomes an operational control when its purpose, information, time, authority and expected response are explicit; overrides are documented with who made them, why and what happened afterward.
- **Verify the corrective action worked** — Return to the baseline and compare the same stages of the decision pathway before and after the intervention: Baseline → Finding → Corrective Action → Actual Result; the action stays open until evidence shows the intended effect.
- **Reassess when the system changes** — Recruiter capacity, workflow, vendor interface or operating conditions can change the outcome even when the model does not; reassess on any meaningful change and keep the assessment as part of the system's operating record.
- **Close the governance loop** — Finding → Decision → Owner → Action → Evidence → Reassessment; the organization deploying the AI-enabled process remains accountable for the outcome it produces.

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

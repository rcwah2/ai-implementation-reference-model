# From AI Pilot to Enterprise Readiness

## AI Implementation Reference Model

A reference model for connecting strategy and governance to coordinated execution, production operations, and measurable outcomes.

> **What has to be true for this particular AI capability to succeed in this particular enterprise?**

This is the first article in a six-part series exploring the Enterprise AI Implementation Reference Model. The model is not intended to be a definitive methodology for implementing AI — AI is changing too quickly, and organizations are too different for that to make sense. It is guidance for identifying which activities, controls, decisions, and evidence are necessary for a given AI capability in a given enterprise at a given level of risk.

> **A successful pilot is not the same as enterprise readiness.**

---

## Core Principles

### The challenge is not the number of activities. It is the dependencies.

As AI enters an enterprise, it interacts with business processes, employees, customers, data, identities, APIs, vendors, security controls, regulatory requirements, and operating teams. One dependency reveals another — business alignment connects to value realization, workflow design connects to organizational change, data readiness connects to privacy and cybersecurity, vendor choices create operational dependencies, and production creates requirements for monitoring, support, incident response, continuity, and recovery.

The value of a strong program leader is not in personally executing every technical activity. It is in making cross-functional dependencies visible, getting decisions to the right level, managing resource and risk conflicts, and ensuring that leaders have enough evidence to make informed decisions.

### The project is only one level of the problem.

Enterprise AI cannot always be managed as a collection of independent projects. Organizations may have initiatives competing for the same data, platforms, funding, cybersecurity resources, specialized talent, and business capacity. That creates a **portfolio problem**:

- Which AI investments align with strategy?
- Which should receive funding and scarce resources?
- Which are actually ready to proceed?
- Where are multiple initiatives creating common dependencies or concentrations of risk?
- Which should be accelerated, redesigned, deferred — or stopped?

At the **program level**, the challenge becomes integration. Data, technology, cybersecurity, governance, vendors, organizational change, and operations may cut across multiple projects. Program governance establishes how dependencies are managed, where risks are escalated, what evidence is required, and who has the decision rights to accept, mitigate, transfer, or reject risk at key points.

### Change management begins before rollout.

Organizational change is not something that starts when training begins. It starts during discovery — leadership alignment matters early, managers need to understand how roles may change, business users need to be involved when workflows are redesigned, and adoption continues after production. Organizational change and adoption is a **cross-cutting discipline** from early discovery through value realization.

### Governance should guide execution, not become a separate universe.

An organization may establish an AI Management System under ISO/IEC 42001 and use NIST AI RMF to support its approach to AI risk. What matters operationally is whether governance expectations become real work, real decisions, real evidence, and real controls. A policy alone does not implement governance — programs and operating teams have to translate policy into the way AI is actually designed, approved, deployed, and operated.

### Agility and governance do not have to compete.

> **Sprints create learning. Gates authorize changes in business exposure.**

A team can iterate quickly during development. But connecting AI to sensitive information, granting additional permissions, allowing autonomous actions, or authorizing production can materially change the organization's exposure. Those decisions may require a different level of evidence and decision authority. The objective is not bureaucracy — it is knowing when an experiment becomes an enterprise risk decision.

### Production is not the finish line.

The lifecycle does not end at Build → Deploy. It continues:

**Operate → Monitor → Respond → Improve**

Data can drift. Performance can degrade. Models and vendor platforms can change. Cyber threats evolve. Business processes, regulatory expectations, and employee and customer behavior change. A system that was acceptable under one set of assumptions may no longer be acceptable when those assumptions materially change. Material changes may require reauthorization.

### Runtime governance matters.

A governance policy might say that an AI agent cannot access a particular system, spend beyond a threshold, or execute a consequential action without approval. But a policy is not the same as enforcement. Production environments may need controls that operate while the AI is running:

- Identity and access controls
- Bounded permissions
- Permitted tools and destinations
- Authorization checks
- Transaction limits
- Human approval for consequential actions
- Telemetry
- Escalation
- Containment
- Shutdown capabilities

> **Governance defines what the AI should be allowed to do. Runtime controls help determine what it can actually do.**

---

## The Progression

| Level | Question |
|---|---|
| **Portfolio Strategy** | Where should we invest, and why? |
| **Phase 0 — Enterprise Discovery & Readiness** | Should this initiative move forward, and is the organization ready? |
| **Enterprise Governance / AIMS** | What policies, accountability, and risk-management environment apply? |
| **Program Governance & Integration** | How do we coordinate dependencies, resources, decision rights, risks, and organizational change? |
| **Implementation Reference Model** | What workstreams and readiness conditions apply? |
| **Execution & Production Authorization** | How do we build, evaluate, and determine whether the enterprise should accept the remaining risk? |
| **Runtime Operations & Value Realization** | How do we operate, monitor, adapt, and determine whether the investment delivered the expected outcome? |

Organizational change and adoption spans the entire progression. Agentic AI controls and runtime governance also span the progression — from Phase 0 (should we deploy an autonomous agent?) through Runtime Operations (how do we monitor, contain, and shut it down?).

---

## Workstream Areas

The reference model spans the following areas. Not every AI initiative requires all of them — applicability depends on the system's risk profile, autonomy level, and regulatory context.

- **Business strategy and value** — Investment justification, expected outcomes, value realization
- **Workflow and process design** — How AI changes how work moves through the organization
- **Data and information** — Readiness, provenance, sensitivity, privacy
- **Model development and evaluation** — Build, test, evaluate, iterate
- **Cybersecurity and privacy** — Exposure assessment, security controls, data protection
- **AI governance and risk** — Policies, accountability, risk processes, controls, evidence
- **Vendor and third-party dependencies** — Due diligence, procurement, ongoing monitoring
- **Organizational change and adoption** — Leadership alignment, role changes, training, adoption tracking
- **Operational support and resilience** — Monitoring, incident response, continuity, recovery
- **Production authorization and runtime operation** — Decision gates, runtime controls, reauthorization

### Agentic AI Controls (Cross-Cutting)

Agentic AI — systems that can invoke tools, access systems, communicate externally, initiate transactions, and take consequential actions — creates a distinct set of governance and control requirements that span the entire progression. A governance policy might say that an AI agent cannot access a particular system, spend beyond a threshold, or execute a consequential action without approval. But a policy is not the same as enforcement.

> **Governance defines what the AI should be allowed to do. Runtime controls help determine what it can actually do.**

Agentic AI controls cut across every level of the progression:

| Progression Level | Agentic AI Question |
|---|---|
| **Portfolio Strategy** | Does this use case require autonomous action? Is the organization ready to govern it? |
| **Phase 0 — Discovery & Readiness** | What authority will the agent have? What systems will it access? What are the consequences of unintended actions? |
| **Enterprise Governance / AIMS** | What policies apply to autonomous agents? Who owns the risk of agent decisions? |
| **Program Governance & Integration** | How are agent permissions coordinated across initiatives? Where do agent capabilities create concentrations of risk? |
| **Implementation** | What runtime controls are needed? (identity, bounded permissions, permitted tools, authorization checks, transaction limits) |
| **Execution & Production Authorization** | Who authorizes an agent to take consequential actions? What evidence is required? |
| **Runtime Operations & Value Realization** | How do we monitor agent behavior against baseline? How do we contain and shut down an agent that behaves unexpectedly? |

Runtime controls that may be required for agentic AI in production:

- Identity and access controls
- Bounded permissions
- Permitted tools and destinations
- Authorization checks
- Transaction limits
- Human approval for consequential actions
- Telemetry and behavioral monitoring
- Delegation chain logging
- Escalation
- Containment
- Shutdown capabilities

**Framework references:** NIST AI 100-4 (Agentic AI), NIST AI 100-5, CSA Agentic AI Governance Profile, OWASP Top 10 for Agentic Applications, NIST CAISI AI Agent Standards Initiative

> See [AI Vendor Due Diligence Template](https://github.com/rcwah2/ai-vendor-due-diligence-template) — Agentic AI Controls section for assessment questions covering autonomy classification, tool access, identity, kill switch, and behavioral monitoring

---

## Decision Gates

Each gate represents a point where an experiment becomes an enterprise risk decision. The question is not whether every activity was completed, but whether sufficient evidence exists for the decision-maker to authorize a change in business exposure.

| Gate | Criteria to Proceed | If Not Met |
|---|---|---|
| Portfolio → Phase 0 | Investment aligns with strategy; funding and resources available | Do not initiate |
| Phase 0 → Governance | Business problem validated; executive alignment confirmed; enterprise readiness assessed | Do not proceed to design |
| Governance → Program | Policies, accountability, and risk framework established | Do not begin implementation |
| Program → Implementation | Dependencies mapped; decision rights assigned; resource conflicts resolved | Do not execute |
| Implementation → Production Authorization | Controls implemented; testing complete; oversight defined; risk accepted by authorized decision-maker | Do not deploy to production |
| Production Authorization → Agentic AI Gate | Agent authority defined; runtime controls tested; containment and shutdown verified; human approval workflow operational | Do not authorize agent actions |
| Agentic AI Gate → Runtime Operations | Monitoring operational; incident response tested; value metrics defined; behavioral baseline established | Do not certify; continue monitoring |
| Runtime → Reassessment | Value realized; material changes assessed; reauthorization if needed | Re-enter at appropriate level |

---

## Where CPMAI Fits

The reference model is not intended to replace established AI lifecycle methodologies such as PMI-CPMAI. CPMAI provides a structured lifecycle for progressing an AI initiative through business understanding, data understanding, data preparation, model development, evaluation, and operationalization.

> **CPMAI provides an AI delivery lifecycle. The reference model looks at the broader enterprise environment that may need to support that lifecycle.**

While the AI delivery team progresses through the lifecycle, other parts of the enterprise may have work to complete — cybersecurity may need to evaluate exposure, privacy may need to resolve data questions, vendors may need additional due diligence, operations may need a support model, governance may require evidence, users may need preparation, and executives may need to authorize additional business exposure. These activities do not replace the AI lifecycle. They surround it.

---

## Framework Alignment

| Progression Level | NIST AI RMF Function | ISO/IEC 42001 Clauses |
|---|---|---|
| Portfolio Strategy | GOVERN | Clauses 4-5, Annex A.2/A.3 |
| Phase 0 — Discovery & Readiness | MAP | Clause 6.1.4, Annex A.4/A.5 |
| Enterprise Governance / AIMS | GOVERN | Clauses 4-5, 6.1, Annex A.2/A.3 |
| Program Governance & Integration | GOVERN, MANAGE | Clause 6.1.2, Annex A.10 |
| Implementation Reference Model | MEASURE, MANAGE | Clauses 8, 10, Annex A.6/A.8 |
| Execution & Production Authorization | MEASURE, MANAGE | Clause 8.3, Annex A.8 |
| Runtime Operations & Value Realization | MEASURE, MANAGE | Clause 9, Annex A.6 |
| Agentic AI Controls (cross-cutting) | GOVERN, MEASURE, MANAGE | Annex A.8.4, A.10; NIST AI 100-4/100-5 |

> See [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) for detailed framework mapping

---

## Related Repositories

This reference model is the hub that ties together all governance artifacts:

| Repository | Role in the Model |
|---|---|
| [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) | Phase 0 / Governance: System registration and documentation |
| [AI Vendor Due Diligence Template](https://github.com/rcwah2/ai-vendor-due-diligence-template) | Implementation: Vendor assessment, procurement, and contract requirements |
| [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) | Governance: Framework selection and alignment (NIST AI RMF, ISO 42001, EU AI Act) |
| [AI Governance Portfolio](https://github.com/rcwah2/ai-governance-portfolio) | Case studies and governance reasoning |
| [Case Studies](https://github.com/rcwah2/Case-Studies) | Enterprise delivery experience |

---

## Read the Series

The full reasoning, narrative, and case studies behind this reference model are published as a 7-part series on Substack:

1. **From AI Pilot to Enterprise Readiness** — [rwahai.substack.com](https://rwahai.substack.com/p/from-ai-pilot-to-enterprise-readiness)
2. **Portfolio Strategy — Where Should We Invest, and Why?** — [rwahai.substack.com](https://rwahai.substack.com/p/portfolio-strategy-where-should-we)
3. Phase 0 — Enterprise Discovery & Readiness *(coming soon)*
4. Enterprise Governance & AIMS *(coming soon)*
5. Program Governance & Integration *(coming soon)*
6. Execution & Production Authorization *(coming soon)*
7. Runtime Operations & Value Realization *(coming soon)*

---

## A Reference Model, Not a Recipe

The question is not:

> Did we complete every activity in the model?

The better question is:

> Which activities, controls, decisions, and evidence are necessary for this particular AI capability, in this particular enterprise, at this particular level of risk?

A low-risk internal assistant should not be treated the same as an autonomous system making consequential decisions or taking actions inside a regulated environment. Agentic AI — where systems can take actions, not just generate information — raises the stakes at every decision gate. The question of what authority an AI agent has, and who approved that authority, is not optional. Adapt this model to your organization's specific requirements, risk tolerance, and regulatory obligations.

---

## Author

**Raymond Wah** — Enterprise AI Governance & Implementation Program Leader

- LinkedIn: [linkedin.com/in/raymondwah](https://www.linkedin.com/in/raymondwah/)
- Substack: [rwahai.substack.com](https://rwahai.substack.com/)
- GitHub: [github.com/rcwah2](https://github.com/rcwah2)

## License

Copyright (c) 2026 Lissome Technology Consulting.

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it, including for commercial purposes, provided you give appropriate credit to Lissome Technology Consulting, link to the license, and indicate if changes were made. See [LICENSE](LICENSE) for the full terms.

This reference model is provided for educational and professional use. Adapt it to your organization's specific requirements, risk tolerance, and regulatory obligations.

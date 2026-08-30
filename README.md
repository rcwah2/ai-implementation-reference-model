# From AI Pilot to Enterprise Readiness

## AI Implementation Reference Model

A phased reference model for moving AI initiatives from pilot to enterprise-ready production. Designed for program managers, governance leads, and implementation teams who need a structured framework for navigating the gap between a successful pilot and operational AI.

> **A successful pilot is not the same as enterprise readiness.**

## Why This Exists

Most AI initiatives fail not at the pilot stage but at the transition to production. The pilot proves the technology works in a controlled environment. Enterprise readiness requires governance, vendor management, risk assessment, monitoring, incident response, and organizational alignment that pilots rarely address.

This reference model defines the phases, activities, artifacts, and decision gates that must be in place before AI can move from experiment to enterprise operation safely.

## The Model

### Phase 0: Governance Before Execution

Before any AI system is deployed, establish the governance foundation:

- **AI policy** — Define acceptable use, accountability, and oversight requirements
- **Roles and responsibilities** — Assign AI system owners, governance leads, and escalation paths
- **Risk assessment framework** — Select and align to NIST AI RMF, ISO/IEC 42001, EU AI Act
- **AI system inventory** — Register every AI system with an owner, risk tier, and classification

> Artifacts: [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) | [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk)

### Phase 1: Context and Risk Mapping

Define the scope, intended use, and risk profile of the AI system:

- **Intended use and stakeholders** — Document the business purpose, affected parties, and deployment context
- **Risk classification** — Classify by EU AI Act tier, NIST AI RMF risk level, and business criticality
- **Impact assessment** — Conduct AI-specific impact assessment (bias, privacy, safety, societal)
- **Data provenance** — Document training data sources, lineage, and sensitivity

> Artifacts: [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) — System identification, classification, and data/model sections

### Phase 2: Vendor Assessment and Procurement

Assess third-party AI systems and vendors before procurement:

- **Due diligence questionnaire** — Assess vendor capabilities across governance, security, privacy, financial viability, incident response, and agentic AI controls
- **Vendor risk scoring** — Score responses against organizational risk tolerance
- **Contract requirements** — Define SOW/operational requirements and contract clause checklist for legal review
- **Agentic AI assessment** — If the system includes autonomous agents, assess autonomy classification, tool access, identity, kill switch, and behavioral monitoring

> Artifacts: [AI Vendor Due Diligence Template](https://github.com/rcwah2/ai-vendor-due-diligence-template) — Three-part governance pack

### Phase 3: Implementation and Controls

Deploy the AI system with appropriate controls in place:

- **Security controls** — Encryption, access management, vulnerability management
- **Human oversight** — Define oversight mechanisms, escalation thresholds, and override capabilities
- **Bias and fairness testing** — Conduct and document bias testing methodology and findings
- **Explainability** — Provide model documentation, feature importance, and transparency artifacts
- **Agentic AI controls** — Runtime guardrails, approval gates, behavioral monitoring, delegation chain logging

### Phase 4: Monitoring and Operations

Maintain ongoing oversight of the AI system in production:

- **Performance monitoring** — Track accuracy, drift, and behavioral changes
- **Drift detection** — Monitor for model drift, data drift, and concept drift
- **Incident response** — Maintain AI-specific incident response plan with evidence preservation
- **Supplier monitoring** — Reassess vendors on a defined cadence
- **Agentic AI monitoring** — Behavioral monitoring against baseline, delegation chain monitoring, autonomy calibration

### Phase 5: Review and Improvement

Continuously improve the AI governance program:

- **Internal audit** — Audit AI systems against governance requirements
- **Management review** — Review program effectiveness and make improvements
- **Corrective actions** — Address findings from audits, incidents, and monitoring
- **Program maturity** — Assess and advance governance program maturity over time

## Decision Gates

Each phase has a decision gate that must be passed before proceeding:

| Gate | Criteria to Proceed | If Not Met |
|---|---|---|
| Phase 0 → 1 | AI policy approved, roles assigned, risk framework selected | Do not begin AI system deployment |
| Phase 1 → 2 | Intended use documented, risk classification complete, impact assessment done | Do not procure or deploy |
| Phase 2 → 3 | Vendor due diligence complete, risk accepted, contracts in place | Do not proceed with vendor |
| Phase 3 → 4 | Security controls implemented, oversight defined, testing complete | Do not move to production |
| Phase 4 → 5 | Monitoring operational, incident response plan tested | Continue monitoring, do not certify |
| Phase 5 → 0 | Audit complete, corrective actions addressed | Re-enter at Phase 0 for updates |

## Framework Alignment

| Phase | NIST AI RMF Function | ISO/IEC 42001 Clauses |
|---|---|---|
| Phase 0 | GOVERN | Clauses 4-5, Annex A.2/A.3 |
| Phase 1 | MAP | Clause 6.1.4, Annex A.4/A.5 |
| Phase 2 | GOVERN, MANAGE | Annex A.10 (suppliers) |
| Phase 3 | MEASURE, MANAGE | Clause 6.1.2, Clauses 8, 10, Annex A.6/A.8 |
| Phase 4 | MEASURE, MANAGE | Clause 9, Annex A.6 |
| Phase 5 | GOVERN | Clause 9.2, 9.3 |

> See [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) for detailed framework mapping

## Related Repositories

This reference model is the hub that ties together all governance artifacts:

| Repository | Role in the Model |
|---|---|
| [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) | Phase 0-1: System registration and documentation |
| [AI Vendor Due Diligence Template](https://github.com/rcwah2/ai-vendor-due-diligence-template) | Phase 2: Vendor assessment and procurement |
| [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) | Phase 0: Framework selection and alignment |
| [AI Governance Portfolio](https://github.com/rcwah2/ai-governance-portfolio) | Case studies and reasoning |
| [Case Studies](https://github.com/rcwah2/Case-Studies) | Enterprise delivery experience |

## Read the Series

The full reasoning, narrative, and case studies behind this reference model are published as a 6-part series on Substack: [rwahai.substack.com](https://rwahai.substack.com/)

## Author

**Raymond Wah** — Enterprise AI Governance & Implementation Program Leader

- LinkedIn: [linkedin.com/in/raymondwah](https://www.linkedin.com/in/raymondwah/)
- Substack: [rwahai.substack.com](https://rwahai.substack.com/)
- GitHub: [github.com/rcwah2](https://github.com/rcwah2)

## License

This reference model is provided for educational and professional use. Adapt it to your organization's specific requirements, risk tolerance, and regulatory obligations.

---

*"The challenge is not the number of activities. It is the dependencies."*

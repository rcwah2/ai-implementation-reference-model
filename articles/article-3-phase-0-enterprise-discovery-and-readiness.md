# Phase 0 — Enterprise Discovery and Readiness

*AI Implementation Reference Model — Article 3 of 7*

**Before an AI initiative becomes an implementation commitment, determine whether the enterprise can support it.**

In [Article 2, I examined portfolio strategy](https://rwahai.substack.com/p/portfolio-strategy-where-should-we): which AI investments deserve scarce enterprise capacity, and which should be redesigned, deferred, or stopped.

Suppose an initiative clears that first hurdle. Leadership sees a meaningful opportunity. The team may have an early demonstration of technical feasibility.

The next question is different:

> Can this organization implement, govern, operate, and realize value from this AI capability under the conditions that actually exist?

That is the purpose of **Phase 0 — Enterprise Discovery and Readiness**.

Portfolio selection earns an initiative a closer look. It does not yet establish that the business process, data, systems, people, controls, and operating model are ready for a larger commitment.

## Where a pilot fits

In the intended sequence, portfolio strategy selects an opportunity for closer review. Phase 0 then frames the business problem, tests readiness, defines the pilot's purpose and success criteria, and identifies the conditions for proceeding. **A controlled pilot is built and run after an initial Phase 0 decision authorizes that work.** Its results inform a later decision about further investment, scale, and production readiness.

A narrowly scoped feasibility test may be needed *during* Phase 0 to resolve a specific unknown. That test should have an owner, limits, and a defined question; it should not quietly become a production pilot. In organizations where a pilot has already started, Phase 0 can still be applied before expanding authority, spending, or deployment. The sequence describes a sound decision path, not a claim that every organization began there.

## An attractive use case can still be unready

Imagine a company wants an AI assistant to answer customer questions and eventually resolve service requests. The early demonstration is impressive. It retrieves useful information, drafts clear responses, and appears to save time.

Before authorizing a controlled pilot or broader implementation, the enterprise questions begin.

Which knowledge source is authoritative? Are customer records complete and current? Can the assistant see information that a particular employee should not see? Who approves an answer that changes a customer's entitlement? What happens when the system is wrong, unavailable, or manipulated? Will the service team have time and training to supervise it? Who measures whether customers actually receive better service?

If the assistant later gains the ability to update accounts, issue credits, or contact customers, the authority question changes again.

None of those questions means the initiative should stop. They mean technical feasibility is only part of the investment decision. The enterprise needs to understand the conditions under which a pilot can safely test the idea and a successful result can become a dependable business capability.

## Start with the business problem

Phase 0 should begin before the organization becomes attached to a model, vendor, or agent design.

What problem is the organization trying to solve? What happens today, and why is it inadequate? Which outcome would justify the investment? Who owns that outcome after implementation? What baseline will allow leadership to tell whether the situation improved? What budget might be required to reach and sustain that outcome?

This also means asking whether AI is the right intervention. A poorly defined process does not become a good process because an AI system sits inside it. Sometimes the immediate work is to clarify decisions, repair data, simplify handoffs, or change an existing application. AI may still have a role, but that role should emerge from the business problem.

The question is not merely whether the system can perform a task in a demonstration. It is whether performing that task changes the outcome that justified the investment.

## Readiness is a connected set of conditions

I look at readiness across several domains because a gap in one can limit the entire initiative.

| Domain | Phase 0 question |
|---|---|
| Leadership and decisions | Is there a sponsor, an accountable business owner, and a clear path for resolving cross-functional decisions and accepting risk? |
| Process and people | Is the current workflow understood, and can the organization redesign roles, approvals, exceptions, and training around the new capability? |
| Data | Are sources sufficiently reliable, accessible, current, permitted for the intended use, and owned by someone who can resolve problems? |
| Technology and security | Can the capability integrate with existing systems and be protected, monitored, supported, contained, and recovered? |
| Vendors and AI supply chain | Which providers supply the model, orchestration, application, cloud services, and data—and which responsibilities remain with the enterprise? |
| Risk and obligations | What privacy, security, regulatory, contractual, safety, and resilience constraints affect the intended use? |
| Investment economics | What is the likely investment range, who funds it, and what value must materialize for the return to justify the cost and risk? |
| Value and operations | How will benefits be measured, and who will operate and improve the capability after launch? |

This is not an instruction to complete every implementation task during discovery. Phase 0 identifies material gaps, dependencies, owners, and decisions early enough to change the investment path.

For example, a provider may offer strong security evidence for its model service. That does not answer whether the enterprise configured retrieval permissions correctly, has rights to use its source data, or can support the business workflow when the provider changes. Vendor assurance and enterprise readiness are related, but they are not interchangeable.

The same issue appears across a portfolio. Several initiatives may rely on one model provider, cloud service, data source, or security review team. A dependency that looks manageable inside one project can become a concentration of risk when viewed across the enterprise.

## Test the economics before committing to scale

Phase 0 does not need a falsely precise ROI figure. It does need a credible financial hypothesis. What will discovery, integration, controls, change management, vendor services, human review, and ongoing operations cost? Which budget owns those costs? Are projected benefits based on a measured baseline, an assumption, or a vendor claim?

Leadership can use a range of scenarios: the expected cost and benefit, a less favorable case, and the conditions under which the initiative no longer makes economic sense. The question is whether the potential return warrants the next investment, given uncertainty and the other demands on enterprise capacity. Actual ROI can only be tested against measured costs and realized benefits after deployment.

## Authority changes the readiness decision

An assistant that drafts a response and an agent that executes a transaction should not receive the same approval simply because they use similar models.

During Phase 0, leadership should establish the proposed boundary of authority. What information may the AI access? Which systems and tools might it use? Will it recommend actions, prepare them for human approval, or execute them? Which actions could affect money, rights, records, safety, or external communications? Who can pause or withdraw that authority?

The detailed architecture and runtime controls come later. But if the organization cannot describe the intended authority and its consequences, it cannot make an informed decision about the investment, its risk, or the level of oversight required.

This question matters even if the first release is deliberately limited. A plausible future expansion should be visible in the roadmap rather than appearing as an informal permission change after the pilot succeeds.

## Turn discovery into a decision

Phase 0 is useful when it produces a decision leaders can act on. A concise executive brief should establish:

1. The business problem, intended outcome, baseline, and accountable owner.
2. The proposed AI capability, its users, affected people, and limits of authority.
3. The most important readiness findings and shared dependencies.
4. Material security, privacy, vendor, regulatory, resilience, and change concerns.
5. A directional budget, cost and benefit assumptions, expected return range, funding owner, and economic stop or reassessment threshold.
6. Prerequisites, owners, effort, and the sequence in which gaps must be addressed.
7. A recommendation and the evidence supporting it.

The decision might be to **proceed**, **proceed with conditions**, **redesign**, **defer**, or **stop**. These are different decisions, not variations of “yes.”

“Proceed with conditions” should name the condition, its owner, the evidence required to close it, and the next review point. “Defer” should explain what must change before the initiative is reconsidered. “Stop” should record why the investment no longer justifies the expected value, capacity, or risk.

That discipline gives executives a way to preserve a promising idea without pretending the organization is ready to scale it today.

## Phase 0 is a starting decision, not production authorization

A favorable Phase 0 decision authorizes the next level of work under defined conditions. It does not mean every control has been built, every test passed, or production risk accepted.

Those decisions belong to the subsequent implementation and governance process: architecture, data and model work, security and privacy engineering, vendor responsibility, evaluation, operational readiness, and formal production authorization. Agile teams can learn and iterate during delivery, while leaders retain decision rights when the proposed capability gains access, authority, scale, or business exposure.

This is where the Enterprise AI Implementation Reference Model helps me connect the pieces. It turns a readiness decision into coordinated work, named owners, evidence, and gates. The work is tailored to the actual system and risk. A purchased internal assistant, a custom predictive model, and an agent that can change business records will not follow identical paths.

The purpose of Phase 0 is not to make every AI initiative look ready. It is to give leaders enough visibility to invest deliberately—and to recognize when the enterprise must change before the technology can succeed.

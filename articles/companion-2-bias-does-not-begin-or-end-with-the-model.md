# Bias Does Not Begin or End With the Model

Enterprise AI Implementation Reference Model — Companion Article 2 of 3

**Understanding systemic, data, model, human and system-level bias across the decision pathway**

An AI hiring system identifies a group of applicants as the strongest matches for a position.

Other candidates remain available for review. The recruiter starts with the recommended group, finds enough people to interview and moves forward.

The system did not reject the remaining applicants. The recruiter could have reviewed them.

But did those applicants receive meaningful consideration?

And if qualified candidates were repeatedly overlooked, where did the bias occur?

Was it in the historical data?

Was it in the model?

Was it in how the candidates were ranked and presented?

Was it in how recruiters used the recommendations?

Or was it created by the way all of these elements worked together?

That last question is the focus of this article.

## Bias Can Exist Before AI

In 2018, Reuters reported that Amazon abandoned an experimental résumé-screening tool after finding that it penalized résumés containing the word “women’s.” The tool had learned from a decade of applications submitted to a company whose technical workforce was predominantly male.

The model learned from the organization’s history.

But where did the original pattern come from?

Suppose an organization has historically recruited from a limited number of universities and professional networks. Candidates with nontraditional backgrounds may have received fewer interviews. Employees entering through different routes may have received fewer opportunities, less mentoring or different performance evaluations.

Those conditions existed before AI.

NIST describes bias arising from institutional practices and established procedures as systemic bias.

Eventually, the results of those practices become data.

The data may accurately show who was hired, promoted or evaluated as a strong performer. But an accurate record of previous decisions is not necessarily an appropriate standard for future decisions.

## How Systemic Bias Becomes Data Bias

Suppose the organization uses its historical hiring and performance records to train a hiring model.

Those records may contain fewer examples of successful employees with nontraditional career paths. Performance labels may also reflect differences in assignments, managerial support or opportunities for advancement.

The model is now learning from data that already reflects the organization’s previous environment.

This is training-data bias.

The central question is:

> Does the data measure a person’s capability, or does it partly measure who previously received an opportunity?

Removing protected characteristics does not necessarily remove the problem.

ZIP codes, universities, employment gaps and job titles may act as proxies for broader social or organizational conditions. The model may learn patterns associated with those conditions without receiving a protected characteristic directly.

Training-data bias affects what the model learns.

## Bias Within the Model

Model bias concerns how the AI converts information into a score, prediction or ranking.

A model may give too much weight to conventional job titles. It may interpret experience from one industry more accurately than comparable experience from another. It may also produce different error rates among relevant populations.

The organization can create another problem by selecting the wrong prediction objective.

A model that predicts whom previous managers would have hired is not necessarily predicting who can perform the work.

A technically accurate prediction of previous hiring decisions could simply reproduce previous hiring preferences.

Model bias affects how candidates are evaluated.

But the decision pathway does not end when the model produces its ranking.

## What Happens When People Use the Ranking?

Assume the recruiting application displays the recommended candidates first. Lower-ranked candidates remain available.

Recruiters may treat the ranking as more than a sort order. They may begin with the recommended candidates, give greater weight to those profiles and stop when they have enough people to interview.

Two forms of human-cognitive bias may become relevant.

**Automation bias** can cause someone to give too much weight to an automated recommendation.

**Anchoring** can cause the first information presented to influence how later information is interpreted.

Neither requires a recruiter to intend to discriminate. Workload, interface design and organizational expectations can influence how a person responds to an AI recommendation.

This is why simply placing a human in the loop does not resolve the issue.

The organization still needs to understand what the person can see, what the person is expected to review and how the AI output influences the decision.

## When the Complete System Produces the Bias

Now suppose qualified candidates with certain backgrounds appear more frequently in the lower-ranked group.

Because recruiters rarely move beyond the recommended candidates, those applicants receive less consideration.

The resulting disadvantage is produced through the interaction of:

**AI Ranking → Candidate Presentation → Recruiter Workload → Review Practice → Interview Opportunity**

The ranking influences visibility.

The interface determines what recruiters see first.

Workload affects how deeply they review the list.

Organizational expectations influence when they stop.

I define this as system-level bias: a recurring and unjustified disadvantage produced by the combined operation of data, AI, business rules, workflows, people and organizational conditions.

No single component necessarily explains the complete outcome.

The model may pass its fairness assessment and still operate within a process that produces an unjustified disparity.

## Follow the Complete Decision Pathway

The pathway looks like this:

**Systemic Conditions → Training Data → Model → AI Output → Business Rules and Workflow → Human Review → Decision → Outcome → Future Data**

Bias can enter at several points.

It can also be amplified, reduced or corrected as information moves through the process.

Then the outcome may become part of the organization’s future data.

Candidates who never receive interviews cannot become successful employees. Their absence from future performance data may appear to confirm that the organization’s previous hiring profile was appropriate.

The organization begins learning from a world partly created by its own earlier decisions.

This is why a one-time model assessment is not enough.

## Start With a Baseline

How can an organization determine whether the AI-enabled process changed anything?

It needs a baseline.

Before implementation, the organization should document how the existing process distributes attention, decisions and outcomes.

For hiring, that could include:

- Who enters the applicant pool.
- How applications are prioritized.
- How many applications recruiters review.
- When recruiters stop reviewing.
- Who receives interviews, offers and employment.
- Whether progression rates differ among relevant populations.
- How exceptions and overrides are handled.

The baseline tells us what happened before AI.

It does not tell us that the previous process was acceptable.

If the existing process already contains an unjustified disparity, reproducing the same result with AI would preserve the problem.

The organization therefore needs three points of comparison:

1. **Existing-process baseline:** What happens today?
2. **Intended outcome:** What should the new process achieve?
3. **Actual result:** What happened after implementation?

Suppose AI-assisted ranking reduces the time needed to build an interview slate.

At the same time, recruiters review fewer applications, rarely examine the lower-ranked group and overlook qualified candidates identified through independent sampling.

The organization improved efficiency.

But did it improve hiring?

And did it create or increase a disparity in who received meaningful consideration?

Those are different questions.

## Find Where the Difference Appeared

The organization should compare results at each significant stage:

**Applicant Pool → AI Ranking → Recruiter Review → Interview → Offer → Hire**

If a difference already exists in the applicant pool, recruiting channels or job requirements may be contributing to it.

If it first appears in the ranking, the training data or model may require attention.

If it grows during recruiter review, presentation order, workload, automation bias or review practices may be influencing the result.

If it appears during interviews or offers, the organization must examine those decisions and the criteria being applied.

Possible assessment methods include:

- Having qualified reviewers assess a sample of applications without seeing the AI ranking.
- Determining whether qualified candidates appear in lower-ranked groups.
- Measuring how often recruiters review candidates outside the recommended group.
- Testing whether decisions change when rankings are hidden.
- Comparing progression patterns across recruiters, positions and relevant populations.

A difference does not automatically prove harmful bias.

The organization still needs to determine whether it is recurring, consequential and justified by a legitimate job requirement.

A system-level assessment can also complement legally required reviews. For example, New York City’s Local Law 144 requires certain automated employment decision tools to undergo an independent bias audit. A broader system-level assessment would examine how the audited tool operates within the organization’s complete hiring process.

## Assessment Must Continue After Deployment

The system can change even when the model does not.

Recruiter capacity may decrease. Application volume may increase. The interface may change. Managers may create new expectations. Recruiters may begin relying more heavily on the ranking.

The organization should therefore reassess the system when there is a meaningful change to:

- Training data or data sources.
- The model, features, objective or thresholds.
- Business rules or workflow.
- The user interface.
- Application volume or recruiter capacity.
- Monitoring results, complaints or reported harms.

Retraining requires particular attention.

Once the model learns from post-deployment outcomes, its training data includes decisions produced by the AI-assisted process. The organization must examine the new training data, rather than conducting only another model-performance test.

## Match the Response to the Source

The correct response depends on where the difference appeared.

A difference that begins in the ranking may require changes to the data, model or prediction objective.

A difference that grows during recruiter review may require changes to candidate presentation, recruiter workload or review procedures.

A difference that cannot be measured may reveal a data or monitoring gap.

The solution will not always be another model adjustment.

It may require a change to a job requirement, recruiting channel, business rule, workflow, interface, human responsibility or organizational incentive.

This is also where accountability becomes difficult.

HR may own the hiring process and historical data. A model team or vendor may manage the model. IT may manage the integration. Recruiters and hiring managers influence the decisions.

Each group can show that its part worked as designed while the complete process produced an unjustified outcome.

Who owns that outcome?

## Assess the System, Not Only the Model

Training-data and model assessments remain essential.

But they answer only part of the question.

- **Systemic bias:** What organizational or institutional conditions shaped the decision environment?
- **Training-data bias:** What did the model learn from?
- **Model bias:** How did the model evaluate candidates?
- **Human-cognitive bias:** How did people respond to the AI output?
- **System-level bias:** How did all parts of the process work together?
- **Outcome assessment:** Who actually received consideration and opportunity?

This work begins during **Enterprise Discovery and Readiness—Phase 0** of my Enterprise AI Implementation Reference Model and continues for as long as the system operates.

The central question is broader than whether the data or model is biased:

> Where did bias enter the decision pathway, how did the system reduce or amplify it, and what outcome did the complete process produce?

AI bias does not begin or end with the model.

Neither should the assessment.

## Next in the Series

Finding a problem is not the same as governing it.

The final companion article, **An AI Bias Assessment Found a Problem. What Happens Next?**, will examine how an organization turns assessment findings into operating governance.

Who owns the corrective action?

What evidence demonstrates that the change worked?

What result triggers intervention?

Who can restrict or pause the system?

And who has the authority to accept the remaining risk?

That returns us to the question raised in Companion Article 1:

> Who owns the risk when it crosses a boundary?

---

Original publication: [Bias Does Not Begin or End With the Model](https://rwahai.substack.com/p/bias-does-not-begin-or-end-with-the) (rwahai.substack.com).

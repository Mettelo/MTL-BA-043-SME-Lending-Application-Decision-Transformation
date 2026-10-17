# Alderbridge SME finance — business context and sponsor initiation brief
**Mettelo Business Analyst Project Studio · MTL-BA-043 · aligned pathway edition · Stage 1**
Issued 6 July 2026 by Daniel Reed, Chief Operating Officer. All local people, organisations, policies, figures and case records are synthetic.

## Organisation and operating model
Alderbridge Business Finance Ltd is a fictional UK commercial lender with 67 staff, eight relationship managers, six underwriters and nine operations colleagues. Finance, Credit Risk, Compliance, IT and customer support provide control and shared services. Its directors describe an established business-lending book, but no audited balance-sheet dataset is supplied for this exercise.

This pilot concerns unsecured loans of £30,000–£150,000 to UK limited companies. Applicants include established trading businesses needing equipment, working capital or expansion funding. Applications may come from the website, an existing relationship manager or email. Directors and advisers can provide documents, but the business must establish identity, authority, purpose and relevant evidence under the applicable product/governance arrangements.

Sole traders, partnerships, consumer loans, mortgages, collections and a wider regulatory product expansion are outside the pilot. The legal/regulatory perimeter must be confirmed by Compliance; this source does not assert that all SME finance is regulated alike. The current FCA reference is contextual teaching material, not an internal policy or a sponsor document available before its publication.

## Current working environment
WebForm captures application fields. CaseVault holds documents. CreditSheet is an underwriting workbook. A bureau extract is delivered through an existing contract. A tracker records progress and Ledger records funding after an authorised decision. Relationship managers also use email and local notes.

“Complete” has several meanings: enough for a commercial discussion, all expected documents attached, or verified evidence suitable for underwriting. Customers may upload a document without the relevant period or the evidence may sit in an email rather than the case folder. A missing reference can therefore mean absent evidence, inaccessible evidence or unverified evidence; the source does not decide which dominates.

Operations identifies and links duplicate web/email submissions. A reconciled analysis ID does not demonstrate a universal live identity model. A relationship manager may tell a customer “approved in principle” before the final decision, creating expectations. Credit Risk wants policy/version, evidence and authority retained; Sales wants faster answers and less friction.

## Trigger for change
The 29 June operations review considered repeated document requests, an application left on a generic awaiting-credit status despite a company-data mismatch, and an audit review that could not retrieve every decision's rationale/version. Daniel proposed a digital decision workflow. Sales has advocated instant decisions below a value threshold; Underwriting and Credit Risk dispute the evidence and authority for that proposal.

No live automated approval is authorised. The BA is commissioned to understand the business need and recommend an appropriate intervention, not to build or validate a credit model. Different stakeholders offer plausible explanations: incomplete applications, repeated hand-offs, status ownership, document access, policy ambiguity, capacity or incentives. None is established as the sole root cause.

## Existing management cohort report
The frozen population groups first received month and observes outcomes through 30 June. Older cohorts have longer to complete. Requested amounts are not funded lending or recognised income.

| Received cohort | Applications | Requested GBP | Verified complete | Approved | Declined | Withdrawn | Pending | Document-request events | Contact events |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| April | 250 | 19,565,000 | 237 | 160 | 77 | 13 | 0 | 157 | 108 |
| May | 300 | 22,570,000 | 283 | 208 | 75 | 17 | 0 | 176 | 116 |
| June | 350 | 26,220,000 | 259 | 145 | 58 | 15 | 132 | 177 | 141 |

An approval is a decision, not proof of drawdown. A document request is an event, not a unique applicant or a confirmed error. Pending cases can be waiting for customer information, verification, underwriting or an authority decision. A blank rationale reference is absence of retained evidence in this extract, not proof that nobody reasoned about the decision.

Daniel has previously described complete-file turnaround as customer decision speed. Customer interviews challenge that wording. The BA must define useful start/end events, exclusions, cohorts, distributions and unresolved-work measures rather than produce one flattering completion average.

## Business and customer consequences
Customers face uncertainty about what is missing, who owns the next update and whether an indicative response is a final approval. Relationship managers spend time chasing documents and interpreting status. Underwriters repeat checks or search several sources. Operations may send reminders after withdrawal if the tracker is stale. Incomplete audit evidence complicates review and accountability even if the decision itself was reasonable.

Planning rates are £28/hour Operations, £45/hour relationship management, £60/hour underwriting and £75/hour specialist Risk/Compliance. These are loaded capacity values, not guaranteed cash avoidance. No reliable population of lost business, fraud loss, arrears, default, funding conversion or risk-adjusted profitability is supplied.

Doing nothing may preserve friction, inconsistent communications and weak evidence retrieval as applications grow. Uncontrolled automation could make unsuitable or unauditable decisions faster, create new data-use obligations or expand the product perimeter without approval. Any later funding decision would need to consider both, with uncertainty visible.


## Business need for this commission

An assisted SME lending application passes between Sales, Operations and Underwriting, but definitions of completeness, exception handling and decision authority are not consistently understood. Historic slides, policy versions and incomplete rationale records make it difficult to specify trustworthy system behaviour.

The business cannot responsibly ask a delivery team to automate an ambiguous policy. It needs a functional specification that explains what users and the system must do, which decisions remain human, and how reviewers can check rules, exceptions and policy applicability.

## Illustrative business situation to investigate

A relationship manager submits an application and supporting documents for a UK limited company. Operations checks receipt and verification; Underwriting may request evidence or raise a mismatch. A permitted decision-maker must act under the applicable authority and policy. Meanwhile an applicant may withdraw, a reminder may be queued or the requested amount may change. The BA must specify these interactions and unresolved cases; the source scenario is not a completed use-case specification.

This is a source scenario. Your team must analyse it; it is not an approved process, detailed use case or designed solution.

## Sponsor commission and authority

Daniel Reed, Chief Operating Officer commissions your team as functional business analysts. The decision is: **What functional behaviour, data, states and controlled rules should an assisted application-to-decision workflow support, and is that specification coherent enough for design estimation and business validation?**

The requested handover is: **A versioned FRD supported by detailed use cases, decision tables, data/state models and requirements-to-validation traceability.**

Sales wants an early response and fewer steps, Operations needs clear next actions, Underwriting distinguishes receipt from verified completeness, and Risk/Compliance require accountable authority, exceptions and audit. A vendor claim about automation is not an approved functional requirement.

The sponsor can request analysis but cannot substitute for Risk, Compliance, underwriting-policy, security and funding owners. Identify material approvals and unknowns without fabricating named reviewers or sign-off.

## Scope and exclusions

**Included:** Receipt, document requests, verification, completeness, application status, authorised decisions, communication, withdrawal, exceptions and audit for unsecured £30,000–£150,000 lending to UK limited companies. Analyse current and prospective policy applicability explicitly.

**Outside this assignment:** No automatic approval model, real credit decision, new bureau integration, sole-trader/partnership expansion, collections or pricing redesign. No full process-transformation business case, product backlog, software build or executed UAT programme is required.

## Constraints and evidence limitations

The initial £150,000 one-off envelope includes £15,000 committed, with a £30,000 annual incremental ceiling. Treat it as a constraint when identifying design dependencies and likely scope; this commission does not approve expenditure or demand a procurement recommendation.

The learning commission lasts 6 cohort weeks. Original dates in operational records remain source history; later operational ambitions do not extend the assessed scope. Staff availability is limited: plan proportionate elicitation using supplied interviews and record follow-up questions when real access is unavailable.

The dataset is constructed, observed at its stated cutoff and incomplete for some business questions. An absent event is not always proof an event did not happen. Do not claim representative research, causality, approved targets or realised outcomes merely from these records. Use [the data guide](../evidence/DATA_GUIDE.md) and [source provenance](../reference/OFFICIAL_REFERENCES_AND_SOURCE_PROVENANCE.md).

## How the evidence supports the work

| Evidence | Analytical purpose | Relevant tasks |
|---|---|---|
| Stakeholder accounts and functional transaction supplement | Find actors, triggers, main/alternative flows and unresolved behaviour. | F1–F3 |
| Policies and authority/version notices | Analyse authority boundaries, exceptions and effective-date decisions. | F2–F4 |
| Applications, document requests and decision audit | Understand entities, states, missing information and actual exception records. | F3–F5 |
| Technology context and data guide | Separate observed fields/capability from proposed functional behaviour. | F2–F5 |
| Automation and data-use challenges | Validate scope and constraints; revise specification and traceability without accepting claims as requirements. | F6–F7 |

## What leadership needs to receive

A reviewer can follow a material need from source evidence through a functional requirement, use case, rule/data/state behaviour and proposed validation scenario. Policy gaps remain explicit decisions for owners rather than invented approved rules.

| Task | Required handover content | Assessment weight |
|---|---|---|
| F1 | Functional boundary; actor inventory; elicitation issue log and external dependencies. | 10% |
| F2 | FRD with stable IDs, source references, functional/quality constraints, testable acceptance conditions and unresolved decisions. | 25% |
| F3 | Use-case diagram; at least five detailed specifications with triggers, preconditions, main/alternative/exception flows and postconditions. | 20% |
| F4 | Decision tables; policy/version applicability specification; exact authority boundaries and unresolved owner decisions. | 15% |
| F5 | Conceptual data model; data dictionary; application state model including invalid transitions and audit needs. | 15% |
| F6 | Requirements traceability matrix; boundary/exception scenarios with expected behaviour; review log distinguishing unexecuted from executed checks. | 10% |
| F7 | Versioned specification index; decision summary; change/review record; design-estimation dependencies and readiness recommendation. | 5% |

Use [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) for the four acceptance criteria per task and [the submission checklist](../submission/DELIVERABLES_CHECKLIST.md) for the exact handover package. These define the commission; historical stakeholder ambitions are inputs to evaluate, not extra mandatory portfolios.

No preferred solution or completed learner artefacts are provided.

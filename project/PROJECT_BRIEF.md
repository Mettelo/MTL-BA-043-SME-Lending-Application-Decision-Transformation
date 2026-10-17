# MTL-BA-043 — commissioned assignment

**Mettelo Business Analyst Project Studio · distinct pathway edition**

## Business problem and reason for commissioning the team

An assisted SME lending application passes between Sales, Operations and Underwriting, but definitions of completeness, exception handling and decision authority are not consistently understood. Historic slides, policy versions and incomplete rationale records make it difficult to specify trustworthy system behaviour.

The business cannot responsibly ask a delivery team to automate an ambiguous policy. It needs a functional specification that explains what users and the system must do, which decisions remain human, and how reviewers can check rules, exceptions and policy applicability.

Read the [organisation and sponsor context](../business_context/BUSINESS_CONTEXT_AND_SPONSOR_BRIEF.md) for the observed operating environment.

## Role and business decision
You are the Functional Business Analyst. What must an assisted application-to-decision workflow do, under which rules and authorities, and how will reviewers verify its behaviour?

A reviewable functional specification for an assisted lending workflow, ready for design estimation and business validation. No autonomous credit model or production credit decisions.

## Business situation and intended value

A relationship manager submits an application and supporting documents for a UK limited company. Operations checks receipt and verification; Underwriting may request evidence or raise a mismatch. A permitted decision-maker must act under the applicable authority and policy. Meanwhile an applicant may withdraw, a reminder may be queued or the requested amount may change. The BA must specify these interactions and unresolved cases; the source scenario is not a completed use-case specification.

A reviewer can follow a material need from source evidence through a functional requirement, use case, rule/data/state behaviour and proposed validation scenario. Policy gaps remain explicit decisions for owners rather than invented approved rules.

## Scope

Receipt, document requests, verification, completeness, application status, authorised decisions, communication, withdrawal, exceptions and audit for unsecured £30,000–£150,000 lending to UK limited companies. Analyse current and prospective policy applicability explicitly.

No automatic approval model, real credit decision, new bureau integration, sole-trader/partnership expansion, collections or pricing redesign. No full process-transformation business case, product backlog, software build or executed UAT programme is required.

## Required work
| ID | Task | Required output | Assessment weight |
|---|---|---|---|
| F1 | Define the functional boundary | Scope, actor inventory and elicitation issue log | 10% |
| F2 | Specify functional behaviour | Functional Requirements Document (FRD) | 25% |
| F3 | Model actor-system interactions | Use-case diagram and at least five detailed use-case specifications | 20% |
| F4 | Specify controlled decision rules | Decision tables and rule/version applicability specification | 15% |
| F5 | Specify data and state behaviour | Conceptual data model, data dictionary and application state model | 15% |
| F6 | Validate the specification | Requirements traceability matrix, boundary/exception scenarios and review log | 10% |
| F7 | Handover the functional baseline | Versioned functional specification and decision summary | 5% |

The [task specification](TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) defines evidence and pass conditions for every output. Equivalent document formats are acceptable; omissions of analytical content are not. This is a 6-week learning commission, not a requirement to deliver a live business implementation.

## Working agreement
Use supplied facts, conflicting stakeholder accounts and synthetic source records. Make calculations reproducible; distinguish evidence, interpretation, proposal and unresolved approval. Reference actual source paths and row/case IDs. Do not invent stakeholder sign-off, real research, executed tests or realised benefits. External references supply context, not automatic approval of your proposals.

## Commission precedence
This brief, task criteria, assessment, timeline and release manifest supersede earlier generic end-to-end assignment instructions. Source packs retain historical requests and evolving assumptions to analyse. They are not additional deliverable lists. Record material contradictions and decide how they affect this commission.

## Evidence-to-deliverable connection

| Evidence | What you use it to establish | Tasks |
|---|---|---|
| Stakeholder accounts and functional transaction supplement | Find actors, triggers, main/alternative flows and unresolved behaviour. | F1–F3 |
| Policies and authority/version notices | Analyse authority boundaries, exceptions and effective-date decisions. | F2–F4 |
| Applications, document requests and decision audit | Understand entities, states, missing information and actual exception records. | F3–F5 |
| Technology context and data guide | Separate observed fields/capability from proposed functional behaviour. | F2–F5 |
| Automation and data-use challenges | Validate scope and constraints; revise specification and traceability without accepting claims as requirements. | F6–F7 |

## Submission
Submit the indexed outputs above in your own delivery repository using [Mettelo's submission model](../submission/SUBMISSION_GUIDELINES.md).


The [team deliverables checklist](../submission/DELIVERABLES_CHECKLIST.md) specifies the required handover content, suggested package paths and completion checks.

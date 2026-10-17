# Mettelo Business Analyst Project Studio — MTL-BA-043

## SME lending: functional requirements and decision rules

**Role:** Functional Business Analyst · **Duration:** 6 cohort weeks · **Organisation:** Alderbridge Business Finance

This repository is the source library for a simulated business assignment. Your team acts as the BA team commissioned by Daniel Reed, Chief Operating Officer. You investigate supplied evidence and create your own analysis in a separate delivery repository. All local organisations, people and operational records are fictional; clearly labelled official reference material remains external context.

## The business situation

Alderbridge Business Finance has commissioned this simulation. An assisted SME lending application passes between Sales, Operations and Underwriting, but definitions of completeness, exception handling and decision authority are not consistently understood. Historic slides, policy versions and incomplete rationale records make it difficult to specify trustworthy system behaviour.

### Example business situation

A relationship manager submits an application and supporting documents for a UK limited company. Operations checks receipt and verification; Underwriting may request evidence or raise a mismatch. A permitted decision-maker must act under the applicable authority and policy. Meanwhile an applicant may withdraw, a reminder may be queued or the requested amount may change. The BA must specify these interactions and unresolved cases; the source scenario is not a completed use-case specification.

### Why this work is needed

The business cannot responsibly ask a delivery team to automate an ambiguous policy. It needs a functional specification that explains what users and the system must do, which decisions remain human, and how reviewers can check rules, exceptions and policy applicability.

### Perspectives you must reconcile

Sales wants an early response and fewer steps, Operations needs clear next actions, Underwriting distinguishes receipt from verified completeness, and Risk/Compliance require accountable authority, exceptions and audit. A vendor claim about automation is not an approved functional requirement.

## Your commission and the decision it supports

**Business question:** What functional behaviour, data, states and controlled rules should an assisted application-to-decision workflow support, and is that specification coherent enough for design estimation and business validation?

**Your endpoint:** A versioned FRD supported by detailed use cases, decision tables, data/state models and requirements-to-validation traceability.

**What good work enables:** A reviewer can follow a material need from source evidence through a functional requirement, use case, rule/data/state behaviour and proposed validation scenario. Policy gaps remain explicit decisions for owners rather than invented approved rules.

**Skills you will practise:** FRD authoring, actor/system use cases, functional decomposition, decision tables, data and state modelling, boundary analysis and traceability.

## What your team will actually do

1. **F1 — Define the functional boundary.** Produce scope, actor inventory and elicitation issue log. Use it to inform the next task and keep unresolved decisions visible.
2. **F2 — Specify functional behaviour.** Produce functional Requirements Document (FRD). Use it to inform the next task and keep unresolved decisions visible.
3. **F3 — Model actor-system interactions.** Produce use-case diagram and at least five detailed use-case specifications. Use it to inform the next task and keep unresolved decisions visible.
4. **F4 — Specify controlled decision rules.** Produce decision tables and rule/version applicability specification. Use it to inform the next task and keep unresolved decisions visible.
5. **F5 — Specify data and state behaviour.** Produce conceptual data model, data dictionary and application state model. Use it to inform the next task and keep unresolved decisions visible.
6. **F6 — Validate the specification.** Produce requirements traceability matrix, boundary/exception scenarios and review log. Use it to inform the next task and keep unresolved decisions visible.
7. **F7 — Handover the functional baseline.** Produce versioned functional specification and decision summary. Use it to inform the next task and keep unresolved decisions visible.

Each task has four explicit assignment acceptance criteria in [TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md](project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md). They explain how the output is assessed. Where you must write solution acceptance criteria, those are your own proposed business/system/product behaviours, not supplied answers.

## Exactly what you submit

| Task | Required team handover content | Weight |
|---|---|---|
| F1 | Functional boundary; actor inventory; elicitation issue log and external dependencies. | 10% |
| F2 | FRD with stable IDs, source references, functional/quality constraints, testable acceptance conditions and unresolved decisions. | 25% |
| F3 | Use-case diagram; at least five detailed specifications with triggers, preconditions, main/alternative/exception flows and postconditions. | 20% |
| F4 | Decision tables; policy/version applicability specification; exact authority boundaries and unresolved owner decisions. | 15% |
| F5 | Conceptual data model; data dictionary; application state model including invalid transitions and audit needs. | 15% |
| F6 | Requirements traceability matrix; boundary/exception scenarios with expected behaviour; review log distinguishing unexecuted from executed checks. | 10% |
| F7 | Versioned specification index; decision summary; change/review record; design-estimation dependencies and readiness recommendation. | 5% |

Use [the project-specific submission checklist](submission/DELIVERABLES_CHECKLIST.md) for package names, minimum content and final checks. You may combine related content if the final index links each task to the relevant section. A heading with no analysis is not a completed deliverable.

## Start here

1. Read [the business context and sponsor brief](business_context/BUSINESS_CONTEXT_AND_SPONSOR_BRIEF.md) to understand the organisation, observed problem and decision owners.
2. Read [the project brief](project/PROJECT_BRIEF.md) and [task acceptance criteria](project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) to understand the assignment boundary.
3. Follow [the delivery guide](project/DELIVERY_GUIDE.md), [timeline](project/PROJECT_TIMELINE.md) and [release manifest](project/RELEASE_MANIFEST.csv). In a controlled cohort, use only released evidence.
4. Create your separate team repository using [submission guidelines](submission/SUBMISSION_GUIDELINES.md). Confirm reviewer access before substantial work.
5. Build and review the required outputs; submit the tagged repository URL through Mettelo's cohort route.

## What the evidence is for

Open [the source catalogue](evidence/README.md) for direct links and release labels for each evidence file.

| Source group | Why you need it | Main tasks |
|---|---|---|
| Stakeholder accounts and functional transaction supplement | Find actors, triggers, main/alternative flows and unresolved behaviour. | F1–F3 |
| Policies and authority/version notices | Analyse authority boundaries, exceptions and effective-date decisions. | F2–F4 |
| Applications, document requests and decision audit | Understand entities, states, missing information and actual exception records. | F3–F5 |
| Technology context and data guide | Separate observed fields/capability from proposed functional behaviour. | F2–F5 |
| Automation and data-use challenges | Validate scope and constraints; revise specification and traceability without accepting claims as requirements. | F6–F7 |

The source packs deliberately contain disagreement, missing information and unapproved proposals. A stakeholder request is evidence of a need or preference, not automatically an agreed requirement. Preserve raw data, identify source rows/case IDs and distinguish facts, interpretation, assumptions and proposals. The task pack does not contain completed BA answers.

## Scope and practical boundaries

**Included:** Receipt, document requests, verification, completeness, application status, authorised decisions, communication, withdrawal, exceptions and audit for unsecured £30,000–£150,000 lending to UK limited companies. Analyse current and prospective policy applicability explicitly.

**Outside this assignment:** No automatic approval model, real credit decision, new bureau integration, sole-trader/partnership expansion, collections or pricing redesign. No full process-transformation business case, product backlog, software build or executed UAT programme is required.

**Planning constraints:** The initial £150,000 one-off envelope includes £15,000 committed, with a £30,000 annual incremental ceiling. Treat it as a constraint when identifying design dependencies and likely scope; this commission does not approve expenditure or demand a procurement recommendation.

6 weeks describes your learning commission; any dated operational pilot in source testimony is a business ambition, not an instruction to deploy. Later pilot/experiment files are optional background. Do not claim you conducted the supplied interviews, executed tests or achieved live benefits. No paid tool is required; use readable documents, spreadsheets and diagram/prototype tools you can access.

## Why there are change scenarios

The notices introduce new facts, contested proposals or constraints that test your judgement. Apply them to this project's outputs and keep a revision trail. They do not make every project a change-management assignment and do not require a separate generic three-change report.

## Repository navigation

- **business_context:** organisation, problem, sponsor commission and decision boundaries.
- **stakeholders:** supplied testimony and conflicting perspectives.
- **evidence:** synthetic records, forms and the pathway-specific supplement.
- **policies / systems:** existing rules, capability claims and constraints.
- **reference:** external context and source provenance; observe retrieval limitations.
- **change_scenarios:** staged challenge evidence.
- **project:** tasks, acceptance criteria, assessment, releases and timeline.
- **submission:** instructions and the exact team handover checklist; no team answers.

Public GitHub exposes all stages. A facilitator must distribute releases separately if staged access matters. Never commit participant answers to this master; maintain your work, contribution history and final submission in your team's repository.

# MTL-BA-043 — required team deliverables

**Pathway:** Functional Business Analyst

**Business decision:** What functional behaviour, data, states and controlled rules should an assisted application-to-decision workflow support, and is that specification coherent enough for design estimation and business validation?

**Final audience:** Operations, underwriting, Risk, Compliance and the solution design/estimation team.

The team submits its own analysis listed below. These are assignment instructions, not completed answers or a template containing a solution. Every required item must be easy for a reviewer to locate in the tagged version.

## Required analytical packages

### F1 — Define the functional boundary

**Suggested location:** `analysis/01-scope-actors/`. Equivalent files/sections are acceptable.

**Required content:** Functional boundary; actor inventory; elicitation issue log and external dependencies.

**Why the business needs it:** Prevent functional scope and actor authority from drifting before detailed specification.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F1-AC1 to F1-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F2 — Specify functional behaviour

**Suggested location:** `analysis/02-frd/`. Equivalent files/sections are acceptable.

**Required content:** FRD with stable IDs, source references, functional/quality constraints, testable acceptance conditions and unresolved decisions.

**Why the business needs it:** Give business and design reviewers a precise account of required behaviour and unresolved decisions.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F2-AC1 to F2-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F3 — Model actor-system interactions

**Suggested location:** `analysis/03-use-cases/`. Equivalent files/sections are acceptable.

**Required content:** Use-case diagram; at least five detailed specifications with triggers, preconditions, main/alternative/exception flows and postconditions.

**Why the business needs it:** Explain how actors and the system interact, including exceptions that a simple feature list would miss.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F3-AC1 to F3-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F4 — Specify controlled decision rules

**Suggested location:** `analysis/04-rules/`. Equivalent files/sections are acceptable.

**Required content:** Decision tables; policy/version applicability specification; exact authority boundaries and unresolved owner decisions.

**Why the business needs it:** Expose policy boundaries and effective-date ambiguity before they become coded behaviour.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F4-AC1 to F4-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F5 — Specify data and state behaviour

**Suggested location:** `analysis/05-data-states/`. Equivalent files/sections are acceptable.

**Required content:** Conceptual data model; data dictionary; application state model including invalid transitions and audit needs.

**Why the business needs it:** Keep the information and state changes supporting the workflow internally consistent.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F5-AC1 to F5-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F6 — Validate the specification

**Suggested location:** `analysis/06-validation/`. Equivalent files/sections are acceptable.

**Required content:** Requirements traceability matrix; boundary/exception scenarios with expected behaviour; review log distinguishing unexecuted from executed checks.

**Why the business needs it:** Show how reviewers can check each material behaviour against its sources and edge conditions.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F6-AC1 to F6-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### F7 — Handover the functional baseline

**Suggested location:** `analysis/07-functional-handover/`. Equivalent files/sections are acceptable.

**Required content:** Versioned specification index; decision summary; change/review record; design-estimation dependencies and readiness recommendation.

**Why the business needs it:** Let design and estimation teams identify the usable baseline and remaining approval dependencies.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every F7-AC1 to F7-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

## Repository and submission records required from every team

- [ ] A separate repository named `MTL-BA-043-<team-name>`, following the cohort's ownership/access route.
- [ ] A README explaining this simulated commission, the business decision, navigation and how to reproduce calculations or open visual artefacts.
- [ ] CONTRIBUTIONS.md identifying each contributor, substantive work/review references and declared assistance.
- [ ] Preserved raw evidence and calculation/transformation notes for material numerical claims; external reference/provenance links where used.
- [ ] Meaningful issues, branches, commits and material PR/review history inside the team repository; solo work may use clearly labelled self-review.
- [ ] `submission/FINAL_SUBMISSION.md` containing team/lead details, repository URL, final branch, exact final commit/tag, a row for each task ID linking its outputs, unresolved decisions, limitations, reproduction/opening instructions, contribution links and reviewer-access confirmation.
- [ ] A tag or release named `v1.0-mettelo-submission` that resolves to the reviewed final version.
- [ ] Verified Mettelo reviewer access to files, history, issues and pull requests for that version.
- [ ] The repository URL, tag and final index submitted through the route supplied for the cohort; do not email project files or invent a submission portal.

## Accepted formats and completion standard

Use readable Markdown/PDF/documents, spreadsheets/CSV with clear calculations and diagram/prototype formats reviewers can open. Include a readable export if the authoring tool or sharing permission might block access. A working application is not required. Keep editable/source material where needed to check calculations and analysis.

Several outputs may share a document or workbook; link the specific sections from each task row. Do not omit one because its content overlaps another. Do not fill the portfolio with unrelated BA deliverables to compensate for missing required work.

No automatic approval model, real credit decision, new bureau integration, sole-trader/partnership expansion, collections or pricing redesign. No full process-transformation business case, product backlog, software build or executed UAT programme is required.

Do not submit supplied interviews or source packs as your own research, simulated observations as tests you ran, or proposed approval as signed agreement. Record what remains unknown. The [weighted assessment](../project/ASSESSMENT_CRITERIA.md) applies to the tasks above.

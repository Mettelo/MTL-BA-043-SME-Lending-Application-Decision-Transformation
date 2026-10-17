# Lending operations and audit evidence
**Mettelo BA-043 · Stage 3 · Collated 20 July**
Source fragments support investigation; they do not provide a completed AS-IS model, root-cause report or requirements.

## BE01 — intake observation
At 09:15 an Operations colleague finds an application in a web queue and a related relationship-manager email. A document exists in email but not CaseVault. At 09:40 another colleague sends a request using a generic missing-documents macro. At 10:05 Underwriting queries which accounts period was verified. No complete version receipt is visible during the session.

The observer watched one experienced colleague, not a representative shift. A repeated request may reflect missing, stale, inaccessible or unverified information. Staff offer different explanations; the observation does not establish prevalence or one root cause.

## BE02 — linked case fragments
A0551: £60,000 request, received 1 June; verified complete 12 June; approved 17 June by senior underwriter under recorded v4. The customer account describes the earlier document interval; it is excluded from a complete-file clock. Original uploads are not supplied.

A0552: £90,000 request, received 1 June; complete 8 June; approved 15 June by Credit Manager. Operations describes duplicate intake conversations, but the reconciled data contains one application. No full duplicate population is supplied.

A0553: £40,000, company/bureau mismatch flag, exception yes, no verified-complete or decision event at cutoff. The underlying bureau record is unavailable. Do not infer creditworthiness or decide identity from the flag alone.

A0555: £75,000 standard/no-exception, complete 4 June, approved 8 June by senior underwriter. This source boundary case is not an approval to encode an automatic rule. A0556 withdrew on 10 June; the later reminder discussion concerns communication control, not a funding result.

## BE03 — audit associate's review
On 26 June the associate reviewed 32 available decision folders, selected for document availability. Six lacked a readily retrievable rationale reference, five lacked a retained policy-version reference and four held approver evidence in email only. Categories overlap. The reviewed case list is not retained in the exercise, so these counts cannot become a representative error rate or be joined reliably to the full source population.

The associate did not evaluate loan performance, model fairness, regulatory compliance for every case or whether missing evidence existed elsewhere. Farah requests retrieval and authority review; Peter notes documents can be dispersed. No control certification was issued.

## BE04 — synthetic correspondence
Applicant: “I need to know whether you have the correct period or whether another person cannot find it.”
Underwriter: “The attachment tick is not a verification decision.”
Relationship manager: “Approved in principle needs agreed customer wording.”
Operations: “Please tell us when a withdrawal should stop the next reminder.”

These are separate source accounts, not extra contact rows or approved future requirements. Their frequency is unknown.

## BE05 — cost and capacity
Planning values: Operations £28/hour, relationship management £45/hour, underwriting £60/hour, specialist Risk/Compliance £75/hour. No full touch-time population, overtime contract or cash-release mechanism is supplied. Time potentially released may remain necessary capacity.

Supplier setup, recurring licences, bureau/verification charges, data work, policy/governance review, training and support must be considered. The initial £150,000 includes £15,000 committed. Requested principal is not a savings or revenue estimate. No risk-adjusted return model is supplied.

## BE06 — evidence gaps
The source lacks real bureau outputs, complete original documents, a full rationale archive, all duplicate-intake events, live funding results, default/arrears performance, validated customer research and model validation. Record the fact needed for a decision and what follows if unavailable.

Preserve the source and cite IDs. The participant must reconstruct processes, distinguish symptoms/causes, propose rules/requirements and evaluate options. Do not treat a cleanly reconciled teaching extract as evidence that production systems already integrate correctly.

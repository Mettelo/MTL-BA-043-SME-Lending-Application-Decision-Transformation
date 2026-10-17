# Lending evidence — data dictionary and extraction basis
**Mettelo BA-043 · Stage 3 · Frozen 30 June 2026, 18:00 UK**
All companies, application IDs, classifications and outcomes are synthetic. No real bureau, borrower or bank data is supplied.

## Population and units
operational_data.csv contains 900 applications received in April (250), May (300) and June (350), within the stated limited-company product. document_request_events.csv has 510 request events; decision_audit_records.csv 723 retained decision rows; applicant_contact_events.csv 365 contacts. These are different units, not additive case counts.

The board table groups by received month and observes through one cutoff. Older cohorts have longer to progress. A pending record with no decision date is not zero days or a confirmed failure. Requested GBP is principal requested, not approval amount, drawdown, income or credit risk performance.

## Application fields
application_id is unique and company_id is invented. received_date is first included intake, channel records an intake route and requested_gbp is £30,000–£150,000. risk_record is an existing classification, not independently validated creditworthiness. policy_exception is an existing yes/no flag; its legal or risk sufficiency is not established.

verified_complete_date is the recorded verified-file event. decision_date records approved/declined outcome; withdrawn_date records a separate withdrawal, not a decision. outcome is approved/declined/withdrawn/pending. recorded_approver is a role, not a full identity/audit record. policy_version_recorded can be blank; v3/v4 describe the recorded source version, not a guarantee of correct application. bureau_mismatch is a flag, not a real bureau result.

Historical v3 and current v4 share the documented value delegation for this training population; the uncontrolled March slide conflicts with them. Later policy changes are prospective source events and must not silently rewrite June facts.

## Document requests, decisions and contacts
request_id uniquely identifies a document-request event. Repeated requests can concern the same application/document. reason distinguishes some existing labels but does not establish responsibility. received_date is the recorded resolution/receipt event when available; blank means unobserved. It is not proof the uploaded content was suitable.

decision_record_id is unique and application_id joins to the application. rationale_reference can be absent in the extract without proving no reasoning occurred. policy_version and approval_evidence describe retained provenance. Email-only/workbook evidence requires investigation, not an automatic declaration that a decision was invalid.

contact_id is unique. Theme, handling minutes and complaint flag are source observations, not representative customer research or a validated regulatory classification. No customer-level identifier supports unique-person metrics.

## Measurement and financial limitations
Dates have calendar-day precision, not same-day order or a holiday calendar. Do not compare a working-day target with an undeclared calendar-day calculation. Use the same population/clock and keep incomplete and withdrawn work visible where relevant.

No funded-loan, default, arrears, fraud-loss or profitability population is provided. A completion average cannot establish credit quality or a model's validity. Loaded capacity rates are not guaranteed cash savings. Preserve raw evidence and explain joins, cutoffs, exclusions, assumptions and uncertainty.

## Stage 6 observations
pilot_observations.csv contains 80 rows from 40 historical cases A0551–A0590, baseline replay on 17 August and workflow trial on 19 August. paired_case_id links modes. task_seconds measures operator activity, not application elapsed time or customer outcome. Visibility/retention/review flags are observer findings, not approval. operator_assisted affects independence.

These are not 80 new applicants or independent users. The supplier experiment is isolated and cannot prove live automation benefit. Read the compiled delivery pack at the 24 August release and judge it against your own requirements and acceptance approach.

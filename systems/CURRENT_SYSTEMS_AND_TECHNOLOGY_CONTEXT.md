# Lending systems and commercial source context
**Mettelo BA-043 · Stage 3 · IT note, 20 July**

## Current products and events
WebForm captures fields; CaseVault stores documents; CreditSheet holds underwriting work; the existing bureau batch is read-only; the status tracker is maintained separately; Ledger records funding after authorised handover. Email documents do not automatically enter CaseVault.

Application, company, document-version and bureau references mean different things. A recorded upload is not verification. Operations' reconciled training ID is not proof of universal live identity or duplicate prevention. A changed document can affect verification and decision evidence even if a status field remains complete.

## Existing capability hypothesis
IT believes existing queues, document receipts and version references might be improved. Indicative effort: 15 analyst days at £450/day, 10 integration days at £650/day; £8,000–£12,000 annual support. No resource booking, full audit coverage, failure recovery or security approval is committed. Current tools are not free to implement.

The bureau contract does not automatically allow a new data purpose or real-time access. A failed file needs operational reconciliation, not merely a successful retry email. No complete missed-file/replay test or data-migration scope is supplied.

## Supplier commercial inputs
DecisionFlow: £90,000 setup plus £25,000/year, two-year minimum. Excludes bureau/verification charges, independent model validation, data cleansing, governance review, training/backfill, VAT and some interfaces. Claims 70% automated decisions from twenty fabricated standard cases, with no representative exception or loan-performance study.

CaseRoute: £55,000 workflow setup plus £18,000/year, two-year term. Claims document/status management and human decision tasks, not an approved credit model. Indicative Ledger handover connector £16,000 excluded. Audit export and document-version handling not demonstrated.

No weighted scores, total-cost conclusion or preferred option is supplied. Process/document ownership changes, current-tool configuration and sequencing remain alternatives for the participant to assess.

## Access, audit and deployment questions
IT asks for business meaning and consequences of stale data, document replacement after completion, multiple intake sources and a withdrawn case. Access to commercially sensitive information and authority to decide are distinct. A human approval click needs evidence and context to be meaningful.

The August experiment uses fabricated historical replay data, not production bureau or funding access. No live approval, credit model or source-data transfer is authorised. Supplier defaults cannot settle a policy or regulatory question.

## Information not established
Final licence coverage, interface scope/capacity, recovery criteria, complete audit/retention, support ownership, peak demand and committed implementation resource remain unknown. The BA must turn business needs into validated testable requirements with appropriate technical/control collaboration. This pack supplies raw claims and constraints, not a future architecture or completed integration requirements.

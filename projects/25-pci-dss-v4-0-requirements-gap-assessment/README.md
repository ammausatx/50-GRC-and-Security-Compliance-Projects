# Project 25: PCI DSS v4 0 Requirements Gap Assessment

**Level:** Intermediate | **Track:** GRC & Security Compliance

## Objective
Conduct a structured pci dss v4 0 requirements gap assessment exercise. Convert applicable obligations into assigned controls, testable evidence, risk decisions, and a management-ready improvement plan.

## Scope and authorization
Use a fictional organization and synthetic information. Define entity, service, data, systems, suppliers, locations, scope boundaries, exclusions, and assessment period. Never include actual sensitive records in this public repository. This is a training exercise, not legal advice, certification, or an audit opinion.

## Prerequisites
- Current official framework/regulatory publication and applicable guidance
- Scope and asset/service inventory with accountable owners
- Spreadsheet or GRC platform, document repository, and diagramming tool
- Synthetic policy, process, configuration, and ticket examples

## Lab setup
1. Create project folders for scope, requirements, controls, tests, evidence, findings, actions, and reporting.
2. Record source publication, version, effective date, assessment date, and scope.
3. Build linked registers using unique IDs and controlled status values.
4. Define risk scoring, sample selection, evidence quality, reviewer, and approval rules.
5. Prepare a synthetic baseline to test the workflow end to end.

## Walkthrough
### 1. Establish the assessment boundary
Describe the business objective, in-scope services, systems, data flows, locations, third parties, interfaces, and exclusions. Obtain written approval and record assumptions.

### 2. Interpret authoritative requirements
Break relevant requirements into testable criteria. Capture exact reference, plain-language interpretation, applicability rationale, accountable owner, expected outcome, and evidence source. Verify requirements against official publications rather than relying on secondary summaries.

### 3. Map requirements to controls
For each criterion identify control objective, process, performer, reviewer, frequency, system dependency, and escalation path. Note shared controls, inherited controls, compensating measures, and gaps in coverage.

### 4. Test design and operation
Inspect synthetic artifacts and interview fictional owners. Select samples from a defined population using a documented risk-based rationale. Record sample IDs, period, procedure, result, exceptions, and evidence references. Separate design adequacy from operating effectiveness.

### 5. Assess exceptions and impact
Classify results as effective, partially effective, ineffective, not implemented, not applicable with rationale, or unable to verify. Document the factual condition, expected requirement, root cause, impact, likelihood, and limitations.

### 6. Prioritize corrective work
Rate risks consistently. For each confirmed gap create an action with owner, priority, milestones, target date, dependencies, interim safeguards, closure evidence, and retest method. Record accepted risks separately with authorized approver and expiry.

### 7. Produce a readiness report
Summarize scope, methodology, coverage, test results, high-risk gaps, evidence limitations, management decisions, and remediation roadmap. Avoid claims of certification or compliance beyond the evidence actually assessed.

## Example control test record
| ID | Criterion | Test procedure | Evidence | Result |
|---|---|---|---|---|
| CTRL-001 | Requirement has assigned owner | Inspect ownership record | EVD-001 | Pending |
| CTRL-002 | Control is implemented | Inspect synthetic artifact | EVD-002 | Pending |
| CTRL-003 | Control operates consistently | Sample dated records | EVD-003 | Pending |

## Tools and checks
Use a requirements-control crosswalk, sample tracker, evidence index, risk register, and corrective-action log. Add spreadsheet checks for duplicate IDs, missing owners, unreferenced conclusions, stale evidence, expired exceptions, and overdue actions. Preserve source licensing and do not reproduce restricted standard text.

## Expected output
A complete scoped assessment with requirement mapping, control narratives, test workpapers, evidence references, findings, risk ratings, treatment decisions, and management report.

## Findings and risk assessment
Assess coverage, design, operating consistency, sample limitations, dependencies, business impact, and compensating safeguards. State uncertainty explicitly. A mapped control or a policy document alone does not prove the requirement is met.

## Framework mapping
Use the exact edition and references of the primary subject. Consider relevant intersections with ISO/IEC 27001:2022, NIST CSF 2.0, NIST SP 800-53 Rev. 5, CIS Controls v8, and SOC 2 Trust Services Criteria where appropriate. Explain mapping rationale and avoid assuming equivalence between frameworks.

## Remediation
Document root cause, corrective action, owner, severity, milestones, target date, interim safeguards, dependencies, and objective closure evidence. Require independent retesting for material findings and escalation of overdue high-risk actions.

## Validation criteria
- Scope and applicability are approved
- Official requirements and versions are recorded
- Requirements map to owners, controls, tests, and evidence
- Sampling is reproducible and results are dated
- Gaps have risk ratings and approved treatment
- Exceptions have compensating controls and expiry
- Closure evidence is independently validated

## Evidence and reporting checklist
- [ ] Approved charter and boundary
- [ ] Official criteria and applicability register
- [ ] Control mapping and ownership
- [ ] Test procedures and sample population
- [ ] Evidence index and dated workpapers
- [ ] Findings, impact, risk, and limitations
- [ ] Remediation and exception approvals
- [ ] Management report and next review date

## Training illustrations
Simulated training illustrations only; not real audit evidence or certification artifacts.

![Project 25 scope and governance](images/01-baseline.svg)
![Project 25 assessment and findings](images/02-findings.svg)
![Project 25 remediation and validation](images/03-validation.svg)

## Deliverables
1. Scope and applicability statement
2. Requirements-to-controls matrix
3. Design and operating test workpapers
4. Evidence, risk, and remediation registers
5. Executive readiness report

## Completion criteria
An independent reviewer can reproduce the results from source requirements, approved scope, documented samples, evidence references, and management decisions.

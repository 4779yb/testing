Criteria for Determining "Production Readiness Review" Requirement
General Principle
PRR is required for all major changes related to control onboarding/control releases with reference to control design, workflow, and code changes, except for minor change releases due to bug fixes or incident responses for any control.

Specific Criteria
Nature of the Change

Major Changes: PRR is mandatory for major changes involving:

Control Design: Any redesign or significant modification of control mechanisms.
Workflow: Alterations in the workflow that impact how controls are executed or monitored.
Code Changes: Significant code changes that affect control logic, integrations, or overall functionality.
Minor Changes: PRR is not required for:

Bug Fixes: Minor changes solely aimed at fixing bugs without altering the overall control design or workflow.
Incident Responses: Immediate changes made in response to incidents to restore functionality or address specific issues.
Control Onboarding

New Controls: Introducing new controls into the system requires a PRR to ensure they are properly integrated, monitored, and do not negatively impact existing systems.
Performance and Scalability

Load Testing: Any changes requiring new load testing or significant adjustments to existing load testing protocols.
Capacity Planning: Adjustments in capacity planning that might be necessary due to increased usage or new control mechanisms.
Security Considerations

Data Sensitivity: Changes involving controls that handle sensitive data.
Compliance: Ensuring compliance with regulatory requirements necessitates PRR for changes affecting control compliance mechanisms.
Operational Readiness

Monitoring and Alerting: Changes that require updates or new configurations for monitoring and alerting systems.
Incident Response: Major updates to incident response procedures or tools.
Testing and Quality Assurance

Automated Testing: Introduction of new automated tests or significant updates to existing tests.
Manual Testing: Changes that require extensive manual testing, including user acceptance testing (UAT).
Deployment and Rollback

Deployment Strategy: Significant changes in deployment strategy or tools.
Rollback Plan: Updates to rollback plans that affect how major incidents will be managed.
Dependencies and Integration

External Dependencies: New or significantly altered external dependencies.
Integration Points: Changes affecting major integration points with other systems or services.
Process for Determining PRR Requirement
Initial Assessment:

Conduct an initial assessment to categorize the nature of the change (major vs. minor).
Self-Assessment Checklist:

Provide a checklist to the development team to self-assess their changes against the criteria mentioned above.
Review Meeting:

Hold a review meeting with key stakeholders to discuss the assessment and confirm whether a PRR is necessary.
Decision Making:

Document the decision and rationale. If PRR is required, proceed to schedule and plan the review.
Plan PRR:

Schedule the PRR at least 2-3 weeks before the go-live date.
Define the agenda and participants for the PRR to ensure a comprehensive evaluation.
Example Self-Assessment Checklist
Nature of the Change:

Is this a major change involving control design, workflow, or code changes?
Is this change a minor bug fix or an incident response?
Control Onboarding:

Are new controls being introduced?
Performance and Scalability:

Does this change require new load testing or capacity planning adjustments?
Security Considerations:

Does this change involve handling sensitive data?
Is compliance affected by this change?
Operational Readiness:

Are updates required for monitoring and alerting systems?
Are incident response procedures being updated?
Testing and Quality Assurance:

Are new automated tests or significant updates to existing tests required?
Does this change require extensive manual testing, including UAT?
Deployment and Rollback:

Are there significant changes in the deployment strategy?
Are updates to rollback plans necessary?
Dependencies and Integration:

Are there new or significantly altered external dependencies?
Are major integration points affected?
By following these updated criteria and processes, the SRE team can ensure that all major changes are thoroughly reviewed for production readiness, maintaining system stability and reliability while minimizing risks.

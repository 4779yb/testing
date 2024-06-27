Criteria for Determining "Production Readiness Review" Requirement
Criticality of the Application/Service

Business Impact: Determine if the application/service has a high impact on business operations or revenue.
User Base: Assess if a large number of users will be affected by the deployment.
Service Level Agreements (SLAs): Check if the application has strict SLAs that require high availability and reliability.
Architectural Changes

Major Changes: Identify if there are significant changes to the architecture, such as new microservices, changes to data storage, or integration with new third-party systems.
New Technologies: Determine if the deployment introduces new technologies or frameworks that the team has not previously used.
Performance and Scalability

Load Testing: Ensure that load testing has been performed and meets performance criteria.
Capacity Planning: Verify that capacity planning has been done to handle expected user load.
Security Considerations

Data Sensitivity: Check if the application handles sensitive data that requires strict security controls.
Compliance: Ensure that the application complies with relevant regulatory and compliance requirements.
Operational Readiness

Monitoring and Alerting: Confirm that monitoring and alerting mechanisms are in place and configured correctly.
Incident Response: Ensure that incident response plans are defined and tested.
Documentation: Verify that operational documentation, including runbooks and troubleshooting guides, is complete and up-to-date.
Testing and Quality Assurance

Automated Testing: Ensure that automated tests (unit, integration, end-to-end) have been created and passed.
Manual Testing: Verify that necessary manual testing has been conducted, including user acceptance testing (UAT).
Deployment and Rollback

Deployment Strategy: Determine if a well-defined deployment strategy (e.g., blue-green deployment, canary releases) is in place.
Rollback Plan: Ensure that there is a clear rollback plan in case of deployment issues.
Dependencies and Integration

External Dependencies: Identify if the application has critical external dependencies that need to be verified.
Integration Points: Check if all integration points with other systems or services have been tested and validated.
Process for Determining PRR Requirement
Initial Assessment:

Conduct an initial assessment using the criteria above to determine if a PRR is likely required.
Self-Assessment Checklist:

Provide the development team with a self-assessment checklist based on the criteria. This checklist helps the team to self-evaluate their readiness for PRR.
Review Meeting:

Schedule a review meeting with key stakeholders, including representatives from development, QA, security, and SRE teams, to discuss the results of the self-assessment.
Decision Making:

Based on the assessment and discussion, make a decision on whether a PRR is required. Document the decision and the rationale behind it.
Plan PRR:

If a PRR is required, schedule it well in advance of the go-live date (ideally 2-3 weeks prior). Define the agenda and participants for the PRR.
Example Self-Assessment Checklist
Business Impact and Criticality:

Does the application/service have a significant impact on business operations?
Is the user base large or growing rapidly?
Architectural Changes:

Are there major architectural changes involved?
Are new technologies or frameworks being introduced?
Performance and Scalability:

Have load tests been conducted and passed?
Is capacity planning complete and validated?
Security Considerations:

Does the application handle sensitive data?
Is the application compliant with regulatory requirements?
Operational Readiness:

Are monitoring and alerting mechanisms in place and tested?
Is there a defined and tested incident response plan?
Is the operational documentation complete?
Testing and Quality Assurance:

Are automated tests (unit, integration, end-to-end) passing?
Has manual testing, including UAT, been conducted and passed?
Deployment and Rollback:

Is there a well-defined deployment strategy?
Is there a clear rollback plan?
Dependencies and Integration:

Are all external dependencies verified?
Have all integration points been tested and validated?
By defining and using these criteria, the SRE team can systematically determine whether a "Production Readiness Review" is necessary, ensuring that the application or service is thoroughly evaluated and prepared for production deployment.

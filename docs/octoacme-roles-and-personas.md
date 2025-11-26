# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

The following personas expand coverage for release, documentation, support, and cross-functional activities. Each persona includes responsibilities, interactions with existing roles, and acceptance criteria for work handoffs.

---

### Engineering Lead / Tech Lead

#### Role Summary
Engineering Leads provide technical leadership, guide architectural decisions, and mentor developers. They bridge product requirements and engineering execution.

#### Responsibilities
- Drive technical direction and architecture decisions
- Mentor developers and conduct code reviews
- Collaborate on estimation and technical feasibility
- Identify and address technical debt
- Ensure engineering best practices are followed

#### Interactions
- **Developers**: Provide guidance, review code, unblock technical issues
- **Product Manager**: Collaborate on trade-offs and feasibility assessments
- **Project Manager**: Help estimate work and identify technical risks
- **QA Lead**: Align on testing strategies and quality standards

#### Acceptance Criteria for Handoffs
- Technical decisions are documented and communicated
- Architecture diagrams updated for significant changes
- Knowledge transfer completed before transitioning ownership

---

### Release Manager

#### Role Summary
Release Managers coordinate and oversee releases and deployments, ensuring smooth transitions from development to production.

#### Responsibilities
- Plan and coordinate release schedules
- Manage deployment windows and change approvals
- Ensure rollback and mitigation plans are documented
- Communicate release status to stakeholders
- Coordinate with QA Lead for test signoff

#### Interactions
- **Developers**: Coordinate handover of code ready for release
- **QA Lead**: Confirm test coverage and signoff
- **Project Manager**: Align on scheduling and stakeholder communication
- **On-call/Support Engineer**: Ensure monitoring readiness
- **Security Representative**: Verify security reviews are complete

#### Acceptance Criteria for Handoffs
- Release checklist completed (see [Release Readiness Checklist](./checklists/release-readiness-checklist.md))
- Stakeholders notified of release schedule and outcomes
- Rollback plan tested and documented

---

### On-call / Support Engineer

#### Role Summary
On-call/Support Engineers handle production incidents, triage reported issues, and communicate feedback to product and development teams.

#### Responsibilities
- Monitor production systems and respond to alerts
- Triage and prioritize reported issues
- Escalate critical incidents following the incident playbook
- Capture post-release feedback and trends
- Ensure knowledge base is updated with known issues

#### Interactions
- **Release Manager**: Confirm monitoring and alerting readiness before release
- **Developers**: Report bugs and provide context for reproduction
- **Product Manager**: Communicate user feedback and pain points
- **Project Manager**: Escalate blockers and resource needs

#### Acceptance Criteria for Handoffs
- Incident reports completed with root cause and resolution
- Known issues documented and triaged in backlog
- On-call handoff notes shared with incoming engineer

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers ensure products are user-centered by conducting research, creating designs, and validating usability.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Collaborate on feature specs and acceptance criteria
- Validate designs with users before development
- Document design patterns and style guidelines

#### Interactions
- **Product Manager**: Align on user problems and success metrics
- **Developers**: Hand off design specs and answer implementation questions
- **QA Lead**: Provide expected behavior for UI testing
- **Stakeholders**: Present research findings and design proposals

#### Acceptance Criteria for Handoffs
- Design specs include edge cases and responsive behavior
- Usability testing results documented and shared
- Design assets delivered in agreed formats

---

### Data Analyst

#### Role Summary
Data Analysts extract insights from data to inform product decisions, measure outcomes, and identify opportunities.

#### Responsibilities
- Define and track success metrics
- Build dashboards and reports
- Conduct ad-hoc analysis to answer product questions
- Identify trends, anomalies, and opportunities
- Support A/B testing and experimentation

#### Interactions
- **Product Manager**: Collaborate on metrics and analysis priorities
- **Developers**: Request instrumentation and data pipelines
- **Project Manager**: Provide data for status reports and retrospectives
- **Stakeholders**: Present insights and recommendations

#### Acceptance Criteria for Handoffs
- Analysis documented with methodology and conclusions
- Dashboards accessible and maintained
- Data sources and definitions documented

---

### Security Representative

#### Role Summary
Security Representatives ensure security is integrated into the development lifecycle, from design through deployment.

#### Responsibilities
- Review designs and code for security vulnerabilities
- Ensure security scanning is part of CI/CD
- Respond to security incidents and coordinate remediation
- Maintain security policies and training materials
- Verify compliance with security requirements before release

#### Interactions
- **Developers**: Conduct security reviews and provide guidance
- **Release Manager**: Signoff on security readiness for releases
- **QA Lead**: Coordinate on security testing
- **Project Manager**: Report security risks and status

#### Acceptance Criteria for Handoffs
- Security review completed and documented
- Known vulnerabilities addressed or accepted with mitigation
- Security checklist completed before release

---

### Business Analyst

#### Role Summary
Business Analysts bridge business needs and technical solutions by gathering requirements, documenting processes, and facilitating stakeholder alignment.

#### Responsibilities
- Gather and document business requirements
- Analyze current processes and identify improvements
- Facilitate stakeholder workshops and interviews
- Create process diagrams and specifications
- Support acceptance testing and validation

#### Interactions
- **Product Manager**: Collaborate on requirements and prioritization
- **Developers**: Clarify requirements and answer questions
- **Stakeholders**: Gather needs and present solutions
- **Project Manager**: Support planning and scope definition

#### Acceptance Criteria for Handoffs
- Requirements documented with acceptance criteria
- Stakeholder sign-off obtained
- Process documentation updated

---

### Program Manager

#### Role Summary
Program Managers coordinate across multiple projects or teams, ensuring alignment on goals, dependencies, and timelines.

#### Responsibilities
- Manage cross-project dependencies and risks
- Facilitate alignment across teams and stakeholders
- Track program-level milestones and metrics
- Escalate blockers that span multiple projects
- Ensure consistent reporting and communication

#### Interactions
- **Project Manager**: Coordinate on shared dependencies and timelines
- **Product Manager**: Align on roadmap and priorities
- **Stakeholders**: Provide program-level status and escalations
- **Engineering Lead**: Coordinate on cross-team technical dependencies

#### Acceptance Criteria for Handoffs
- Program status reports delivered on schedule
- Cross-project risks documented and mitigated
- Stakeholder alignment confirmed before major milestones

---

### Technical Writer

#### Role Summary
Technical Writers maintain up-to-date documentation, write guides, and ensure clarity of process and product information.

#### Responsibilities
- Create and maintain process documentation
- Write user guides, release notes, and API documentation
- Collaborate with teams to gather knowledge
- Ensure documentation is accurate and accessible
- Review documentation for clarity and consistency

#### Interactions
- **Product Manager**: Document new features and processes
- **Project Manager**: Maintain project documentation
- **Developers**: Capture technical details and code documentation
- **Release Manager**: Draft and publish release notes

#### Acceptance Criteria for Handoffs
- Documentation reviewed and approved by subject matter experts
- Release notes published with each release
- Documentation updates tracked and versioned

---

### QA Lead

#### Role Summary
QA Leads oversee all quality assurance processes, establish testing standards, and ensure releases meet quality requirements.

#### Responsibilities
- Define and maintain testing standards and strategies
- Coordinate manual and automated testing efforts
- Report on quality metrics and test coverage
- Sign off on release readiness from a quality perspective
- Mentor QA team members

#### Interactions
- **Developers**: Coordinate on test coverage and bug fixes
- **Release Manager**: Provide test signoff for releases
- **Product Manager**: Align on acceptance criteria and quality expectations
- **Security Representative**: Coordinate on security testing

#### Acceptance Criteria for Handoffs
- Test plan executed and results documented
- All critical and high-severity bugs resolved or accepted
- Release signoff provided with summary of quality status

---

## How to Propose a New Persona

To propose a new persona, use the [Persona Proposal Template](./templates/persona-proposal-template.md). The template guides you through defining the persona's summary, responsibilities, interactions, and success criteria. Submit the proposal as a pull request for review by maintainers and stakeholders.


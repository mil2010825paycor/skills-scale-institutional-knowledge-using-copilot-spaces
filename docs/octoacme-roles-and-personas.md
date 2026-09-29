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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define the test strategy and coordinate quality practices throughout delivery. They help the team verify that work meets acceptance criteria and is ready to release.

### Key Responsibilities
- Define test coverage and quality gates for the project
- Plan and coordinate automated, integration, end-to-end, and manual testing
- Review acceptance criteria and provide testability feedback during planning
- Track defects, assess severity, and communicate quality risks
- Verify release criteria, including smoke-test readiness, with the team
- Report test results, coverage, and unresolved quality risks

### Goals and Success Metrics
- Catch defects before production; track escaped defects and defect trends
- Improve useful automated coverage and reduce manual regression effort
- Provide clear, evidence-based release-readiness assessments
- Ensure acceptance criteria and agreed quality gates are verified

### Typical Communication Patterns
- Test plans, test results, and defect reports linked to project work
- Testability feedback in refinement, sprint planning, and pull requests
- Quality and blocker updates in standups and delivery syncs
- Release-readiness coordination with Developers and DevOps/Release Engineers

### Role Interactions
- Partners with Developers and the Technical Lead/Architect to make changes testable and resolve defects.
- Aligns acceptance criteria and release expectations with Product Managers and Project Managers.
- Coordinates test automation and deployment-environment needs with DevOps/Release Engineers.
- Works with the Security Lead on security test coverage and findings; shares quality risks with the team and Stakeholder/Sponsor through the Project Manager.

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects guide technical direction and design so solutions meet product needs while remaining secure, reliable, and maintainable. They surface and help mitigate technical risks.

### Key Responsibilities
- Define and communicate architecture, technical standards, and design decisions
- Review designs and significant changes for scalability, reliability, and maintainability
- Identify technical dependencies, constraints, and risks; agree on mitigations with owners
- Support Developers with implementation choices and complex technical issues
- Coordinate technical requirements with QA/Testing, DevOps/Release, and Security

### Goals and Success Metrics
- Deliver a solution that meets functional and non-functional requirements
- Reduce unmanaged technical risk and costly rework; track risks and design decisions
- Maintain system reliability and maintainability, informed by defects and operational signals
- Enable Developers to make consistent decisions with timely design guidance

### Typical Communication Patterns
- Architecture proposals, decision records, and design reviews
- Technical refinement and planning with Developers and Product Managers
- Risk and dependency updates with the Project Manager
- Operational and security reviews with DevOps/Release Engineers and the Security Lead

### Role Interactions
- Works with Product Managers to translate outcomes into feasible technical approaches and with Developers to implement them.
- Coordinates testability and quality expectations with the QA/Testing Lead.
- Partners with DevOps/Release Engineers on infrastructure, reliability, and release design, and with the Security Lead on security requirements and threat mitigations.
- Provides technical risks and trade-offs to the Project Manager, who coordinates delivery impacts and escalations to the Stakeholder/Sponsor.

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches help the team use its agreed delivery practices effectively. They facilitate collaboration, surface impediments, and support continuous improvement without taking ownership of product decisions or delivery commitments.

### Key Responsibilities
- Facilitate team ceremonies, including planning, standups, reviews, and retrospectives
- Help the team identify and resolve impediments or escalate them to the right owner
- Coach the team on its agreed Agile practices and healthy collaboration
- Support retrospectives and follow through on improvement actions
- Make workflow issues and delivery patterns visible to the team

### Goals and Success Metrics
- Improve the team's ability to deliver and adapt; review flow and predictability trends
- Reduce the age of blockers and ensure impediments have owners and next steps
- Track completion of retrospective actions and team feedback on collaboration
- Keep ceremonies focused, inclusive, and useful to the team

### Typical Communication Patterns
- Facilitated ceremonies, team working agreements, and retrospective notes
- Frequent blocker check-ins with Developers and role leads
- Improvement themes and workflow observations shared with the Project Manager
- Escalations communicated to the relevant decision-maker with context and options

### Role Interactions
- Facilitates collaboration among Developers, QA/Testing, Technical Lead/Architect, DevOps/Release, and Security; helps the team resolve process impediments.
- Coordinates with the Project Manager on dependencies and delivery risks while keeping facilitation distinct from project planning and status ownership.
- Helps Product Managers and the team make backlog discussions productive, and brings improvement themes to the Stakeholder/Sponsor when broader support is needed.

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders provide business, customer, operational, or compliance perspectives. The Sponsor is an accountable stakeholder who supports the project with strategic direction, decisions, and resources.

### Key Responsibilities
- Communicate strategic objectives, constraints, and expected outcomes
- Provide timely decisions on direction, scope trade-offs, and escalated issues
- Secure or coordinate resources and organizational support
- Review progress and outcomes at agreed milestones
- Identify relevant stakeholder groups and represent their needs or concerns

### Goals and Success Metrics
- Ensure the project remains aligned with strategic objectives and stakeholder needs
- Make timely decisions and resolve escalations that exceed the team's authority
- Confirm that expected outcomes and benefits are assessed after delivery
- Ensure material risks, resource constraints, and scope changes are visible

### Typical Communication Patterns
- Milestone reviews and concise status updates from the Project Manager
- Roadmap, customer-value, and outcome discussions with Product Managers
- Decision requests that state options, impacts, and the needed decision date
- Escalations for business-impacting risks, scope, or resource constraints

### Role Interactions
- Sets strategic context and makes business-level decisions with Product Managers, who own product prioritization and outcomes.
- Partners with Project Managers on governance, resourcing, risks, and escalations without directing day-to-day team execution.
- Receives technical, quality, release, and security risks through the Project Manager and relevant leads; provides decisions or resources when escalation is needed.
- Engages the Scrum Master/Agile Coach on team-level impediments only when organizational support or authority is required.

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers own the delivery systems and operational practices that enable safe, repeatable releases. They help teams automate build, test, deployment, and post-deployment verification.

### Key Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Integrate agreed automated tests, quality gates, and security scans into CI
- Coordinate environments, release procedures, and deployment readiness
- Maintain monitoring, operational documentation, and rollback or mitigation procedures
- Execute or support deployments and verify post-deployment health
- Coordinate operational incident response and follow-up actions

### Goals and Success Metrics
- Make releases repeatable and safe; track deployment frequency and change failure rate
- Reduce deployment recovery time and avoid preventable release incidents
- Maintain reliable pipelines and useful deployment-health signals
- Ensure release and rollback procedures are documented and exercised as appropriate

### Typical Communication Patterns
- Pipeline and infrastructure changes through pull requests and technical documentation
- Release plans, deployment checklists, and readiness updates
- CI failures and operational risks shared with Developers, QA/Testing, and the Project Manager
- Incident coordination, monitoring updates, and post-incident actions with relevant leads

### Role Interactions
- Partners with Developers and the Technical Lead/Architect on build systems, infrastructure, reliability, and deployment design.
- Aligns automated quality gates and staging smoke tests with the QA/Testing Lead.
- Integrates security scanning and remediation workflows with the Security Lead.
- Coordinates release scope and timing with Product Managers and Project Managers, and communicates release outcomes to stakeholders through the agreed project channels.

---

## Security Lead

### Role Summary
Security Leads help the team identify and manage security risks across design, implementation, and release. They define applicable security requirements and coordinate reviews and vulnerability remediation.

### Key Responsibilities
- Identify security requirements, applicable policies, and risk areas
- Review designs and changes for security risks and recommend mitigations
- Coordinate security reviews, scanning, and vulnerability triage
- Assign or coordinate remediation owners and track findings to resolution or an approved exception
- Advise on security incidents and escalate material risks through established channels

### Goals and Success Metrics
- Address security requirements and material findings before release or through an approved risk decision
- Track vulnerabilities by severity, ownership, and remediation status
- Improve timely security review and remediation without avoidable delivery delays
- Ensure security risks and exceptions are documented and communicated to decision-makers

### Typical Communication Patterns
- Security requirements and design-review feedback early in planning and implementation
- Findings with severity, impact, recommended action, and owner
- Security scan and remediation status in delivery and release-readiness updates
- Incident coordination with DevOps/Release Engineers and relevant technical leads

### Role Interactions
- Works with the Technical Lead/Architect and Developers to build mitigations into designs and implementation.
- Coordinates security test coverage and finding verification with the QA/Testing Lead.
- Partners with DevOps/Release Engineers to integrate scanning into CI/CD and respond to security incidents.
- Shares security risks and release constraints with the Project Manager and Product Manager; escalates material residual risk to the Stakeholder/Sponsor for an appropriate decision.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

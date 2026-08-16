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

## Additional Personas

Not every project requires every persona below. Applicability depends on project type, size, risk, and complexity — for example, a small internal tool may not need a dedicated Security/Compliance Partner or Business Analyst, while a customer-facing release touching regulated data likely needs both. Project Managers and Product Managers should decide together, during initiation and planning, which of these roles are needed for a given project and document that decision.

## Engineering Lead / Tech Lead

### Role Summary
The Engineering Lead (or Tech Lead) owns technical direction and design alignment for a project, ensuring the engineering approach is sound, consistent, and delivers to the required quality bar.

### Responsibilities
- Set and communicate technical approach, architecture, and design standards
- Identify and manage technical risks and dependencies
- Guide implementation decisions and resolve technical disagreements among Developers
- Review designs and code for quality, maintainability, and scalability
- Support estimation and sequencing of technical work

### Goals
- Deliver a technically sound solution that meets acceptance criteria
- Reduce rework from late-discovered technical risk
- Keep the engineering approach consistent across the team

### Lifecycle Touchpoints
- Initiation and planning: assesses technical feasibility and risk
- Execution: guides implementation and reviews technical decisions
- Release: confirms technical readiness before deployment
- Retrospective: surfaces technical lessons learned

### Interactions with Existing Roles
- **Project Manager**: partners on delivery risks, dependencies, and schedule impacts of technical decisions
- **Product Manager**: advises on feasibility and trade-offs when scoping features
- **Developers**: sets technical direction, reviews work, and unblocks implementation decisions
- **QA/Testing**: aligns on testability, quality gates, and defect triage
- **Stakeholders**: escalation point for technical constraints affecting scope or timeline

### Typical Communication and Artifacts
- Technical design docs and architecture reviews
- Code review comments and engineering standards
- Risk and dependency updates shared with the Project Manager

### Decisions Owned / Escalated
- Owns: technical architecture, implementation approach, engineering standards
- Escalates: scope or timeline trade-offs to the Product Manager and Project Manager

---

## UX/UI or Product Designer

### Role Summary
The UX/UI or Product Designer represents user needs throughout solution design, ensuring the product is usable, accessible, and validated with users before and after release.

### Responsibilities
- Conduct or synthesize user research to inform design decisions
- Produce wireframes, prototypes, and design specifications
- Validate usability through testing and iterate based on feedback
- Help refine acceptance criteria to reflect user experience expectations
- Partner on accessibility and consistency with design standards

### Goals
- Ensure solutions are usable, accessible, and aligned with user needs
- Reduce rework from usability issues discovered late
- Maintain design consistency across the product

### Lifecycle Touchpoints
- Initiation and planning: contributes user research and design feasibility input
- Execution: produces designs and validates usability with users
- Release: confirms user-facing experience is ready for launch
- Retrospective: shares usability findings and feedback trends

### Interactions with Existing Roles
- **Project Manager**: flags design dependencies and timeline needs for research or testing
- **Product Manager**: collaborates on desired outcomes and prioritization of design work
- **Developers**: partners to ensure designs are implementable and testable
- **QA/Testing**: helps define expected behavior and usability acceptance criteria
- **Stakeholders**: gathers input and presents design validation results

### Typical Communication and Artifacts
- Wireframes, prototypes, and design specs
- Usability research findings and readouts
- Refined acceptance criteria reflecting UX requirements

### Decisions Owned / Escalated
- Owns: user experience design, usability validation approach
- Escalates: scope or timeline conflicts to the Product Manager and Project Manager

---

## Release or DevOps Engineer

### Role Summary
The Release or DevOps Engineer coordinates deployment readiness, environments, automation, and observability, ensuring software is released safely and can be rolled back if needed.

### Responsibilities
- Maintain deployment pipelines, environments, and release automation
- Coordinate release timing, sequencing, and rollback plans
- Monitor observability and alerting during and after release
- Support incident response for deployment or infrastructure issues
- Document release and operational runbooks

### Goals
- Ensure safe, repeatable, and low-risk releases
- Minimize downtime and reduce time to detect and recover from incidents
- Maintain reliable environments and deployment automation

### Lifecycle Touchpoints
- Planning: assesses release and environment readiness needs
- Execution: prepares pipelines and automation alongside development
- Release: executes and monitors deployment, manages rollback if needed
- Retrospective: reviews release health and incident learnings

### Interactions with Existing Roles
- **Project Manager**: coordinates release scheduling and communicates release risk
- **Product Manager**: confirms release scope and timing align with business goals
- **Developers**: partners on deployability, automation, and troubleshooting
- **QA/Testing**: aligns on release validation and smoke/regression testing
- **Stakeholders**: communicates release status and incident updates

### Typical Communication and Artifacts
- Release plans, runbooks, and rollback procedures
- Deployment and monitoring dashboards
- Incident reports and postmortems

### Decisions Owned / Escalated
- Owns: release execution, environment configuration, rollback decisions
- Escalates: release delays or major incidents to the Project Manager and stakeholders

---

## Security or Compliance Partner

### Role Summary
The Security or Compliance Partner identifies security, privacy, and regulatory requirements early and validates that controls are in place before release.

### Responsibilities
- Identify applicable security, privacy, and regulatory requirements
- Review designs and implementations for security risks
- Validate controls, audits, and compliance evidence prior to release
- Support risk assessment and threat modeling
- Advise on remediation for identified vulnerabilities

### Goals
- Prevent security and compliance issues from reaching production
- Ensure regulatory obligations are met
- Reduce risk exposure through early identification and mitigation

### Lifecycle Touchpoints
- Initiation and planning: identifies security/compliance requirements early
- Execution: reviews designs and code for risk
- Release: validates controls as part of release gates
- Retrospective: reviews security incidents or gaps

### Interactions with Existing Roles
- **Project Manager**: informs risk register and release gate criteria
- **Product Manager**: engages early on requirements affecting scope and features
- **Engineering Lead / Developers**: reviews technical implementation for security risks
- **QA/Testing**: supports security and compliance test coverage
- **Stakeholders**: communicates risk posture and compliance status

### Typical Communication and Artifacts
- Risk assessments and threat models
- Compliance checklists and audit evidence
- Security review sign-off as part of release gates

### Decisions Owned / Escalated
- Owns: security/compliance requirements and control validation
- Escalates: unresolved risks or compliance gaps blocking release to the Project Manager and stakeholders

---

## Customer or Support Representative

### Role Summary
The Customer or Support Representative brings customer-impact context into the project and channels post-release feedback and support signals back to the team.

### Responsibilities
- Provide input on customer impact and readiness for upcoming changes
- Support enablement, documentation, and training for customer-facing teams
- Capture and relay post-release feedback, issues, and support trends
- Represent customer perspective in planning and prioritization discussions

### Goals
- Ensure customers are prepared for and successfully adopt changes
- Reduce support burden through better readiness and documentation
- Feed real customer signals back into planning

### Lifecycle Touchpoints
- Planning: provides customer impact input
- Execution: contributes readiness and enablement materials
- Release: supports customer communication and readiness
- Retrospective: shares post-release feedback and support trends

### Interactions with Existing Roles
- **Project Manager**: coordinates customer communication timing and readiness activities
- **Product Manager**: shares customer feedback to inform prioritization
- **Developers / QA/Testing**: reports customer-observed issues for triage
- **Stakeholders**: relays customer sentiment and adoption signals

### Typical Communication and Artifacts
- Customer readiness and enablement materials
- Support tickets and post-release feedback summaries
- Release notes and customer communications

### Decisions Owned / Escalated
- Owns: customer readiness and support enablement content
- Escalates: significant customer-impacting issues to the Project Manager and Product Manager

---

## Business Analyst or Operations Subject-Matter Expert

### Role Summary
The Business Analyst or Operations Subject-Matter Expert translates operational needs into requirements, workflows, and acceptance criteria, ensuring solutions align with real-world business processes.

### Responsibilities
- Elicit and document business/operational requirements and workflows
- Translate operational needs into clear, testable acceptance criteria
- Identify process gaps or edge cases affecting operations
- Support scope alignment between business needs and technical solutions

### Goals
- Ensure delivered solutions meet operational needs accurately
- Reduce requirements ambiguity and rework
- Improve alignment between business processes and technical scope

### Lifecycle Touchpoints
- Initiation and planning: documents requirements and workflows
- Execution: clarifies requirements and edge cases as they arise
- Release: validates operational readiness
- Retrospective: reviews whether operational needs were met

### Interactions with Existing Roles
- **Project Manager**: helps align scope, timeline, and operational constraints
- **Product Manager**: partners on prioritization and requirement trade-offs
- **Developers / QA/Testing**: provides domain clarity and clarifies acceptance criteria
- **Stakeholders**: gathers and validates operational requirements

### Typical Communication and Artifacts
- Requirements documents and process workflows
- Acceptance criteria and edge-case documentation
- Operational readiness reviews

### Decisions Owned / Escalated
- Owns: requirements accuracy and operational workflow definitions
- Escalates: scope conflicts between operational needs and technical feasibility to the Product Manager and Project Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


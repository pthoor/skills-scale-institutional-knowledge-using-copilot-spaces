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

### Interactions with Other Roles
- **Product Managers**: Receive feature specs and acceptance criteria; clarify scope and raise technical constraints.
- **Project Managers**: Provide effort estimates, flag blockers, and update task status.
- **QA/Testing**: Collaborate on testability, share test strategies, and resolve defect findings.
- **Engineering Manager/Tech Lead**: Seek technical guidance, participate in design reviews, and receive mentorship.
- **DevOps/Platform Engineer**: Consume CI/CD pipelines, request infrastructure changes, and coordinate deployments.
- **Security Engineer**: Address security findings in code reviews and implement recommended controls.
- **UX/Product Designer**: Implement UI/UX designs, raise feasibility concerns, and request design clarifications.

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

### Interactions with Other Roles
- **Developers**: Communicate feature requirements and acceptance criteria; resolve ambiguities quickly.
- **Project Managers**: Align on scope, timeline, and priorities; escalate risks together.
- **UX/Product Designer**: Co-define user stories; review and approve design solutions.
- **Data Analyst/Analytics Partner**: Define success metrics and review usage data to inform prioritization.
- **Stakeholders**: Present roadmaps, gather requirements, and communicate trade-offs.
- **Customer Support/Success Representative**: Gather customer feedback and surface common pain points.

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

### Interactions with Other Roles
- **Developers**: Coordinate task status, remove blockers, and track delivery progress.
- **Product Managers**: Align on scope, priorities, and milestone commitments.
- **QA/Testing**: Schedule testing windows, track defects, and manage release readiness.
- **Engineering Manager/Tech Lead**: Coordinate capacity planning and escalate technical risks.
- **Stakeholders**: Provide regular status updates, manage expectations, and escalate decisions.
- **DevOps/Platform Engineer**: Coordinate environment availability and deployment scheduling.

---

## QA/Testing

### Role Summary
QA/Testing professionals validate that software meets defined quality standards and acceptance criteria before release. They design test strategies, execute test plans, and advocate for quality throughout the delivery lifecycle.

### Responsibilities
- Define and maintain test plans, test cases, and acceptance criteria checklists
- Execute manual and automated tests across functional and non-functional areas
- Report, track, and verify defects through resolution
- Participate in sprint planning to identify testability requirements
- Advocate for quality gates and Definition of Done criteria
- Coordinate user acceptance testing (UAT) with stakeholders

### Goals
- Prevent defects from reaching production
- Ensure consistent and repeatable test coverage
- Reduce rework and post-release incidents
- Shift quality left by engaging early in the delivery cycle

### Typical Communication
- Test plans and defect reports in the project tracker
- QA sign-off comments on PRs and in release readiness reviews
- Sprint demos and UAT sessions with stakeholders

### Interactions with Other Roles
- **Developers**: Collaborate on test strategies, clarify acceptance criteria, and verify bug fixes.
- **Product Managers**: Validate acceptance criteria and surface gaps in requirements.
- **Project Managers**: Provide test status, flag quality risks, and confirm release readiness.
- **DevOps/Platform Engineer**: Coordinate test environment provisioning and CI pipeline configuration.
- **Security Engineer**: Coordinate security testing and validate vulnerability remediation.
- **Stakeholders**: Facilitate UAT sessions and collect approval sign-off.

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide requirements and strategic direction, approve key decisions, and validate that deliverables meet business needs.

### Responsibilities
- Define and communicate business goals and success criteria
- Review and approve project charters, roadmaps, and key deliverables
- Participate in demos and user acceptance testing
- Escalate business-critical risks or decisions
- Champion the project within the broader organization

### Goals
- Ensure the project delivers measurable business value
- Maintain visibility into progress and risk
- Secure organizational alignment and resource support

### Typical Communication
- Monthly or milestone-based project status updates
- Decision requests and approval reviews
- Demo and UAT participation

### Interactions with Other Roles
- **Product Managers**: Provide strategic input; review and validate product direction.
- **Project Managers**: Receive status updates and escalations; make key decisions.
- **QA/Testing**: Participate in UAT and provide acceptance sign-off.
- **Customer Support/Success Representative**: Share customer insights and validate that solutions address real user needs.
- **Data Analyst/Analytics Partner**: Review business impact metrics and validate success criteria.

---

## UX/Product Designer

### Role Summary
UX/Product Designers are responsible for the user experience and visual design of product features. They translate user needs and business requirements into intuitive, accessible interfaces and workflows that delight customers.

### Responsibilities
- Conduct user research and usability studies to understand customer needs
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns, information architecture, and design systems
- Collaborate with Product Managers to refine user stories and acceptance criteria
- Participate in design reviews and iterate based on feedback
- Ensure accessibility and inclusive design standards are met

### Goals
- Deliver user experiences that are intuitive, accessible, and consistent
- Reduce user friction and support-related issues through thoughtful design
- Validate design decisions with real user feedback before development begins

### Typical Communication
- Design reviews with Product Managers and Developers
- Prototype walkthroughs and usability session reports
- Design handoff documentation (e.g., Figma links, component specs)

### Interactions with Other Roles
- **Developers**: Hand off design specs and assets; clarify design intent and feasibility during implementation.
- **Product Managers**: Co-define user stories, validate design direction against product goals.
- **Project Managers**: Communicate design task status and flag dependencies or timeline risks.
- **QA/Testing**: Support visual and interaction QA; clarify expected behaviors and edge cases.
- **Stakeholders**: Present design concepts for business approval and gather feedback.
- **Customer Support/Success Representative**: Gather pain points and usability insights to inform design priorities.

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager or Tech Lead provides technical leadership and people management for the development team. They ensure architectural integrity, guide technical decisions, and support developers in delivering high-quality software efficiently.

### Responsibilities
- Define and maintain technical standards, architecture patterns, and coding guidelines
- Conduct technical design reviews and mentor developers
- Manage team capacity, skill development, and career growth
- Identify and mitigate technical debt and architectural risks
- Coordinate with Product and Project Managers on feasibility and effort estimates
- Drive resolution of complex technical blockers

### Goals
- Ensure the team delivers technically sound, scalable, and maintainable solutions
- Build team capability and engineering culture
- Balance delivery velocity with long-term technical health

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- 1:1s and team retrospectives for continuous improvement
- Escalation paths for technical risks to Project Managers and stakeholders

### Interactions with Other Roles
- **Developers**: Provide technical mentorship, review designs and code, and unblock complex issues.
- **Product Managers**: Advise on technical feasibility and trade-offs; participate in roadmap discussions.
- **Project Managers**: Communicate team capacity, technical risks, and delivery confidence.
- **DevOps/Platform Engineer**: Collaborate on platform strategy and infrastructure decisions.
- **Security Engineer**: Incorporate security requirements into architecture and coding standards.
- **QA/Testing**: Align on quality standards, test strategies, and definition of done criteria.

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers design, build, and operate the infrastructure, CI/CD pipelines, and tooling that enable reliable, fast, and safe software delivery. They are the bridge between development and production operations.

### Responsibilities
- Build and maintain CI/CD pipelines for automated build, test, and deployment
- Manage cloud infrastructure, container orchestration, and environment configuration
- Monitor system health, performance, and reliability in production
- Define and enforce infrastructure-as-code standards
- Automate operational tasks and reduce manual toil
- Respond to and resolve infrastructure incidents

### Goals
- Enable development teams to ship software faster and more reliably
- Maintain high availability and observability of production systems
- Reduce deployment risk through automation and repeatable processes

### Typical Communication
- Incident reports and post-mortems
- Infrastructure change notifications and deployment runbooks
- Capacity planning updates with Engineering Manager and Project Manager

### Interactions with Other Roles
- **Developers**: Provide tooling, pipelines, and environment support; review infrastructure requirements.
- **Project Managers**: Coordinate deployment windows and communicate infrastructure risks.
- **Engineering Manager/Tech Lead**: Collaborate on platform strategy and technical architecture.
- **Security Engineer**: Implement security controls in infrastructure and pipelines; respond to security findings.
- **QA/Testing**: Provision and maintain test environments; integrate test automation into CI.
- **Stakeholders**: Communicate system reliability metrics and planned infrastructure changes.

---

## Security Engineer

### Role Summary
Security Engineers identify, assess, and remediate security risks across the full software and infrastructure stack. They embed security practices into the development lifecycle to protect customer data and system integrity.

### Responsibilities
- Perform threat modeling, security design reviews, and penetration testing
- Integrate security scanning (SAST, DAST, dependency checks) into CI/CD pipelines
- Define and maintain security policies, standards, and guidelines
- Triage and prioritize security vulnerabilities for remediation
- Respond to security incidents and coordinate remediation
- Educate the team on secure coding practices and emerging threats

### Goals
- Minimize the attack surface and reduce security incidents
- Ensure compliance with applicable security standards and regulations
- Enable teams to ship securely without sacrificing velocity

### Typical Communication
- Security findings in code review comments and issue trackers
- Threat models and security review reports
- Incident response communications and post-mortems

### Interactions with Other Roles
- **Developers**: Review code for security issues; provide remediation guidance and secure coding training.
- **Engineering Manager/Tech Lead**: Advise on security architecture and establish secure design patterns.
- **DevOps/Platform Engineer**: Implement security controls in infrastructure and validate pipeline security gates.
- **Product Managers**: Surface security risks that affect product features or compliance requirements.
- **Project Managers**: Communicate security risk status and estimate remediation effort in project plans.
- **QA/Testing**: Coordinate security testing activities and validate that vulnerabilities are resolved.

---

## Data Analyst / Analytics Partner

### Role Summary
Data Analysts and Analytics Partners provide data-driven insights that inform product decisions, measure feature impact, and support business goals. They translate raw data into actionable intelligence for the team and stakeholders.

### Responsibilities
- Define and instrument success metrics aligned with product and business goals
- Build and maintain dashboards, reports, and data pipelines
- Analyze product usage, feature adoption, and customer behavior
- Support A/B testing and experimentation frameworks
- Ensure data quality, governance, and privacy compliance
- Communicate findings and recommendations to non-technical audiences

### Goals
- Enable data-informed product and business decisions
- Reduce time to insight for the team and stakeholders
- Maintain trustworthy, well-governed data assets

### Typical Communication
- Dashboard links and metric summary reports in project channels
- Analysis write-ups and experiment results shared with Product Managers
- Data review sessions at sprint milestones or release reviews

### Interactions with Other Roles
- **Product Managers**: Co-define success metrics; provide analysis to support prioritization and roadmap decisions.
- **Developers**: Collaborate on data instrumentation and event tracking in product features.
- **Project Managers**: Provide metrics updates that feed into status reports and retrospectives.
- **Stakeholders**: Present business impact analyses and post-launch metric reviews.
- **DevOps/Platform Engineer**: Collaborate on data pipeline infrastructure and observability tooling.
- **Security Engineer**: Ensure data collection and storage practices comply with privacy and security requirements.

---

## Customer Support / Success Representative

### Role Summary
Customer Support and Success Representatives are the voice of the customer within the product team. They capture and communicate real-world user problems, manage customer relationships, and help ensure that product changes positively impact the customer experience.

### Responsibilities
- Collect and categorize customer feedback, bugs, and feature requests
- Communicate customer impact during incident response and release planning
- Participate in UAT and release reviews to validate customer-facing changes
- Maintain knowledge bases, help articles, and internal support documentation
- Escalate high-impact customer issues to Product and Project Managers
- Onboard and support customers through product changes and new feature releases

### Goals
- Advocate for the customer's perspective in every product decision
- Reduce customer friction, support ticket volume, and churn
- Ensure customers are informed, prepared, and successful with product changes

### Typical Communication
- Customer feedback summaries and support trend reports
- Release notes contributions and customer communication drafts
- Escalation tickets and incident impact assessments

### Interactions with Other Roles
- **Product Managers**: Provide qualitative and quantitative customer feedback to inform priorities and validate solutions.
- **Project Managers**: Flag customer-impacting risks and coordinate communication plans around releases.
- **Developers**: Report reproducible customer-facing bugs and validate fixes from the customer perspective.
- **QA/Testing**: Contribute real-world user scenarios to test plans and UAT sessions.
- **Stakeholders**: Report on customer sentiment, adoption trends, and post-launch experience.
- **UX/Product Designer**: Share usability pain points and support insights to inform design improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The collaboration matrix and lifecycle ownership checklist in [octoacme-role-collaboration-checklist.md](octoacme-role-collaboration-checklist.md) provide additional guidance on cross-functional handoffs and responsibilities.


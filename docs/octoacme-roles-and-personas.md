# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

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

### How they interact with other roles
- **QA Lead:** Collaborate on test automation, Definition of Done criteria, and design for testability
- **Tech Lead/Engineering Manager:** Receive technical guidance and unblock impediments
- **Project Manager:** Report progress and blockers in daily standups

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

### How they interact with other roles
- **QA Lead:** Validate feature acceptance criteria and confirm user requirements are met
- **Stakeholder/Sponsor:** Align on business objectives and strategic priorities
- **Project Manager:** Weekly sync on delivery status and trade-offs

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

### How they interact with other roles
- **QA Lead:** Report quality status, risks, and blockers during weekly syncs
- **Tech Lead/Engineering Manager:** Coordinate dependencies and resource allocation
- **Stakeholder/Sponsor:** Escalate strategic issues and seek approvals at gates

---

## Expanded Roles

## Quality Assurance / QA Lead

### Role Summary
QA Leads own the quality strategy, test planning, and acceptance validation for projects. They work closely with developers and product managers to define quality standards and ensure deliverables meet acceptance criteria before release.

### Responsibilities
- Define test strategy and quality standards for each project
- Create and maintain test plans, test cases, and acceptance criteria
- Perform functional, integration, and end-to-end testing
- Validate that features meet acceptance criteria before release
- Identify and document quality gaps and regressions
- Collaborate with developers on testability and automation
- Report quality metrics and test coverage to stakeholders

### Goals
- Deliver high-quality software with minimal defects in production
- Reduce time-to-quality through automation and early testing
- Ensure user acceptance and feature completeness
- Build quality into the development process, not as an afterthought

### Typical Communication
- Sprint planning and refinement sessions
- Quality reviews and sign-off before release
- Defect reports and regression testing updates
- Test strategy discussions with engineering leads

### How they interact with other roles
- **Developers:** Work together on test automation, Definition of Done criteria, and design for testability; provide feedback on code quality
- **Product Managers:** Validate feature acceptance criteria and confirm user requirements are met; adjust test priorities based on product priorities
- **Project Managers:** Report quality status, risks, and blockers during weekly syncs; escalate quality-related schedule impacts
- **Tech Lead/Engineering Manager:** Collaborate on test strategy and quality standards; align on automation priorities

---

## Tech Lead / Engineering Manager

### Role Summary
Tech Leads bridge technical strategy with project delivery. They provide technical guidance, mentor developers, and ensure the project's technical direction aligns with OctoAcme's engineering standards and long-term architecture.

### Responsibilities
- Define technical direction and architecture for projects
- Mentor and guide developers on technical decisions
- Review and approve technical designs and implementations
- Identify and mitigate technical risks and debt
- Ensure compliance with engineering standards and best practices
- Unblock technical impediments and escalate when needed
- Advocate for technical quality and sustainable pace

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and rework
- Build team capability and expertise
- Ensure scalability and long-term sustainability

### Typical Communication
- Technical design reviews and architecture discussions
- 1-on-1 mentoring with team members
- Engineering retrospectives and improvement discussions
- Escalations to leadership for technical decisions

### How they interact with other roles
- **Developers:** Provide technical guidance, code review, and mentoring; unblock technical impediments
- **Product Managers:** Discuss technical trade-offs and feasibility; influence roadmap decisions
- **Project Managers:** Communicate technical risks and resource needs; coordinate cross-team dependencies
- **QA Lead:** Collaborate on test strategy and quality standards

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and executive oversight for projects. They ensure projects deliver on business objectives, have the resources needed, and maintain alignment with organizational priorities.

### Responsibilities
- Define business objectives and success criteria
- Provide approvals at project gates (initiation, planning, release)
- Allocate resources and resolve resource conflicts
- Escalate strategic or business-impacting issues
- Communicate project outcomes to leadership and customers
- Remove organizational or political blockers
- Monitor project health and business value delivery

### Goals
- Ensure projects deliver measurable business value
- Align project delivery with strategic priorities
- Maintain stakeholder confidence and satisfaction
- Enable efficient use of organizational resources

### Typical Communication
- Monthly stakeholder briefings
- Gate review meetings (initiation, planning approval, release approval)
- Ad-hoc escalations and critical decisions
- Executive status reports and business outcome reviews

### How they interact with other roles
- **Project Managers:** Receive status updates and escalations; provide guidance on priority and resource decisions; approve project gates
- **Product Managers:** Review business outcomes and strategic alignment; discuss trade-offs and prioritization
- **Tech Lead/Engineering Manager:** Discuss technical risks with business impact; make decisions on technical investments
- **Leadership team:** Report on portfolio impact, resource allocation, and strategic alignment

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies and coaching to help teams work effectively. They remove impediments, coach teams on agile practices, and foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove team impediments and blockers
- Coach team on agile practices and principles
- Protect the team from external distractions and scope creep
- Foster psychological safety and open communication
- Track and improve team velocity and cycle time
- Escalate systemic issues that impact the team

### Goals
- Enable the team to self-organize and deliver at a sustainable pace
- Improve team communication and collaboration
- Build a culture of continuous improvement
- Maximize flow and minimize waste

### Typical Communication
- Daily standups and sprint ceremonies
- 1-on-1 coaching conversations
- Impediment tracking and resolution
- Retrospective summaries and action items

### How they interact with other roles
- **Developers:** Coach on agile practices; remove impediments; facilitate collaborative problem-solving
- **Project Managers:** Provide team metrics and health indicators; collaborate on dependency management
- **QA Lead:** Ensure quality considerations are included in sprint planning and retrospectives
- **Tech Lead/Engineering Manager:** Collaborate on technical impediments and team capability building

---

## Security Officer / Security Champion

### Role Summary
Security Officers and Champions ensure that OctoAcme projects meet security requirements and compliance standards. They embed security into the development process, conduct threat assessments, and ensure secure deployment practices.

### Responsibilities
- Define security requirements and threat models for projects
- Conduct security code reviews and vulnerability assessments
- Ensure compliance with security standards and regulations
- Perform security testing and penetration testing
- Review deployment and infrastructure security
- Advise on secure design patterns and libraries
- Respond to security incidents and coordinate remediation

### Goals
- Deliver secure software with minimal vulnerabilities in production
- Embed security into the development lifecycle from day one
- Ensure compliance with industry standards and regulations
- Build security awareness across the engineering team

### Typical Communication
- Security requirements discussions during planning
- Security code review comments
- Threat assessments and risk reports
- Incident response and post-incident reviews

### How they interact with other roles
- **Developers:** Review code for security vulnerabilities; advise on secure coding practices
- **Product Managers:** Discuss security requirements and trade-offs with features
- **Project Managers:** Report security risks and escalate critical vulnerabilities
- **DevOps Engineer:** Collaborate on infrastructure security and secure deployment practices

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage infrastructure, CI/CD pipelines, and deployment automation. They enable fast, reliable, and secure deployments while maintaining system stability and performance.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment automation
- Monitor system performance, uptime, and security
- Ensure reliable and secure release processes
- Automate testing, security scanning, and deployment
- Respond to production incidents and performance issues
- Optimize infrastructure costs and performance

### Goals
- Enable fast and reliable deployments
- Maintain high system uptime and performance
- Reduce deployment risk and human error
- Keep infrastructure costs efficient and sustainable

### Typical Communication
- CI/CD pipeline updates and improvements
- Infrastructure and performance reports
- Deployment planning and release coordination
- Incident response and post-incident reviews

### How they interact with other roles
- **Developers:** Provide CI/CD support and infrastructure for local development; respond to deployment issues
- **Project Managers:** Coordinate deployment timing and release windows
- **QA Lead:** Set up test automation and provide environments for testing
- **Security Officer/Security Champion:** Collaborate on security scanning and secure deployment practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Consider how different personas might have different priorities and communication styles when designing project scenarios.
- Recognize that in smaller projects, some personas may be combined or shared across team members.

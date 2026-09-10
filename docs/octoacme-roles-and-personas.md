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

## Product Lead

### Role Summary
Product Leads provide strategic oversight of product direction, ensure stakeholder alignment, and champion the voice of the customer across all project phases. They operate at the intersection of business strategy, product vision, and delivery execution.

### Responsibilities
- Review and approve Project One-pagers and success metrics
- Escalate risks and trade-offs to executive sponsors
- Align product strategy with business objectives and market opportunities
- Review acceptance criteria and feature prioritization decisions
- Validate product outcomes post-release and measure business impact
- Serve as primary liaison between product teams and executive stakeholders
- Guide strategic go/no-go decisions at key project gates

### Interaction with Existing Roles
- **With Product Managers**: Collaborates on vision and strategy; Product Lead sets strategic direction while Product Manager owns prioritization and roadmap execution
- **With Project Managers**: Reviews project charter and high-level timelines; ensures alignment with business objectives and resource availability
- **With Developers**: Participates in technical feasibility assessments during planning phases; approves design trade-offs that impact strategic outcomes

### Goals
- Ensure product initiatives deliver measurable business value and ROI
- Maintain stakeholder confidence and alignment across executive sponsors
- Facilitate cross-team collaboration and clear decision-making
- Reduce time-to-value for strategic initiatives

### Typical Communication
- Weekly alignment meetings with Product Manager and Project Manager
- Monthly stakeholder updates and executive briefings
- Escalation meetings for critical decisions or risks
- Project retrospectives and post-mortems to capture strategic learnings

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads establish quality standards, design test strategies, and ensure acceptance criteria are validated before release. They champion quality throughout the development lifecycle and own test coverage metrics.

### Responsibilities
- Define testing strategy and acceptance criteria validation approach for each project
- Create and maintain test plans, test cases, and test automation frameworks
- Coordinate manual QA and automation efforts across the team
- Report on quality metrics, test coverage, and risk-based testing priorities
- Participate in release readiness assessments and sign-off decisions
- Identify and escalate quality blockers and defect trends
- Mentor developers on testing best practices and testability

### Interaction with Existing Roles
- **With Developers**: Collaborates on acceptance criteria clarity; provides feedback on code testability and suggests automated test coverage improvements
- **With Product Managers**: Works with PdM to validate acceptance criteria are testable; clarifies feature scope and edge cases
- **With Project Managers**: Updates PM on test progress and quality risks; coordinates QA schedule with delivery milestones

### Goals
- Ensure high-quality releases with minimal defects in production
- Maintain comprehensive test coverage and reduce manual testing burden
- Reduce time to quality validation without sacrificing rigor
- Establish shared quality ownership across the team

### Typical Communication
- Sprint planning and retrospectives
- Daily QA standups during active testing phases
- Weekly delivery syncs with quality status updates
- Release readiness sign-off meetings

---

## Technical Lead / Engineering Manager

### Role Summary
Technical Leads provide technical direction and decision-making authority on architecture, design patterns, and technical feasibility. They ensure technical excellence and mentorship while balancing innovation with pragmatism.

### Responsibilities
- Lead technical design reviews and architecture discussions
- Assess technical feasibility of proposed features and identify blockers
- Mentor developers on coding standards, design patterns, and technical best practices
- Identify and mitigate technical risks and dependencies
- Make final decisions on technology choices and technical trade-offs
- Collaborate on performance, scalability, and security considerations
- Represent engineering perspective in prioritization and planning discussions

### Interaction with Existing Roles
- **With Developers**: Provides technical guidance, code review authority, and career development mentorship
- **With Product Managers**: Advises on technical feasibility and timeline impact of feature requests
- **With Product Lead**: Escalates significant technical risks or architectural concerns that affect strategic decisions
- **With Project Managers**: Updates on technical progress, resource needs, and technical blockers

### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Build capability and mentorship within the development team
- Reduce technical debt and improve code quality over time
- Enable faster delivery through clear technical standards and reusable patterns

### Typical Communication
- Technical design review meetings
- Code review participation and feedback
- Weekly technical sync with development team
- Escalation discussions with Product Lead on major technical decisions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide executive visibility, business context, and approval authority for projects. They champion initiatives within the organization and ensure alignment with broader business strategy.

### Responsibilities
- Provide business rationale and strategic context for projects
- Approve project initiation and gate-level decisions
- Escalate organizational blockers and resource needs
- Communicate project progress to broader organization
- Validate that deliverables align with business needs
- Provide executive sponsorship and remove barriers to delivery
- Make business trade-off decisions when needed

### Interaction with Existing Roles
- **With Product Lead**: Receives regular updates and escalations; provides strategic input and approval authority
- **With Project Manager**: Receives status reports and escalations; ensures executive alignment
- **With Product Managers**: Provides business context and prioritization guidance based on organizational strategy

### Goals
- Ensure projects deliver value aligned with business strategy
- Maintain organizational momentum and remove executive-level blockers
- Build stakeholder confidence through transparent communication
- Enable teams to move quickly by providing clear decisions and trade-offs

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Project kickoff and gate-level approval meetings
- Escalation meetings for critical decisions or risks
- Post-release retrospectives with executive stakeholders

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security and compliance requirements throughout the development lifecycle. They embed security practices into processes and escalate risks appropriately.

### Responsibilities
- Define security and compliance requirements for projects
- Review security architecture and threat models
- Coordinate security testing and vulnerability assessments
- Ensure compliance with regulatory and organizational standards
- Provide guidance on secure coding practices and authentication/authorization patterns
- Review release candidates for security readiness
- Participate in incident response and post-incident reviews
- Maintain security risk register and escalate critical findings

### Interaction with Existing Roles
- **With Developers**: Provides security guidance, reviews high-risk code changes, and conducts security training
- **With Technical Leads**: Collaborates on secure architecture design and security trade-off decisions
- **With QA/Testing Leads**: Coordinates security testing and penetration testing activities
- **With Product Leads**: Escalates security risks that may impact release timelines or require business decisions

### Goals
- Reduce security vulnerabilities and compliance breaches in production
- Embed security practices early in development (shift-left security)
- Enable fast, secure delivery without becoming a bottleneck
- Maintain organizational trust and regulatory compliance

### Typical Communication
- Security review meetings during planning phase
- Code review participation for high-risk changes
- Release readiness security sign-off
- Security incident response and escalation
- Quarterly security training and awareness updates

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads bridge development and production, ensuring smooth deployments, monitoring system health, and coordinating incident response. They represent the voice of production reliability and customer support.

### Responsibilities
- Develop and maintain runbooks for deployments and incident response
- Coordinate deployment activities and manage deployment windows
- Monitor system health and alert on critical issues
- Participate in incident triage, response, and post-incident reviews
- Provide input on operability and observability of features
- Capture production feedback and report issues back to development
- Ensure runbooks and documentation are current and accessible

### Interaction with Existing Roles
- **With Developers**: Provides feedback on feature operability; escalates production issues for investigation
- **With Technical Leads**: Collaborates on reliability concerns and escalates architectural issues
- **With Project Managers**: Coordinates deployment schedules and rollback plans
- **With QA/Testing Leads**: Ensures smoke tests and deployment verification procedures are adequate

### Goals
- Minimize downtime and production incidents through smooth deployments
- Reduce time-to-resolution for production issues
- Improve observability and monitoring of deployed systems
- Enable fast, safe releases with confidence in rollback capabilities

### Typical Communication
- Deployment planning and coordination meetings
- Incident response and escalation calls
- Post-incident retrospectives and action items
- Weekly operational status updates
- Release readiness sign-off on deployment procedures

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Existing Roles" section to understand cross-functional collaboration patterns.

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

## Project Sponsor

### Role Summary
Project Sponsors own the business case, provide executive direction and resources, resolve escalated decisions, and confirm go/no-go outcomes. They ensure the project aligns with strategic organizational objectives and has the necessary support and funding.

### Responsibilities
- Own the business case and validate ROI
- Provide executive direction and strategic alignment
- Allocate and commit resources for the project
- Resolve escalated decisions and remove organizational blockers
- Confirm go/no-go decisions at key gates (initiation, planning, release)
- Communicate project importance to the broader organization

### Goals
- Ensure project delivers strategic business value
- Secure organizational support and remove barriers
- Make timely, informed go/no-go decisions
- Maximize return on investment and resource efficiency

### Interactions with Existing Roles
- **Project Manager**: Receives escalations, provides decision authority, receives status updates
- **Product Manager**: Aligns on strategic outcomes, confirms priority and success metrics
- **Developers & QA/Testing**: Aware of project importance; may communicate vision

### Typical Communication
- Milestone gate reviews and go/no-go decisions
- Escalation resolution (blockers requiring executive action)
- Strategic alignment meetings with Product Manager and Project Manager
- Stakeholder communications emphasizing business rationale

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads guide technical execution, own architecture decisions, provide estimates, identify technical risks, and coordinate engineering efforts. They bridge product vision and technical implementation, ensuring solutions are maintainable, scalable, and feasible.

### Responsibilities
- Own technical architecture and design decisions
- Provide technical feasibility assessment and engineering estimates
- Identify and mitigate technical risks and dependencies
- Guide code quality, testing strategy, and engineering best practices
- Mentor developers and facilitate technical problem-solving
- Coordinate technical integration across teams and systems
- Communicate technical constraints and trade-offs to product and project leads

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and engineering risks
- Ensure scalability and performance
- Build team capability and knowledge sharing

### Interactions with Existing Roles
- **Developers**: Provides technical direction, mentorship, and code review authority
- **Product Manager**: Translates product outcomes into technical approach; flags feasibility concerns
- **Project Manager**: Owns technical timeline accuracy; escalates engineering risks and blockers
- **QA/Testing**: Collaborates on test strategy and quality standards

### Typical Communication
- Technical design reviews and architecture decisions
- Sprint planning and estimation
- Risk registers (technical risks and mitigation)
- Code reviews and technical guidance
- Cross-team dependency coordination

---

## UX/Product Designer

### Role Summary
UX/Product Designers define user needs, workflows, and interaction design. They ensure solutions are usable, accessible, and delightful while collaborating with product, engineering, and QA to validate design quality and feasibility.

### Responsibilities
- Conduct user research and identify user needs
- Create wireframes, prototypes, and detailed design specifications
- Define user workflows and interaction patterns
- Ensure accessibility and usability standards are met
- Validate design assumptions through user testing
- Collaborate with developers on design feasibility
- Iterate on design based on feedback and metrics

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Maximize user satisfaction and adoption
- Align design with product strategy

### Interactions with Existing Roles
- **Product Manager**: Collaborates on user needs and feature prioritization
- **Developers**: Partners on feasibility, technical constraints, and implementation details
- **QA/Testing**: Validates design acceptance and usability
- **Project Manager**: Provides design timeline and dependency input

### Typical Communication
- Design reviews and feedback sessions
- User research findings and insights
- Wireframes, prototypes, and design specifications
- Usability testing results and iteration plans
- Design system and accessibility guidance

---

## Release Manager / Delivery Operations

### Role Summary
Release Managers coordinate release readiness, deployment scheduling, operational handoffs, and rollback planning. They ensure releases are smooth, verified, and communicated to stakeholders while minimizing risk and operational disruption.

### Responsibilities
- Coordinate release planning, scheduling, and execution
- Verify pre-release readiness (code, tests, documentation, security scans)
- Manage deployment pipeline and deployment windows
- Plan and validate rollback procedures
- Coordinate operational handoff to support and operations teams
- Conduct post-deployment verification and smoke tests
- Communicate release status and outcomes to stakeholders

### Goals
- Execute reliable, low-risk releases
- Minimize deployment downtime and customer impact
- Ensure smooth operational handoff
- Enable fast rollback if needed

### Interactions with Existing Roles
- **Project Manager**: Owns release timeline and stakeholder coordination
- **Developers**: Provides code readiness and artifact verification
- **QA/Testing**: Validates acceptance criteria and smoke tests
- **Project Sponsor & Stakeholders**: Receives release announcements and status updates

### Typical Communication
- Release checklists and readiness reviews
- Deployment schedules and window announcements
- Release notes and customer-facing communications
- Incident response and rollback decisions
- Post-release verification and retrospectives

---

## Security / Privacy / Compliance Partner

### Role Summary
Security and Compliance Partners review security, privacy, regulatory, and risk requirements. They identify required controls, approve releases or condition them with specific requirements, and ensure the organization meets legal and security obligations.

### Responsibilities
- Review security and privacy requirements
- Identify and assess security risks and compliance gaps
- Define required controls, mitigations, and compliance activities
- Conduct or coordinate security reviews and penetration testing
- Approve or condition releases based on security readiness
- Provide guidance on secure development practices
- Monitor compliance status and escalate unresolved risks

### Goals
- Prevent security breaches and data loss
- Ensure regulatory and legal compliance
- Build secure, privacy-respecting solutions
- Enable business with acceptable risk

### Interactions with Existing Roles
- **Product Manager**: Reviews requirements for privacy and compliance implications
- **Engineering Lead / Developers**: Collaborates on secure design and implementation
- **QA/Testing**: Partners on security testing and validation
- **Project Manager**: Escalates security risks and compliance gates
- **Release Manager**: Approves or conditions production deployments

### Typical Communication
- Security and privacy requirement reviews
- Risk assessments and mitigation plans
- Code and architecture security reviews
- Release approval decisions
- Compliance and incident reporting

---

## Customer Support / Operations Representative

### Role Summary
Customer Support and Operations Representatives bring the customer and operational voice into planning and execution. They prepare support enablement, monitor customer-facing issues post-release, and feed operational insights back to the product and engineering teams.

### Responsibilities
- Understand customer impact and support needs
- Prepare support documentation, training, and runbooks
- Validate customer-facing features and workflows
- Monitor post-release customer issues and feedback
- Escalate critical customer-impacting issues
- Provide insights on customer pain points and operational impact
- Feed support and customer feedback into product improvement

### Goals
- Minimize support burden and customer frustration
- Enable rapid issue resolution and customer satisfaction
- Identify product and operational improvement opportunities
- Reduce operational friction

### Interactions with Existing Roles
- **Product Manager**: Provides customer and operational feedback for prioritization
- **Project Manager**: Alerts on customer impact and escalates critical issues
- **Release Manager**: Coordinates support readiness and deployment communication
- **Developers & QA/Testing**: Collaborates on testability of customer workflows
- **Project Sponsor & Stakeholders**: Escalates major customer-impacting issues

### Typical Communication
- Support readiness and training coordination
- Customer feedback and issue reports
- Post-release health checks and monitoring
- Operational constraint and impact notifications
- Customer satisfaction metrics and trends

---

## Data / Analytics Partner

### Role Summary
Data and Analytics Partners define measurement instrumentation, validate success metrics, and report outcome data after delivery. They enable data-driven decisions by ensuring reliable telemetry and translating data into actionable insights.

### Responsibilities
- Define success metrics and measurement instrumentation
- Ensure reliable data collection and telemetry
- Validate data accuracy and reliability
- Analyze outcome data and provide insights
- Report on success metrics against goals
- Identify gaps in measurement and recommend improvements
- Enable data-driven iteration and optimization

### Goals
- Measure true impact of delivered work
- Enable evidence-based prioritization and decisions
- Identify optimization opportunities
- Reduce guesswork and increase confidence in outcomes

### Interactions with Existing Roles
- **Product Manager**: Collaborates on success metrics and outcome reporting
- **Developers & QA/Testing**: Ensures instrumentation is accurate and reliable
- **Project Manager**: Provides outcome data for project retrospectives
- **Release Manager**: Validates metrics post-release

### Typical Communication
- Success metrics definition and validation
- Measurement and instrumentation planning
- Data quality and accuracy reviews
- Outcome reporting and insights
- Retrospective and learning reviews

---

## Role Interaction Matrix

| Role | Responsible For | Accountable To | Consulted By | Informed By |
|------|---|---|---|---|
| **Project Sponsor** | Business case, strategic alignment | Board/Executive | All roles | PM, Project Manager |
| **Product Manager** | Product vision, outcomes, prioritization | Sponsor, Customers | Engineering Lead, Designers | All delivery roles |
| **Project Manager** | Schedule, risks, communication | Sponsor, PM | All roles | All roles |
| **Engineering Lead** | Technical execution, architecture | Project Manager, PM | Developers, Designers | QA, Security, Release Manager |
| **Developers** | Code quality, implementation | Engineering Lead | Project Manager, Designers | QA, Release Manager |
| **UX/Product Designer** | User experience, usability | Product Manager | Developers, QA | All stakeholders |
| **QA/Testing** | Quality assurance, acceptance | Engineering Lead | Developers, Designers | Release Manager, Support |
| **Release Manager** | Deployment coordination | Project Manager | All delivery roles | Sponsor, Stakeholders |
| **Security Partner** | Security & compliance | Compliance Officer | All roles | Release Manager |
| **Support Representative** | Customer readiness | Operations Lead | Project Manager, Release Manager | All roles |
| **Data/Analytics Partner** | Measurement, outcomes | Product Manager | All roles | All roles |

---

## How These Personas Are Used

- **Scaling projects**: Smaller projects may combine multiple roles; larger initiatives require dedicated ownership.
- **Role selection**: Not all roles apply to every project. Choose roles based on project complexity, risk, and organizational structure.
- **Accountability clarity**: Use the matrix above to understand who is accountable, who needs to be consulted, and who should be informed.
- **Copilot Spaces guidance**: Each persona can be used as a prompt to shape role-specific guidance and checklists within Copilot Spaces.

---

## Key Principles

1. **Clear accountability**: Each role has defined responsibilities and decision authority.
2. **Cross-functional collaboration**: Success requires regular interaction and communication across roles.
3. **Flexibility**: Role definitions can be adapted based on team size, project complexity, and organizational context.
4. **Shared outcomes**: All roles work toward delivering customer and business value.
5. **Continuous improvement**: Refine role definitions and interactions based on retrospectives and team feedback.

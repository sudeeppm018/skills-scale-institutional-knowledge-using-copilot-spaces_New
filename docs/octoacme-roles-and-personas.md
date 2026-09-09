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

### How They Interact with Other Roles
- **Product Managers**: Developers receive acceptance criteria and feature specifications; collaborate on feasibility and trade-offs
- **Project Managers**: Developers provide estimates and progress updates; communicate blockers and dependencies
- **QA/Testing Leads**: Developers work with QA to ensure testability; receive and address defect reports
- **Technical Architects**: Developers follow architectural guidance; participate in design reviews
- **UX/Design Leads**: Developers implement design specifications; provide technical feasibility feedback
- **Business Analysts**: Developers receive detailed requirements and use cases
- **Sponsors/Stakeholders**: Developers present technical progress and risks at reviews

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

### How They Interact with Other Roles
- **Project Managers**: Product Managers define scope and success criteria; PM manages timeline and resources
- **Developers**: Product Managers provide acceptance criteria; developers offer technical insights on feasibility
- **UX/Design Leads**: Product Managers validate user needs; design leads translate to user experience
- **Business Analysts**: Product Managers define business outcomes; analysts create detailed requirements
- **Sponsors/Stakeholders**: Product Managers present business rationale and metrics; sponsors provide strategic alignment
- **QA/Testing Leads**: Product Managers define quality standards; QA validates acceptance criteria
- **Technical Architects**: Product Managers define functional requirements; architects ensures scalability

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

### How They Interact with Other Roles
- **Product Managers**: PM collaborates on scope and timeline; PdM defines business priorities
- **Developers**: PM tracks progress and manages blockers; developers provide estimates and status
- **Sponsors/Stakeholders**: PM escalates risks and decisions; sponsors provide approvals and governance
- **QA/Testing Leads**: PM coordinates release readiness; QA validates quality gates
- **Technical Architects**: PM tracks architectural decisions; architects identify technical risks
- **Business Analysts**: PM uses requirements to build plans; analysts clarify scope and acceptance
- **UX/Design Leads**: PM coordinates design delivery; design leads provide design schedules and dependencies

---

## QA/Testing Leads

### Role Summary
QA/Testing Leads define quality standards, manage testing strategy, and ensure features meet acceptance criteria before release.

### Responsibilities
- Define and maintain test plans and test cases for features
- Execute manual and automated testing; report defects and blockers
- Validate acceptance criteria are met before PRs are merged
- Collaborate with developers on testability and test coverage requirements
- Participate in release readiness assessments and smoke test execution
- Own the test automation strategy and regression suite

### Goals
- Deliver high-quality features with minimal production defects
- Reduce cycle time by catching issues early in development
- Maintain test coverage and automated regression test suite

### Typical Communication
- QA status in daily standups and sprint planning
- Test plan reviews and acceptance criteria feedback
- Defect reports and blockers in PR reviews
- Release readiness sign-offs

### How They Interact with Other Roles
- **Developers**: QA collaborates on testability; receives code for testing and provides defect reports
- **Product Managers**: QA validates against acceptance criteria; provides quality metrics and feedback
- **Project Managers**: QA reports test progress and blocks; participates in release readiness
- **Technical Architects**: QA participates in design reviews to assess testability
- **UX/Design Leads**: QA validates usability and accessibility requirements
- **Business Analysts**: QA uses detailed requirements for test case creation
- **Sponsors/Stakeholders**: QA provides quality assurance sign-off before release

---

## Technical Architects

### Role Summary
Technical Architects define the technical direction, design patterns, and system scalability for projects. They guide technical decisions to ensure long-term sustainability and performance.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigation strategies
- Collaborate with developers on scalability and performance considerations
- Mentor developers on architectural patterns and best practices
- Participate in design reviews and retrospectives to guide technical evolution
- Define technical standards and guidelines for the project

### Goals
- Ensure systems are scalable, maintainable, and aligned with long-term vision
- Reduce technical debt and architectural rework
- Build and share technical expertise across the team

### Typical Communication
- Technical design docs and architecture review meetings
- Risk assessments for complex features
- Mentoring and code review feedback
- Technical guidance in sprint planning

### How They Interact with Other Roles
- **Developers**: Architects provide design direction and mentoring; developers implement and provide feedback on feasibility
- **Project Managers**: Architects identify technical risks and dependencies; PM manages timeline impacts
- **QA/Testing Leads**: Architects define testability requirements; QA validates against design
- **Product Managers**: Architects ensures technical feasibility of features; PdM provides context and trade-offs
- **Business Analysts**: Architects reviews requirements for technical implications
- **UX/Design Leads**: Architects considers performance and technical constraints of designs

---

## UX/Design Leads

### Role Summary
UX/Design Leads ensure user experience is intuitive, accessible, and aligned with product goals. They advocate for the user throughout the project lifecycle.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with product managers and developers on design feasibility
- Define accessibility and design standards for the project
- Validate design decisions through user feedback before implementation
- Ensure consistent design patterns and brand alignment

### Goals
- Deliver intuitive, accessible user experiences that drive adoption
- Align design with business objectives and user needs
- Establish consistent design patterns and system standards

### Typical Communication
- Design reviews and feedback sessions
- User research insights and usability findings
- Design specifications in acceptance criteria
- Accessibility and usability guidance

### How They Interact with Other Roles
- **Product Managers**: Design leads translates product vision to user experience; PdM provides business context
- **Developers**: Design leads provides specifications; developers offer technical feasibility and suggest improvements
- **QA/Testing Leads**: Design leads collaborates on usability testing; QA validates against design specifications
- **Technical Architects**: Design leads considers technical constraints; architects ensures performance
- **Business Analysts**: Design leads uses business requirements to create user flows; analysts validates against business goals
- **Sponsors/Stakeholders**: Design leads presents user research findings; stakeholders provides strategic guidance

---

## Business Analysts

### Role Summary
Business Analysts translate business requirements into functional specifications and validate that solutions meet business goals. They bridge business and technical teams.

### Responsibilities
- Gather and document business requirements and process flows
- Create detailed functional specifications and use cases
- Collaborate with product and technical leads on feasibility and trade-offs
- Define acceptance criteria that map to business outcomes
- Validate solutions against business requirements during QA and release
- Document process changes and impact of new features

### Goals
- Ensure projects deliver measurable business value
- Reduce rework due to unclear or misunderstood requirements
- Improve communication between business and delivery teams

### Typical Communication
- Requirements documentation and specification reviews
- Business case and ROI discussions
- Acceptance criteria definition and validation
- Stakeholder interviews and clarification sessions

### How They Interact with Other Roles
- **Product Managers**: Analysts translates business goals to detailed requirements; PdM provides high-level context
- **Developers**: Analysts provides detailed specifications and use cases; developers ask clarification questions
- **Project Managers**: Analysts helps clarify scope and dependencies; PM tracks timeline
- **QA/Testing Leads**: Analysts works with QA to define test cases based on requirements
- **UX/Design Leads**: Analysts provides business process flows; design leads translates to user experience
- **Technical Architects**: Analysts discusses feasibility and constraints; architects provides technical guidance
- **Sponsors/Stakeholders**: Analysts gathers business requirements; stakeholders provides context and approvals

---

## Sponsors/Stakeholders

### Role Summary
Sponsors and key Stakeholders provide governance, budget approval, and business alignment for projects. They ensure projects deliver strategic value.

### Responsibilities
- Approve project charter, budget, and timeline
- Provide business context and success metrics
- Escalate and resolve blockers that impact business delivery
- Communicate project status to broader organization
- Make go/no-go decisions at key project gates
- Represent business and organizational interests

### Goals
- Ensure projects align with strategic priorities and deliver ROI
- Reduce risk through active governance and oversight
- Enable timely decision-making and resource allocation

### Typical Communication
- Monthly stakeholder updates and status reports
- Gate reviews and approval meetings
- Escalation paths for business-critical issues
- Strategic alignment discussions

### How They Interact with Other Roles
- **Project Managers**: Sponsors receives status updates and escalations; PM coordinates on behalf of delivery team
- **Product Managers**: Sponsors approves business case and priorities; PdM aligns features with business goals
- **Developers**: Sponsors occasionally presents progress and demos; developers implements approved features
- **QA/Testing Leads**: Sponsors receives quality assurance sign-off; QA validates business requirements
- **Business Analysts**: Sponsors provides business context; analysts clarifies requirements
- **Technical Architects**: Sponsors informed of architectural risks; architects ensures technical feasibility
- **UX/Design Leads**: Sponsors reviews design decisions; design leads ensures user value

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions are now documented to help teams understand dependencies and communication patterns.

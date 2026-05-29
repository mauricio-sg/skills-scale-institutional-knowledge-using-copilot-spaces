# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Supporting & Enablement Roles

### UX Designer

#### Role Summary
UX Designers ensure that features are user-centered, accessible, and meet customer needs through research, design, and validation. They bridge the gap between product vision and user experience.

#### Responsibilities
- Conduct user research and translate insights into design requirements
- Create wireframes, prototypes, and design specifications
- Perform usability testing and gather feedback from users
- Collaborate with Product Managers to ensure design aligns with product goals
- Advocate for accessibility and inclusive design principles
- Review implementation against design intent during development

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Validate product decisions with real user feedback

#### Interaction with Other Roles
- Works closely with **Product Managers** to refine user stories and acceptance criteria
- Collaborates with **Developers** during implementation to ensure design fidelity
- Provides input to **Project Managers** on design-related dependencies and timeline impacts

#### Typical Communication
- Design review sessions with cross-functional teams
- Usability testing reports and user insights
- Design specifications and component libraries

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and foster a culture of continuous improvement. They ensure the team adheres to agile principles and optimizes delivery flow.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove impediments blocking the team
- Shield the team from external distractions and scope creep
- Coach the team on agile practices and continuous improvement
- Track team velocity and health metrics
- Escalate recurring blockers to management

#### Goals
- Enable a high-performing, self-organizing team
- Reduce cycle time and improve predictability
- Foster psychological safety and continuous learning

#### Interaction with Other Roles
- Supports **Project Managers** in running ceremonies and removing obstacles
- Collaborates with **Developers** to optimize workflow and team capacity
- Provides insights to **Product Managers** on team health and capacity for planning

#### Typical Communication
- Ceremony facilitation and notes
- Retrospective action items and follow-ups
- Velocity reports and team health dashboards

---

### QA / Quality Assurance

#### Role Summary
QA professionals ensure product quality through comprehensive testing, validation of acceptance criteria, and identification of defects before release. They are the voice of quality and end-user experience.

#### Responsibilities
- Design and execute test plans aligned with acceptance criteria
- Perform manual and automated testing across features
- Identify, document, and track defects
- Validate fixes and regression test changes
- Participate in acceptance criteria refinement
- Contribute to test automation strategy and frameworks
- Provide quality metrics and trend analysis

#### Goals
- Deliver high-quality features with minimal production defects
- Reduce the cost of fixing bugs through early identification
- Maintain comprehensive test coverage and confidence in releases

#### Interaction with Other Roles
- Collaborates with **Developers** on test strategies and defect resolution
- Works with **Product Managers** to clarify acceptance criteria
- Supports **Release Managers** in validating quality gates before deployment

#### Typical Communication
- Test plans and test case documentation
- Defect reports with reproduction steps
- Quality metrics and test coverage reports

---

### Release Manager

#### Role Summary
Release Managers plan, coordinate, and communicate releases across teams. They ensure quality gates are met, rollback plans exist, and deployments are executed with minimal risk.

#### Responsibilities
- Plan and schedule release windows, considering team capacity and dependencies
- Create and maintain pre-release checklists and acceptance criteria
- Coordinate testing, deployment, and verification activities
- Prepare release notes and communication for stakeholders
- Document and test rollback procedures
- Monitor deployments and trigger incident response if needed
- Maintain release documentation and audit trails

#### Goals
- Minimize release risk and unplanned downtime
- Ensure smooth, predictable deployments
- Maintain clear communication across all stakeholders during releases

#### Interaction with Other Roles
- Works with **Developers** to ensure code is deployment-ready and rollback-safe
- Coordinates with **QA** to validate quality gates before release
- Communicates with **Support/Customer Success** to coordinate customer announcements
- Escalates critical issues to **Project Managers** and **Project Sponsors**

#### Typical Communication
- Release plans and deployment checklists
- Pre-release and post-release communications
- Incident reports and rollback documentation

---

## Governance & Leadership Roles

### Project Sponsor

#### Role Summary
Project Sponsors provide business context, secure resources, and serve as the escalation point for critical decisions. They ensure the project remains aligned with business objectives and priorities.

#### Responsibilities
- Define and communicate business objectives and success criteria
- Secure and allocate budget, team, and organizational resources
- Review and approve scope changes and major trade-offs
- Escalate and resolve cross-team dependencies and conflicts
- Review and approve project milestones and release gates
- Communicate project status to senior leadership and stakeholders
- Remove organizational blockers

#### Goals
- Ensure business value is delivered within budget and timeline
- Maintain executive alignment and organizational support
- Enable the team to succeed by removing high-level barriers

#### Interaction with Other Roles
- Partners with **Project Managers** on planning, risk management, and escalations
- Reviews outcomes with **Product Managers** to validate business impact
- Engages with **Developers** and **Scrum Masters** on critical dependencies or resource constraints
- Escalates to C-level leadership when necessary

#### Typical Communication
- Executive status reviews and milestones approvals
- Scope change requests and decisions
- Escalation resolutions and resource confirmations

---

### Support / Customer Success

#### Role Summary
Support and Customer Success teams are the voice of the customer. They provide critical feedback to product and engineering, surface production issues, and ensure end-user needs are represented in prioritization and design decisions.

#### Responsibilities
- Provide customer feedback and usage patterns to Product and Engineering
- Surface production issues, bugs, and performance problems
- Document and prioritize customer requests and pain points
- Ensure customer concerns are addressed in product planning
- Communicate release updates and impacts to customers
- Assist with customer training and adoption of new features
- Monitor customer satisfaction and health metrics

#### Goals
- Maximize customer satisfaction and retention
- Reduce time-to-resolution for customer issues
- Ensure the voice of the customer is heard in product decisions

#### Interaction with Other Roles
- Advises **Product Managers** on customer needs and market opportunities
- Reports production issues to **Developers** and **QA** for triage
- Coordinates with **Release Managers** to understand feature impacts and communicate changes
- Escalates critical customer issues to **Project Managers**

#### Typical Communication
- Customer feedback summaries and request logs
- Production incident reports and severity escalations
- Customer release notes and adoption guidance

---

## Role Interaction Matrix

| Role | Reports to | Works Closely With | Depends On |
|------|------------|-------------------|-----------|
| Developer | Tech Lead / Engineering Manager | Product Manager, QA, Scrum Master | Product Manager, Designer |
| Product Manager | Product Lead | Project Manager, Developer, Designer | Project Manager, Sponsor |
| Project Manager | Program Lead | Product Manager, Developer, Scrum Master | All roles |
| UX Designer | Design Lead / Product Manager | Product Manager, Developer, QA | Product Manager |
| Scrum Master | Engineering Manager | Developer, Project Manager | All delivery roles |
| Release Manager | Engineering Manager / Product Lead | Developer, QA, Support, Project Manager | All roles |
| QA | QA Lead / Engineering Manager | Developer, Product Manager, Release Manager | Developer, Product Manager |
| Project Sponsor | Executive / C-Level | Project Manager, Product Manager | All roles (governance) |
| Support / Customer Success | Support Lead / VP Customer | Product Manager, Developer, Release Manager | All roles |

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in exercises and documentation.
- Reference persona responsibilities when assigning tasks or clarifying ownership.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Update this document as roles, organizational structure, or responsibilities evolve.
- Reference the [Role Responsibilities & Handoff Checklist](./octoacme-role-responsibilities-checklist.md) for detailed phase-by-phase responsibilities and handoff criteria.

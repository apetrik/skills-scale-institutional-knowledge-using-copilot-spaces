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

## UX Designer

### Role Summary
UX Designers own the end-to-end user experience across all product surfaces. They conduct user research, produce design artifacts, and validate usability to ensure the product meets real user needs.

### Responsibilities
- Plan and conduct user research (interviews, surveys, usability tests)
- Create wireframes, prototypes, and high-fidelity design assets
- Maintain a shared design system and component library
- Present design rationale and gather feedback in design reviews
- Validate shipped features against usability criteria

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce usability defects and support tickets related to UX
- Shorten the feedback loop between user insight and product decisions

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Usability test reports and research summaries
- Annotated design specs in the project design tool (e.g., Figma)

### Key Interactions
- **Developers**: Collaborate on feasibility of design proposals, provide detailed specs and assets for implementation, and review built features against designs.
- **Product Managers**: Translate product goals and user insights into design requirements; align on scope and prioritization of design work.
- **Project Managers**: Surface design dependencies and timelines in planning sessions; flag when design reviews block downstream development.

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical execution. They clarify scope, document acceptance criteria, and ensure the team builds the right solution to meet stakeholder needs.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Produce user stories, use cases, and acceptance criteria
- Analyze process gaps and propose improvements
- Facilitate requirements workshops with stakeholders and engineering
- Maintain a requirements traceability matrix to track coverage

### Goals
- Eliminate scope ambiguity and reduce rework caused by unclear requirements
- Ensure all delivered features map to measurable business outcomes
- Keep the backlog well-groomed and ready for development

### Typical Communication
- Requirements workshops and backlog refinement sessions
- Written user stories and acceptance criteria in the issue tracker
- Impact analysis documents when change requests arise

### Key Interactions
- **Developers**: Provide detailed acceptance criteria and clarify edge cases during sprint planning and development; review implementations for requirements compliance.
- **Product Managers**: Translate high-level product goals into structured requirements; flag conflicting or ambiguous requirements for resolution.
- **Project Managers**: Communicate scope changes and their impact on timeline and resources; support risk identification related to requirements gaps.

---

## Technical Writer

### Role Summary
Technical Writers manage documentation, release notes, and knowledge-sharing assets. They ensure that internal and external audiences can find accurate, up-to-date information to perform their work effectively.

### Responsibilities
- Author and maintain product documentation, API references, and user guides
- Write and publish release notes for each product release
- Partner with Developers to document architecture decisions and runbooks
- Establish and enforce documentation standards and templates
- Identify and close knowledge gaps that slow onboarding or cause support escalations

### Goals
- Reduce onboarding time for new team members and customers
- Minimize support tickets caused by missing or outdated documentation
- Build a reliable, searchable knowledge base that scales with the product

### Typical Communication
- Documentation reviews with Developers and Product Managers prior to release
- Release-note drafts circulated to Project Managers and Product Managers for sign-off
- Asynchronous updates via pull requests and documentation platform comments

### Key Interactions
- **Developers**: Collaborate on technical accuracy of architecture docs, runbooks, and API references; request code walkthroughs when documentation requires deeper system understanding.
- **Product Managers**: Align on user-facing messaging, feature descriptions, and release note content; ensure documentation reflects current product positioning.
- **Project Managers**: Incorporate documentation milestones into project timelines; report documentation readiness as a release gate criterion.

---

## DevOps Engineer

### Role Summary
DevOps Engineers own infrastructure, CI/CD pipelines, and deployment reliability. They enable development teams to ship software safely and frequently by automating build, test, and release workflows.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and automated release processes
- Manage cloud infrastructure, environments, and configuration as code
- Monitor system health, define SLOs, and respond to production incidents
- Enforce security and compliance controls in the deployment pipeline
- Drive improvements to deployment frequency, lead time, and recovery time

### Goals
- Achieve zero-downtime deployments and fast, reliable rollbacks
- Reduce manual toil through automation of repetitive operational tasks
- Maintain infrastructure that scales cost-effectively with product growth

### Typical Communication
- On-call runbooks and incident retrospectives
- Infrastructure change proposals and architecture review requests
- Pipeline status dashboards and alerting channels shared with the broader team

### Key Interactions
- **Developers**: Partner on build and test automation, containerization, and environment parity; support debugging of pipeline failures and production issues.
- **Product Managers**: Communicate infrastructure constraints and release windows that affect feature delivery timelines.
- **Project Managers**: Provide deployment readiness status and flag operational risks (e.g., capacity, compliance) that may impact project milestones.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


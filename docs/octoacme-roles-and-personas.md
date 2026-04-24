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
UX Designers ensure that features are usable, accessible, and aligned with user needs. They translate product requirements into designs, run user research, and validate solutions with real users before and after delivery.

### Responsibilities
- Conduct user research, usability testing, and synthesize findings
- Create wireframes, prototypes, and design specifications
- Maintain a design system and ensure visual/interaction consistency
- Collaborate on acceptance criteria to include usability standards
- Review implemented features for design fidelity before release

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce rework by validating designs early with users
- Ensure design decisions are grounded in evidence

### Typical Communication
- Design review sessions with Product Managers and Developers
- Usability test reports shared with the full delivery team
- Async feedback on PRs or prototypes via design tools (e.g., Figma comments)

### Interactions
- **Product Manager**: collaborates on problem framing, success metrics, and feature requirements
- **Developers**: provides design specs and handoff assets; reviews implemented UI
- **Project Manager**: flags design dependencies and timeline impacts during planning
- **QA/Testing**: aligns on usability acceptance criteria and participates in acceptance testing
- **Customer Success**: incorporates user feedback and support insights into design decisions

---

## Data Analyst

### Role Summary
Data Analysts provide the quantitative insights that inform prioritization, track success metrics, and surface trends across the product lifecycle. They partner with Product and Project Managers to ensure decisions are evidence-based.

### Responsibilities
- Define, instrument, and maintain key metrics and dashboards
- Provide ad-hoc analysis to support feature decisions and retrospectives
- Validate that analytics instrumentation is correctly implemented
- Surface anomalies, usage trends, and opportunities in data
- Contribute to the Project One-pager by helping define measurable success criteria

### Goals
- Make data visible and actionable for the whole team
- Ensure success metrics are measured consistently from planning through release
- Enable faster, more confident decision-making

### Typical Communication
- Dashboard links and metric summaries in weekly status updates
- Data deep-dives during planning and retrospective meetings
- Async analysis write-ups shared with Product Manager and stakeholders

### Interactions
- **Product Manager**: co-defines success metrics; provides data to guide backlog prioritization
- **Project Manager**: surfaces trends and anomalies that may affect timelines or risk posture
- **Developers**: aligns on analytics instrumentation requirements and validates data pipelines
- **Customer Success**: combines quantitative data with qualitative feedback for fuller insight
- **Stakeholders**: presents metrics and insights during milestone and executive reviews

---

## Customer Success

### Role Summary
Customer Success (or Support) represents the voice of the customer inside the delivery team. They capture user feedback, monitor adoption, escalate critical issues, and ensure customers can realize value from delivered features.

### Responsibilities
- Collect and triage customer feedback, bug reports, and feature requests
- Communicate customer pain points and priorities to Product Managers
- Create and maintain user-facing guides, FAQs, and support documentation
- Participate in acceptance testing to validate real-world usability
- Coordinate customer communications for releases and incidents

### Goals
- Ensure customers can successfully adopt and use delivered features
- Close the feedback loop between customers and the delivery team
- Reduce support ticket volume through proactive documentation and UX input

### Typical Communication
- Feedback summaries shared with Product Manager before sprint planning
- Incident customer communications coordinated with the Project Manager
- Release announcements and change summaries for end users

### Interactions
- **Product Manager**: provides customer feedback to inform backlog prioritization and roadmap
- **Project Manager**: coordinates customer-facing comms during releases and incidents
- **UX Designer**: shares support insights and user pain points to guide design decisions
- **Data Analyst**: pairs qualitative feedback with quantitative usage data
- **Technical Writer**: collaborates on user-facing release notes and help documentation

---

## Security Lead

### Role Summary
The Security Lead (or Security Engineer) is responsible for the security posture of delivered software. They embed security practices into the development lifecycle, lead incident response for security events, and ensure compliance with relevant standards.

### Responsibilities
- Define and communicate security requirements for new features
- Review architectures, designs, and PRs for security risks
- Oversee security scanning in CI/CD pipelines and act on findings
- Lead triage and response for security incidents (see [Risk Management & Communication](./octoacme-risks-and-communication.md))
- Conduct or coordinate threat modeling for significant changes
- Ensure compliance with applicable security standards and policies

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize mean time to detect and respond to security incidents
- Make security a shared team responsibility, not a gate at the end

### Typical Communication
- Security review notes on PRs and design documents
- Incident status updates during active security events
- Post-incident retrospective findings and remediation action items

### Interactions
- **Developers**: reviews code and architecture; provides secure coding guidance
- **Product Manager**: ensures security requirements are included in acceptance criteria
- **Project Manager**: flags security risks in the Risk Register; escalates incidents per runbook
- **QA/Testing**: aligns on security test coverage and validates scanner findings
- **Stakeholders**: provides clear, timely communications during security incidents

---

## Technical Writer

### Role Summary
Technical Writers create and maintain the documentation that enables teams and users to understand, use, and operate OctoAcme products. They work across the full project lifecycle — from capturing design decisions through post-release user guides.

### Responsibilities
- Draft, review, and publish user-facing documentation (guides, API docs, FAQs)
- Maintain internal process docs and decision logs
- Author or review release notes for every release (see [Release & Deployment Guide](./octoacme-release-and-deployment.md))
- Collaborate with Developers and Product Managers to ensure accuracy
- Identify documentation gaps surfaced by Customer Success or QA

### Goals
- Ensure every feature ships with clear, accurate documentation
- Reduce support burden by making self-service documentation easy to find
- Keep internal process docs up to date as processes evolve

### Typical Communication
- Doc review requests on PRs or design docs
- Release note drafts shared with Product Manager and Customer Success before publication
- Async comments and edits in shared documents

### Interactions
- **Developers**: reviews technical content for accuracy; captures implementation details
- **Product Manager**: aligns documentation scope with feature specs and release plans
- **Project Manager**: ensures documentation tasks are tracked in the backlog and release checklist
- **Customer Success**: incorporates support-driven feedback to improve documentation quality
- **UX Designer**: coordinates on user interface copy and onboarding documentation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For cross-functional ownership at a glance, see the [Cross-Functional Engagement Checklist](./octoacme-cross-functional-engagement-checklist.md).


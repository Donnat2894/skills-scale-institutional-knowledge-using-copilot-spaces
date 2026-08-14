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
- **Works with Technical Architects** on system design and implementation approaches
- **Collaborates with QA/Testing Leads** to ensure code meets quality standards
- **Receives direction from Product Managers** on acceptance criteria and priorities
- **Coordinates with Project Managers** on scheduling and blockers
- **Reports to Release Managers** during deployment and post-release verification

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
- **Receives input from Stakeholders/Sponsors** on business priorities and constraints
- **Works with Project Managers** to plan timelines and dependencies
- **Provides direction to Developers** through acceptance criteria and specs
- **Aligns with Technical Architects** on feasibility and technical trade-offs
- **Partners with QA/Testing Leads** to define acceptance criteria and quality gates

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
- **Facilitates collaboration** between all team roles (Developers, Product Managers, QA, Architects, etc.)
- **Reports to Stakeholders/Sponsors** on progress, risks, and milestones
- **Coordinates with Release Managers** on deployment scheduling and readiness
- **Works with Scrum Masters/Delivery Leads** on sprint cadence and ceremonies
- **Escalates blockers** identified by any team member through defined escalation paths

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality standards, create test strategies, and ensure features meet acceptance criteria and quality gates before release.

### Responsibilities
- Define test plans and acceptance criteria validation approach
- Establish quality standards and testing checklists
- Execute manual QA and oversee automated testing
- Identify and triage quality issues and blockers
- Participate in release readiness reviews

### Goals
- Ensure zero critical defects reach production
- Reduce cycle time for QA verification
- Build confidence in release quality

### Typical Communication
- Sprint planning and backlog refinement
- Daily standups on quality status
- QA signoff on releases
- Bug triage and severity discussions

### Interactions with Other Roles
- **Collaborates with Developers** on test coverage, code quality, and bug fixes
- **Works with Product Managers** to refine acceptance criteria and define quality gates
- **Partners with Technical Architects** on testing strategy for complex systems
- **Coordinates with Release Managers** on pre-release testing and smoke tests
- **Reports to Project Managers** on quality metrics and testing progress

---

## Technical Architect

### Role Summary
Technical Architects define system design, technical direction, and ensure solutions are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Design system architecture and technical solutions
- Review technical proposals and trade-offs
- Identify technical risks and propose mitigation strategies
- Ensure alignment with platform standards and best practices
- Guide developers on implementation approaches

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and rework
- Enable knowledge transfer and consistency across teams

### Typical Communication
- Technical design reviews and architecture discussions
- Planning and estimation sessions
- Code review mentorship
- Risk assessment and mitigation planning

### Interactions with Other Roles
- **Mentors Developers** on implementation approaches and code quality
- **Advises Product Managers** on technical feasibility and trade-offs
- **Collaborates with QA/Testing Leads** on testing strategy for complex architectures
- **Supports Project Managers** by identifying technical risks and dependencies
- **Works with Release Managers** on deployment architecture and rollback strategies

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and sponsors provide business context, prioritization guidance, and executive oversight to ensure projects deliver value and remain aligned with organizational goals.

### Responsibilities
- Define business context and success criteria
- Approve project charter and resource commitments
- Provide guidance on prioritization trade-offs
- Review progress against milestones and business metrics
- Escalate blockers and ensure organizational support

### Goals
- Maximize business value and ROI
- Ensure projects align with strategic objectives
- Provide air cover and remove organizational blockers

### Typical Communication
- Monthly stakeholder updates and reviews
- Milestone and gate reviews
- Escalation for strategic decisions
- Post-project value measurement

### Interactions with Other Roles
- **Receives recommendations from Product Managers** on prioritization and roadmap
- **Works with Project Managers** on milestone reviews and escalation decisions
- **Approves resource commitments** for Developers, Architects, QA, and other roles
- **Reviews outcomes** with Release Managers post-deployment to measure ROI
- **Provides business context** to all team members during project initiation

---

## Scrum Master / Delivery Lead

### Role Summary
Scrum Masters and Delivery Leads facilitate agile ceremonies, remove impediments, and ensure the team maintains velocity and delivers iteratively. They coach the team on agile practices and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Remove impediments and blockers for the delivery team
- Coach team members on agile practices and ceremonies
- Track sprint velocity and identify process improvements
- Protect team focus and minimize distractions

### Goals
- Maintain consistent team velocity
- Improve team collaboration and communication
- Foster a culture of continuous improvement
- Enable the team to self-organize around delivery

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching with team members
- Retrospective facilitation and action item tracking
- Process improvement suggestions to Project Managers

### Interactions with Other Roles
- **Works with Project Managers** to coordinate sprint schedules and roadmap alignment
- **Supports Developers** by removing blockers and facilitating collaboration
- **Coaches all team members** on agile practices and continuous improvement
- **Escalates impediments** that Project Managers must resolve
- **Tracks team health** and raises concerns about burnout or process issues

---

## Release Manager

### Role Summary
Release Managers oversee the deployment process, ensure readiness for production, coordinate rollout activities, and manage post-release verification. They own the release checklist and communication.

### Responsibilities
- Coordinate pre-release testing and readiness verification
- Manage deployment scheduling and communication
- Execute or oversee deployment to production
- Verify post-deployment success and handle rollbacks if needed
- Coordinate release notes and stakeholder announcements

### Goals
- Achieve zero-downtime or minimal-impact deployments
- Ensure release quality and stability
- Improve deployment velocity and confidence
- Reduce post-deployment incidents and rework

### Typical Communication
- Release planning meetings with engineering and stakeholders
- Pre-release readiness reviews with QA, Architects, and Developers
- Deployment coordination and incident response
- Post-release verification and stakeholder updates

### Interactions with Other Roles
- **Coordinates with QA/Testing Leads** on smoke tests and release readiness
- **Works with Developers** on deployment preparation and rollback procedures
- **Consults Technical Architects** on deployment strategy and infrastructure changes
- **Reports to Project Managers** on release status and deployment results
- **Updates Stakeholders/Sponsors** on release outcomes and business metrics
- **Receives deployment readiness confirmation** from all roles before proceeding

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how personas interact to identify communication patterns, dependencies, and escalation paths in project scenarios.

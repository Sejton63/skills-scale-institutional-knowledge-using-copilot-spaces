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

## Security Champion

### Role Summary
The Security Champion helps ensure security is considered throughout planning, development, and release activities. They act as a security advocate embedded in the delivery team and help reduce risk before it reaches production.

### Responsibilities
- Review work for security risks during planning and implementation
- Partner with developers to identify vulnerabilities and secure coding practices
- Support threat assessment and security requirements for features and integrations
- Coordinate security review checkpoints before release
- Help escalate high-risk issues to the appropriate owner

### Goals
- Reduce security risk and prevent avoidable incidents
- Embed secure-by-default practices into day-to-day delivery
- Improve confidence in release readiness and compliance requirements

### Typical Communication
- Security reviews during planning and design
- Risk and dependency updates during standups and weekly syncs
- Release readiness checks with PMs, Product, and engineering leads

### Interaction with Existing Roles
- Works with Developers to review technical design and implementation choices
- Coordinates with Project Managers on risk tracking and escalation
- Aligns with Product Managers on security trade-offs, customer trust, and delivery impact
- Reports critical risks to stakeholders and sponsors when needed

---

## Release Manager

### Role Summary
The Release Manager coordinates the deployment of changes to production while reducing release risk and ensuring clear communication across stakeholders.

### Responsibilities
- Own release scheduling, sequencing, and deployment readiness
- Coordinate pre-release checks, smoke tests, and rollback preparation
- Communicate release scope and timing to stakeholders and support teams
- Confirm that go/no-go criteria are met before deployment
- Capture post-release follow-up and issue triage if problems arise

### Goals
- Reduce deployment-related surprises and operational risk
- Improve release predictability and stakeholder confidence
- Support fast, safe recovery when incidents occur

### Typical Communication
- Release readiness updates with engineering and PM teams
- Deployment communications to stakeholders and support teams
- Post-release status updates and incident follow-up

### Interaction with Existing Roles
- Works with Developers and QA to confirm release quality criteria are met
- Partners with Project Managers on scheduling and approvals
- Supports Product Managers by communicating launch timing and user impact
- Coordinates with Security Champion when security-sensitive changes are involved

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead defines how project success will be measured and how product outcomes are monitored over time. They ensure decisions are informed by evidence, not assumptions.

### Responsibilities
- Define success metrics, KPIs, and reporting needs
- Ensure instrumentation, dashboards, and reporting are in place
- Monitor adoption, quality, and performance signals after launch
- Partner with Product Managers to assess whether outcomes are being achieved
- Help identify when additional learning or iteration is required

### Goals
- Make project decisions evidence-based and measurable
- Improve the visibility of product and operational outcomes
- Support learning loops across the lifecycle

### Typical Communication
- Metric definitions and reporting updates in planning and weekly syncs
- Outcome reviews with Product and PM stakeholders
- Dashboard and signal monitoring with the delivery team

### Interaction with Existing Roles
- Collaborates with Product Managers on success metrics and business impact
- Provides Developers with usage and telemetry needs for instrumentation
- Supports Project Managers in reporting progress and milestone impact
- Helps stakeholders interpret results and adjust priorities

---

## Customer Success / Support Liaison

### Role Summary
The Customer Success / Support Liaison translates customer feedback, adoption patterns, and support issues into actionable project insight. They help ensure customer experience remains central to delivery decisions.

### Responsibilities
- Gather feedback from customers, support teams, and user-facing stakeholders
- Surface recurring pain points, blockers, and product opportunities
- Prioritize high-impact issues and customer-facing risks
- Share adoption, support, and quality trends with project stakeholders
- Support release communication and post-launch follow-up

### Goals
- Improve customer satisfaction and product reliability
- Keep delivery aligned with user needs
- Reduce the gap between customer feedback and product decisions

### Typical Communication
- Customer insight summaries and escalation reports
- Feedback loops with Product and engineering teams
- Support and incident updates during delivery and post-release

### Interaction with Existing Roles
- Provides Product Managers with customer evidence and prioritization input
- Supports Project Managers by identifying risks, stakeholder concerns, and timeline impacts
- Works with Developers to clarify issues and validate bug severity
- Helps Release Manager communicate notable customer impact and rollout considerations

---

## Architecture / Platform Representative

### Role Summary
The Architecture / Platform Representative ensures the team makes sound technical decisions, follows standards, and manages dependencies effectively across systems and services.

### Responsibilities
- Review system design, integration patterns, and technical dependencies
- Recommend architectural standards and platform decisions
- Identify scaling, reliability, and technical debt risks
- Support cross-team coordination for shared systems or platform components
- Help resolve complex technical trade-offs early in delivery

### Goals
- Reduce technical risk and rework
- Improve maintainability, scalability, and operational readiness
- Support sustainable delivery across interconnected systems

### Typical Communication
- Design and dependency reviews with engineering and PM teams
- Architecture risk updates during planning and execution
- Cross-team coordination for shared platform or integration decisions

### Interaction with Existing Roles
- Works closely with Developers to validate implementation choices
- Partners with Project Managers on dependency tracking and milestone planning
- Aligns with Product Managers on technical feasibility and investment trade-offs
- Supports Security Champion and Release Manager on risk, readiness, and deployment considerations

---

## Why these additional roles matter

Project work is rarely delivered by a single function alone. As teams grow and delivery becomes more complex, role clarity is essential for accountability, faster decision-making, and better cross-functional execution. Adding these personas helps the project team:
- Clarify ownership for risks, releases, metrics, and customer impact
- Reduce communication gaps between engineering, product, and stakeholders
- Improve escalation paths and decision quality
- Increase predictability across planning, execution, and release phases
- Support better project outcomes through clearer accountability

---

## How these personas are used in the exercise
- Use these persona definitions to frame project scenarios and team interactions in the Skills Exercise.
- Each persona can be used as a prompt for Copilot Spaces to tailor guidance for role-specific project work.
- Apply these role definitions consistently across initiation, planning, execution, release, and retrospective activities.


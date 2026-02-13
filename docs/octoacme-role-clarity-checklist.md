# OctoAcme — Role Clarity & Responsibility Matrix

## Purpose
Ensure every team member understands their responsibilities, decision-making authority, and collaboration touchpoints, reducing confusion and preventing gaps in project execution.

## When to Use
- During project kickoff to establish clear ownership
- When onboarding new team members mid-project
- After team composition changes or role reassignments
- When confusion about responsibilities emerges
- Quarterly as part of project health checks

## Role Clarity Self-Assessment

Each team member should be able to answer "Yes" to these questions:

### Personal Responsibility Clarity
- [ ] I know what I am accountable for in this project
- [ ] I understand my key deliverables and deadlines
- [ ] I know what decisions I can make independently
- [ ] I know which decisions require consultation or approval
- [ ] I know who I report to for this project
- [ ] I understand my role in team meetings and ceremonies

### Collaboration Clarity
- [ ] I know which team members I work most closely with
- [ ] I understand the handoff points between my work and others
- [ ] I know how to escalate blockers or issues
- [ ] I understand the communication channels and norms for this team
- [ ] I know where to find project documentation and status updates

### Success Clarity
- [ ] I understand how my work contributes to project success
- [ ] I know the metrics or indicators that define success for my role
- [ ] I understand the project timeline and critical milestones
- [ ] I know who depends on my deliverables

---

## RACI Matrix Template

Use this framework to clarify responsibilities for key project activities:
- **R** = Responsible (does the work)
- **A** = Accountable (ultimately answerable, approves)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

### Project Management Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Project planning & timeline | A,R | C | C | C | C | C | I |
| Status reporting | A,R | C | C | I | I | I | I |
| Risk management | A,R | C | C | I | I | C | I |
| Stakeholder communication | A,R | C | I | I | I | I | C |
| Sprint planning | R | A,C | C,R | C | C | C | I |

### Product & Design Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Product roadmap prioritization | C | A,R | C | C | C | I | C |
| User research | I | C | I | A,R | C | I | C |
| Design creation | I | C | C | A,R | I | I | I |
| Design review & approval | I | A | C | R | I | I | I |
| Usability testing | I | C | C | A,R | C | I | C |
| Acceptance criteria definition | C | A,R | C | C | I | I | C |

### Development & Technical Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Technical design | I | C | A,R | I | C | C | I |
| Code implementation | I | I | A,R | C | I | I | I |
| Code review | I | I | A,R | I | I | C | I |
| Unit testing | I | I | A,R | I | I | I | I |
| Integration testing | C | I | A,R | I | C | C | I |
| Data instrumentation | C | C | R | I | A,C | I | I |

### Infrastructure & Deployment Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Infrastructure design | C | I | C | I | C | A,R | I |
| CI/CD pipeline setup | I | I | C | I | I | A,R | I |
| Deployment planning | R | C | C | I | I | A,C | C |
| Deployment execution | C | I | C | I | I | A,R | I |
| Monitoring & alerting setup | C | I | C | I | C | A,R | I |
| Production incident response | C | I | R | I | I | A,R | C |

### Analytics & Measurement Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Success metrics definition | C | A,C | I | C | R | I | C |
| Dashboard creation | I | C | C | I | A,R | I | I |
| A/B test design | C | A,C | C | C | R | I | I |
| Impact analysis | C | C | I | C | A,R | I | I |
| Usage reporting | I | C | I | I | A,R | I | C |

### Support & Customer Activities

| Activity | PM | PdM | Dev | UX | Data | DevOps | Support |
|----------|----|----|-----|----|----|--------|---------|
| Support documentation | C | C | C | C | I | I | A,R |
| Customer communication | C | C | I | I | I | I | A,R |
| Issue triage | I | C | C | I | I | I | A,R |
| Escalation handling | R | C | R | I | I | C | A |
| Customer feedback collection | C | C | I | C | C | I | A,R |

---

## Role-Specific Responsibility Checklists

### Project Manager Checklist
- [ ] I am maintaining the project plan and timeline
- [ ] I am tracking and reporting on project status
- [ ] I am facilitating team meetings and ceremonies
- [ ] I am managing the risk register and escalations
- [ ] I am coordinating cross-team dependencies
- [ ] I am ensuring project documentation is up to date
- [ ] I am the primary point of contact for stakeholder updates

### Product Manager Checklist
- [ ] I own the product vision and strategy
- [ ] I am maintaining a prioritized backlog
- [ ] I am defining and tracking success metrics
- [ ] I am making prioritization decisions and trade-offs
- [ ] I am validating solutions with users and stakeholders
- [ ] I am approving designs and acceptance criteria
- [ ] I am the final decision-maker on scope and features

### Developer Checklist
- [ ] I am implementing assigned features and fixes
- [ ] I am writing and maintaining tests for my code
- [ ] I am participating in code reviews
- [ ] I am contributing to technical design decisions
- [ ] I am collaborating with UX on design implementation
- [ ] I am implementing data instrumentation as specified
- [ ] I am coordinating with DevOps on deployment needs

### UX Designer Checklist
- [ ] I am conducting user research as needed
- [ ] I am creating and maintaining design specifications
- [ ] I am ensuring accessibility standards are met
- [ ] I am reviewing implementation for design fidelity
- [ ] I am collaborating with Product on requirements
- [ ] I am supporting usability testing
- [ ] I am maintaining the design system/component library

### Data Analyst Checklist
- [ ] I am defining and tracking success metrics
- [ ] I am building and maintaining dashboards
- [ ] I am designing and analyzing experiments
- [ ] I am providing data-driven insights to the team
- [ ] I am collaborating with developers on instrumentation
- [ ] I am validating data quality and accuracy
- [ ] I am reporting on feature impact post-launch

### DevOps Engineer Checklist
- [ ] I am managing CI/CD pipelines
- [ ] I am provisioning and maintaining infrastructure
- [ ] I am setting up monitoring and alerting
- [ ] I am coordinating deployment schedules
- [ ] I am responding to production incidents
- [ ] I am documenting deployment procedures
- [ ] I am ensuring security and compliance standards

### Support Lead Checklist
- [ ] I am managing customer support tickets
- [ ] I am triaging and escalating issues appropriately
- [ ] I am maintaining support documentation
- [ ] I am collecting and sharing customer feedback
- [ ] I am coordinating customer communications
- [ ] I am tracking support metrics and trends
- [ ] I am training the support team on new features

---

## Decision-Making Authority Guide

### Independent Decisions (No Approval Needed)
- **Project Manager**: Day-to-day scheduling adjustments, meeting facilitation approaches
- **Product Manager**: Backlog ordering within agreed scope, minor requirement clarifications
- **Developer**: Technical implementation details, code structure, tool selection
- **UX Designer**: Visual design details within established design system
- **Data Analyst**: Analysis methodology, dashboard layout, report format
- **DevOps Engineer**: Infrastructure configuration details, monitoring thresholds
- **Support Lead**: Support ticket prioritization, documentation organization

### Consultative Decisions (Input Required)
- **Project Manager**: Timeline changes, resource reallocation, risk mitigation plans
- **Product Manager**: Feature scope adjustments, acceptance criteria refinements
- **Developer**: Architecture changes, new dependencies, API design
- **UX Designer**: User flow changes, new component creation, accessibility approaches
- **Data Analyst**: New metric definitions, experiment design, data collection methods
- **DevOps Engineer**: Deployment approach changes, new infrastructure services
- **Support Lead**: Support process changes, escalation path modifications

### Approval Decisions (Authorization Required)
- **Project Manager**: Major timeline shifts, budget changes, scope reductions
- **Product Manager**: Roadmap pivots, major feature cuts, release delays
- **Developer**: Breaking changes, major refactors, external API integrations
- **UX Designer**: Design system breaking changes, major UX paradigm shifts
- **Data Analyst**: Changes to core business metrics, data retention policies
- **DevOps Engineer**: Production architecture changes, security configuration changes
- **Support Lead**: Customer SLA modifications, support tier restructuring

---

## Escalation Paths

### Technical Issues
1. Developer → Senior Developer/Tech Lead
2. Tech Lead → Engineering Manager
3. Engineering Manager → VP Engineering / CTO

### Product/Scope Issues
1. Product Manager → Senior Product Manager
2. Senior Product Manager → Director of Product
3. Director of Product → VP Product / CPO

### Project/Timeline Issues
1. Project Manager → Senior Project Manager
2. Senior Project Manager → PMO Lead / Director of Program Management
3. PMO Lead → Executive Sponsor

### Cross-Functional Conflicts
1. Affected team members → Project Manager + Product Manager
2. PM + PdM → Department Heads
3. Department Heads → Executive Leadership

---

## Role Clarity Workshop

If role confusion exists, run a 60-minute workshop:

### Preparation (15 minutes before meeting)
- Share this document with all attendees
- Have each person complete the self-assessment section

### Workshop Agenda
1. **Review Current State** (10 min): Discuss self-assessment results and identify gaps
2. **RACI Clarification** (20 min): Walk through relevant activities and assign RACI
3. **Decision Authority** (15 min): Clarify what each person can decide independently vs. needs approval
4. **Escalation Paths** (10 min): Confirm who to go to when blocked
5. **Action Items** (5 min): Capture any documentation or process updates needed

### Post-Workshop
- [ ] Update project documentation with agreed-upon responsibilities
- [ ] Circulate finalized RACI matrix
- [ ] Schedule follow-up in 2 weeks to address any remaining ambiguity

---

## Ongoing Role Clarity Maintenance

### Weekly Check (in standups or status meetings)
- Are there any areas where ownership is unclear?
- Are handoffs happening smoothly?
- Is anyone blocked due to role confusion?

### Monthly Review
- Review RACI matrix for accuracy
- Update role assignments if team composition changed
- Address any emerging responsibility gaps

### Quarterly Assessment
- Have each team member complete self-assessment again
- Update responsibilities based on lessons learned
- Incorporate feedback into project processes

---

## Signs of Poor Role Clarity (Red Flags)
- Work falling through the cracks (no one owns it)
- Duplicate work (multiple people think they own it)
- Frequent escalations for routine decisions
- Team members unclear on what others are responsible for
- Delays due to waiting for approvals that aren't needed
- Conflicts over decision-making authority
- Inconsistent handoffs between roles

If you observe these patterns, pause and revisit role clarity using this checklist.

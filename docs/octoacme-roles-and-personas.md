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

## QA Lead

### Role Summary
QA Leads ensure quality standards across the product lifecycle. They coordinate test planning, define testing strategies, and work closely with Developers and Product Managers to establish clear acceptance criteria and maintain high quality standards.

### Responsibilities
- Define and maintain testing strategies and quality standards
- Coordinate test planning and execution across the team
- Collaborate with Developers on acceptance criteria and test cases
- Review and approve feature acceptance before release
- Identify quality risks and propose mitigation strategies
- Maintain test automation frameworks and documentation
- Facilitate bug triage and prioritization

### Goals
- Ensure all releases meet quality standards and acceptance criteria
- Reduce production defects and improve test coverage
- Enable faster feedback loops through effective testing
- Build a culture of quality across the team

### Typical Communication
- Daily participation in standups to discuss quality blockers
- Weekly test plan reviews with Developers and Product Managers
- Bug triage sessions and quality metrics reporting
- Pre-release acceptance reviews and sign-offs

---

## UX Designer

### Role Summary
UX Designers create intuitive and user-centered interfaces. They collaborate with Product Managers to understand user needs, design workflows and interfaces, and provide feedback during usability reviews to ensure features meet user expectations.

### Responsibilities
- Design user interfaces, workflows, and interaction patterns
- Conduct user research and usability testing
- Collaborate with Product Managers on feature requirements and user stories
- Create wireframes, prototypes, and design specifications
- Participate in design reviews and provide feedback on implementations
- Ensure consistency with design systems and brand guidelines
- Advocate for accessibility and inclusive design practices

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve task completion rates
- Ensure design consistency across the product
- Validate designs through user feedback and metrics

### Typical Communication
- Design reviews and critique sessions with the team
- Weekly syncs with Product Managers on roadmap and priorities
- Collaboration with Developers during implementation
- User research findings and usability test reports

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure, and deployment automation. They collaborate with Developers and Project Managers to ensure reliable, efficient, and secure software delivery while maintaining production systems.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate testing, building, and deployment processes
- Manage infrastructure and cloud resources
- Monitor system performance, availability, and security
- Collaborate with Developers on deployment strategies and rollback procedures
- Implement and maintain observability tools (logging, metrics, alerting)
- Support incident response and post-incident improvements

### Goals
- Enable fast, reliable, and safe deployments to production
- Minimize deployment-related incidents and downtime
- Improve developer productivity through automation
- Maintain secure and cost-effective infrastructure

### Typical Communication
- Daily monitoring of system health and deployment pipelines
- Weekly infrastructure planning with Project Managers and Developers
- Incident response coordination and post-mortems
- Documentation of deployment procedures and runbooks

---

## Security Champion

### Role Summary
Security Champions advocate for security best practices throughout the development lifecycle. They review code and designs for vulnerabilities, coordinate security testing, and lead incident response efforts to protect the product and users.

### Responsibilities
- Promote security awareness and best practices across the team
- Review code, architecture, and designs for security vulnerabilities
- Coordinate security testing and vulnerability scanning
- Maintain security documentation and threat models
- Lead security incident response and coordinate remediation
- Stay current with security threats and mitigation techniques
- Facilitate security training and knowledge sharing

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with security policies and standards
- Build security awareness across the team
- Minimize time to detect and respond to security incidents

### Typical Communication
- Security review sessions during design and code review
- Weekly security scan results and vulnerability reports
- Incident response coordination and post-incident analysis
- Security training and awareness sessions

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives bridge the gap between engineering teams and business stakeholders. They represent non-engineering stakeholders, gather and provide feedback, and ensure alignment between technical decisions and business goals.

### Responsibilities
- Represent stakeholder interests and business requirements
- Gather and communicate feedback from stakeholders to the team
- Validate that technical solutions align with business goals
- Participate in planning and prioritization discussions
- Review releases and features from a stakeholder perspective
- Facilitate communication between technical and non-technical audiences
- Help resolve conflicts between business and technical priorities

### Goals
- Ensure technical work delivers business value
- Maintain stakeholder satisfaction and engagement
- Facilitate clear communication across technical and business domains
- Identify and address misalignment early in the project lifecycle

### Typical Communication
- Weekly stakeholder updates and feedback sessions
- Monthly business review meetings
- Participation in sprint reviews and demos
- Ad-hoc consultations on business requirements and priorities

---

## Cross-Role Collaboration Checklist

This checklist ensures clear handoffs, accountability, and effective collaboration across all roles throughout the project lifecycle.

### Project Initiation
- [ ] Product Manager defines problem statement and success metrics
- [ ] Stakeholder Representative validates business alignment and gathers stakeholder input
- [ ] Project Manager creates initial timeline and resource plan
- [ ] Security Champion reviews initial security requirements and compliance needs
- [ ] UX Designer conducts initial user research (if applicable)

### Planning Phase
- [ ] Product Manager prioritizes backlog with input from Stakeholder Representative
- [ ] Developers estimate work and identify technical dependencies
- [ ] QA Lead defines testing strategy and acceptance criteria framework
- [ ] DevOps Engineer reviews infrastructure and deployment requirements
- [ ] UX Designer provides design specifications and user flows
- [ ] Security Champion identifies security requirements and threat model
- [ ] Project Manager consolidates plan and secures team commitment

### Execution Phase
- [ ] Developers implement features following acceptance criteria
- [ ] UX Designer reviews implementations for design consistency
- [ ] QA Lead validates features against acceptance criteria
- [ ] Security Champion reviews code for security vulnerabilities
- [ ] DevOps Engineer ensures CI/CD pipeline integration
- [ ] Project Manager tracks progress and manages blockers
- [ ] Product Manager validates alignment with product vision

### Pre-Release
- [ ] QA Lead completes acceptance testing and signs off on quality
- [ ] Security Champion completes security review and vulnerability scan
- [ ] DevOps Engineer validates deployment readiness and rollback procedures
- [ ] UX Designer confirms final UI/UX meets specifications
- [ ] Product Manager approves feature completeness
- [ ] Stakeholder Representative confirms business requirements are met
- [ ] Project Manager coordinates release communication

### Post-Release
- [ ] DevOps Engineer monitors system health and deployment metrics
- [ ] QA Lead tracks production issues and regression testing
- [ ] Product Manager measures success metrics and user feedback
- [ ] UX Designer gathers usability feedback and identifies improvements
- [ ] Project Manager facilitates retrospective with all roles
- [ ] Security Champion monitors for security incidents
- [ ] Stakeholder Representative collects and shares stakeholder feedback

### Ongoing Collaboration
- [ ] All roles participate in daily standups focused on their domain
- [ ] Cross-functional weekly syncs include representation from all key roles
- [ ] Risk escalations follow clear paths (Team → PM → Product Lead → Sponsor)
- [ ] Documentation is maintained and accessible to all roles
- [ ] Knowledge sharing sessions occur regularly
- [ ] Feedback loops are established between all interdependent roles

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


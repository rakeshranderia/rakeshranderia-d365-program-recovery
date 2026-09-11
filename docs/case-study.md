# Recovering and Delivering a Microsoft Dynamics 365 Program

**From requirements and program reset through go-live, hypercare and transition to BAU**

> Organisation and identifying details intentionally omitted.

## Executive overview

This case study describes the recovery and delivery of a Microsoft Dynamics 365 customer platform after two unsuccessful vendor-led implementation attempts.

The program was reset around clearer scope, business ownership, formal project governance, communication, vendor and contract risk management, integration architecture, management reporting and a defined operating-model transition.

The work covered the sales journey, customer service case management, telephony/call-centre integration, knowledge management, ERP and MarTech integration, cross-module and line-of-business reporting, distributed-team coordination, end-user training, data migration, testing, go-live, hypercare and handover to BAU.

![Delivery lifecycle](../assets/d365-delivery-lifecycle.svg)

## 1. Context and program reset

The program had already experienced two unsuccessful vendor-led implementation attempts. Rather than treating the next phase as another technology rollout, the approach was reset around business outcomes, clearer decision rights and a controlled delivery model.

- Re-established business sponsorship, scope and accountability across multiple business units.
- Reframed the work as a business-process, data, integration and adoption program rather than a CRM configuration exercise.
- Defined delivery governance, decision rights, acceptance criteria and escalation paths.
- Introduced stronger vendor risk management where incumbent delivery capability was not sufficient.

## 2. Discovery, requirements and business process

Discovery focused on how customers moved through the organisation, how service interactions were handled, which processes should be standardised, and where local variation was justified.

- **Requirements and user stories** — functional and non-functional requirements, user stories and acceptance criteria.
- **Sales journey** — lead, opportunity, customer, pipeline and sales-management processes, including hand-offs to downstream operational systems.
- **Customer service case management** — case intake, ownership, routing, escalation, service visibility and reporting.
- **Knowledge management** — reusable knowledge content to improve consistency and support service teams.
- **Telephony / call-centre integration** — caller context, case handling, call-centre workflows and connection between telephony and customer-service records.
- **MVP and phasing** — must-have capability separated from later optimisation to restore momentum and control risk.

## 3. Solution and integration design

Dynamics 365 was treated as one component of a wider enterprise ecosystem.

![Enterprise integration](../assets/d365-enterprise-integration.svg)

- D365 for sales, marketing and customer-service capability.
- ERP integration for customer, quote, order, inventory and operational information.
- MarTech integration for marketing automation, campaigns and customer engagement.
- SQL and related data flows for reporting, migration and integration.
- Security, role design, access controls and separation of responsibilities.
- Master-data and data-quality considerations supporting a trusted customer view.
- Reporting and analytics across sales, service and customer interactions.

## 4. Reporting, analytics and management information

Reporting was designed with the CRM rather than added after go-live.

- Cross-module reporting across sales, customer service, marketing and related CRM activity.
- Line-of-business reporting with consistent group definitions and measures.
- CRM activity linked with ERP and operational data to connect sales and service activity to orders, revenue and financial outcomes.
- Pipeline, conversion, customer activity, service levels, case ageing, response/resolution performance, campaign activity and platform adoption.
- Common definitions and data-quality controls to reduce competing versions of the truth.
- Operational reporting for day-to-day management and higher-level reporting for executives and governance forums.
- BAU ownership for dashboard enhancement, KPI definitions and data quality.

## 5. Vendor, contract and delivery risk management

Where an incumbent supplier could not reliably provide all required capability, the delivery model was supplemented while commercial obligations, risk, performance and continuity were actively managed.

- Clearer milestones, deliverables, acceptance criteria and escalation paths.
- Additional specialist capability where vendor performance or expertise was insufficient.
- Delivery, commercial, continuity and dependency risk management across vendors and system integrators.
- Reduced concentration risk by retaining critical knowledge and internal ownership.
- Reviewed and negotiated SOWs, scope, milestones, commercial terms, responsibilities and acceptance criteria.
- Managed contract changes, scope variation and commercial negotiation alongside delivery governance.
- Linked supplier performance to measurable deliverables, service expectations, risk treatment and escalation.

## 6. Building the program team

The delivery model used temporary and permanent roles at different stages of the program.

- Temporary/specialist capability for delivery peaks and specific skill gaps.
- Internal capability development so business and technology teams could increasingly own the platform.
- Recruitment of roles intended to support transition from project delivery into BAU.
- Structured knowledge transfer, documentation and handover so temporary/vendor resources could exit without creating operational dependency.

## 7. Program governance, communication and stakeholder management

![Governance and communication](../assets/d365-governance-communication.svg)

Formal project-management disciplines created visibility, accountability and predictable decision-making across business, technology, vendors and distributed teams.

- RACI for key decisions and deliverables.
- Steering Committee / SteerCo for executive decisions, risk acceptance, scope, budget and escalation.
- Matrix management across business functions, technology specialists, vendors and remote team members.
- RAID controls for Risks, Assumptions, Issues and Dependencies.
- Decision logs, action tracking and escalation thresholds.
- Integrated delivery plans, milestones, critical path, change control and readiness checkpoints.
- Stakeholder and communication plans defining audience, message, owner, channel and frequency.
- Regular project/workstream forums with documented decisions and controlled communications.

## 8. Build, integration and validation

- Platform configuration and customisation.
- ERP, MarTech, SQL and related integration development.
- Data cleansing, mapping and migration planning.
- Progressive demonstrations with business stakeholders.
- UAT against business processes and acceptance criteria.
- OAT covering supportability, access, integrations and production readiness.
- Structured defect triage, prioritisation and retesting.
- Readiness criteria covering technology, data, users, vendors and support.

## 9. Change, training and adoption

Communication, training and adoption were managed as formal workstreams, including geographically distributed and remote staff.

- Planned end-user communications: what was changing, why, when, required actions, cutover impacts and support channels.
- Role-based training using real sales and customer-service scenarios.
- Remote training via virtual sessions, recordings, guides and follow-up clinics.
- Business champions / super users for local adoption, feedback and first-line guidance.
- Readiness and adoption tracking, with recurring questions fed into support documentation and the knowledge base.

## 10. Cutover and go-live

- Sequenced data migration, integration activation, configuration and production validation.
- Go / no-go criteria and escalation responsibilities.
- Fallback and contingency considerations for critical dependencies.
- Vendor, internal-support and business coverage for the initial production period.
- Targeted cutover communications to users, managers and support teams.

## 11. Hypercare and stabilisation

Hypercare provided a structured bridge between project delivery and steady-state operation.

- Dedicated issue and defect triage with severity and ownership.
- Rapid coordination across business, internal technology and vendors.
- Monitoring of key integrations and operational workflows.
- Production defects prioritised separately from later enhancements.
- User support, adoption observation and documentation refinement.
- Progressive transfer of operational knowledge to the BAU team.

## 12. Transition to BAU

BAU transition was designed as part of the program rather than starting after go-live.

- Defined platform, application and integration ownership.
- Established SLAs, escalation and vendor-support arrangements.
- Completed technical and as-built documentation.
- Transferred knowledge to administrators and support roles.
- Embedded change, release and environment-management processes.
- Separated production support from the enhancement backlog.
- Transitioned temporary/specialist roles out as permanent BAU capability became effective.
- Transferred supplier contracts, support obligations, escalation paths and commercial knowledge into BAU.
- Established ongoing vendor-performance and service-review cadence.
- Transferred ownership of CRM reporting, KPI definitions, data-quality monitoring and dashboard enhancement.
- Maintained a reporting and optimisation backlog.

## Key lessons

1. **A failed program usually needs a reset, not another attempt at the same plan.**
2. **CRM is not primarily a software project.** It is a business-process, data, integration and adoption program.
3. **Vendor concentration is a delivery risk.**
4. **Contract management and vendor risk belong together.**
5. **Integration can be harder than configuration.**
6. **Communication is part of delivery control.**
7. **Distributed teams need deliberate enablement.**
8. **Reporting should be designed with the platform.**
9. **Go-live is a milestone, not the finish line.**
10. **Standardise the core; govern the exceptions.**

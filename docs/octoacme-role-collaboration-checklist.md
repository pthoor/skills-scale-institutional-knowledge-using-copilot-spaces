# OctoAcme Role Collaboration Checklist

This document provides a collaboration matrix and lifecycle ownership checklist to make cross-functional handoffs, responsibilities, and communication explicit across all OctoAcme project roles.

For full role definitions, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

---

## Collaboration Matrix

The table below shows the primary collaboration relationship between each pair of roles. Use this to identify who needs to be involved, consulted, or informed at each stage.

| | Dev | PdM | PM | QA | EM/TL | DevOps | SecEng | Designer | Data | Support | Stakeholder |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Developer** | — | Consulted | Informed | Collaborates | Reports to | Depends on | Consulted | Implements | Instruments | Informs | — |
| **Product Manager** | Directs | — | Partners | Informs | Consults | Informs | Informs | Directs | Partners | Receives from | Reports to |
| **Project Manager** | Tracks | Partners | — | Tracks | Coordinates | Coordinates | Informs | Tracks | Informs | Coordinates | Reports to |
| **QA/Testing** | Collaborates | Validates | Reports to | — | Informs | Depends on | Coordinates | Consults | — | Supports | Facilitates UAT |
| **EM/Tech Lead** | Mentors | Consults | Informs | Aligns | — | Collaborates | Collaborates | Reviews | — | — | — |
| **DevOps/Platform** | Enables | Informs | Coordinates | Supports | Collaborates | — | Implements for | — | Supports | — | Informs |
| **Security Engineer** | Reviews | Advises | Informs | Coordinates | Advises | Collaborates | — | — | Governs | — | — |
| **UX/Product Designer** | Hands off to | Partners | Reports to | Supports | Consults | — | — | — | Consults | Receives from | Presents to |
| **Data Analyst** | Instruments | Partners | Informs | — | — | Supports | Consults | Consults | — | — | Reports to |
| **Support/Success** | Reports bugs to | Advocates to | Informs | Supports UAT | — | — | — | Informs | Provides input | — | Reports to |
| **Stakeholder** | — | Directs | Receives from | Approves UAT | — | — | — | Approves | Reviews | Informs | — |

**Legend:**
- **Partners** — Frequent, two-way collaboration; joint decisions
- **Collaborates** — Works closely together on shared deliverables
- **Directs / Reports to** — Provides direction or receives direction
- **Consults** — Provides expertise or input on demand
- **Informs** — Keeps the other party updated; one-way communication
- **Coordinates** — Plans timing, sequencing, or logistics together
- **Supports** — Assists or enables the other role's work
- **Depends on** — Relies on the other role to complete own work
- **Tracks** — Monitors status and progress

---

## Lifecycle Ownership Checklist

Each lifecycle phase lists who **Owns** (primary accountability), who **Contributes** (active participants), and who should be **Consulted/Informed** (kept in the loop).

### Phase 1: Initiation

| Activity | Owner | Contributors | Consulted / Informed |
|---|---|---|---|
| Define problem statement and business case | Product Manager | Stakeholders | Project Manager, EM/Tech Lead |
| Identify stakeholders and communication plan | Project Manager | Product Manager | All roles |
| Draft project one-pager / charter | Project Manager | Product Manager, EM/Tech Lead | Stakeholders |
| Identify initial risks and dependencies | Project Manager | EM/Tech Lead, Security Engineer | DevOps/Platform, Product Manager |
| Confirm team roles and resource availability | Project Manager | EM/Tech Lead | All roles |
| Obtain go/no-go decision | Stakeholders | Product Manager, Project Manager | EM/Tech Lead |

**Initiation Checklist:**
- [ ] Problem statement and business case documented
- [ ] Stakeholder list and communication plan created
- [ ] Project one-pager reviewed and approved
- [ ] Initial risk register created
- [ ] Team roles confirmed and resource availability verified
- [ ] Go/no-go decision recorded

---

### Phase 2: Planning

| Activity | Owner | Contributors | Consulted / Informed |
|---|---|---|---|
| Define scope, milestones, and success metrics | Product Manager | Project Manager, EM/Tech Lead | Stakeholders, Data Analyst |
| Create and prioritize backlog | Product Manager | Developers, UX/Product Designer | QA/Testing, EM/Tech Lead |
| Create UX research plan and initial wireframes | UX/Product Designer | Product Manager | Developers, QA/Testing |
| Define technical architecture and standards | EM/Tech Lead | Developers, DevOps/Platform | Security Engineer |
| Perform threat modeling and security review | Security Engineer | EM/Tech Lead, Developers | DevOps/Platform, Project Manager |
| Define test strategy and quality gates | QA/Testing | Developers, EM/Tech Lead | Project Manager, DevOps/Platform |
| Plan infrastructure and environment needs | DevOps/Platform | EM/Tech Lead, Project Manager | Developers, Security Engineer |
| Define data instrumentation and metrics plan | Data Analyst | Product Manager, Developers | Project Manager |
| Plan customer communication and support readiness | Support/Success Representative | Product Manager, Project Manager | Stakeholders |
| Finalize project plan and timeline | Project Manager | All roles | Stakeholders |

**Planning Checklist:**
- [ ] Scope, milestones, and success metrics defined
- [ ] Backlog prioritized with acceptance criteria
- [ ] UX wireframes or prototypes drafted for key features
- [ ] Technical architecture and coding standards documented
- [ ] Threat model and security requirements captured
- [ ] Test strategy and quality gates defined
- [ ] Infrastructure and environment plan confirmed
- [ ] Data instrumentation plan agreed upon
- [ ] Customer communication and support plan drafted
- [ ] Project plan and timeline reviewed and approved by stakeholders

---

### Phase 3: Execution

| Activity | Owner | Contributors | Consulted / Informed |
|---|---|---|---|
| Implement features per acceptance criteria | Developers | UX/Product Designer | QA/Testing, EM/Tech Lead |
| Review and merge pull requests | EM/Tech Lead | Developers, Security Engineer | DevOps/Platform |
| Execute test cases and report defects | QA/Testing | Developers | Project Manager, Product Manager |
| Monitor CI/CD pipelines and environments | DevOps/Platform | Developers | EM/Tech Lead, Project Manager |
| Track delivery progress and manage blockers | Project Manager | All roles | Stakeholders |
| Perform security code reviews and scanning | Security Engineer | Developers, DevOps/Platform | EM/Tech Lead |
| Validate designs in implementation | UX/Product Designer | Developers, QA/Testing | Product Manager |
| Instrument and monitor success metrics | Data Analyst | Developers, DevOps/Platform | Product Manager |
| Update support documentation and training | Support/Success Representative | Product Manager | Project Manager |
| Provide ongoing stakeholder status updates | Project Manager | Product Manager | Stakeholders |

**Execution Checklist:**
- [ ] Features implemented and meeting acceptance criteria
- [ ] All PRs reviewed and merged per branch conventions
- [ ] Defects logged, triaged, and tracked to resolution
- [ ] CI/CD pipelines passing for all changes
- [ ] Blockers escalated and resolved in a timely manner
- [ ] Security findings addressed before release
- [ ] Designs validated and design debt logged
- [ ] Success metrics instrumented and baseline confirmed
- [ ] Support docs and training materials updated
- [ ] Stakeholders receiving regular status updates

---

### Phase 4: Release

| Activity | Owner | Contributors | Consulted / Informed |
|---|---|---|---|
| Release readiness review and sign-off | Project Manager | Product Manager, QA/Testing, EM/Tech Lead | Stakeholders, Security Engineer |
| Final regression and smoke testing | QA/Testing | Developers, DevOps/Platform | Project Manager |
| Deploy to production | DevOps/Platform | Developers | EM/Tech Lead, Project Manager |
| Validate security posture pre-release | Security Engineer | DevOps/Platform, Developers | Project Manager |
| Confirm production metrics and monitoring | Data Analyst | DevOps/Platform | Product Manager, Project Manager |
| Prepare and publish release notes | Product Manager | UX/Product Designer, Support/Success Representative | Stakeholders, Developers |
| Customer communication and enablement | Support/Success Representative | Product Manager | Stakeholders |
| Stakeholder announcement and demo | Product Manager | Project Manager | All roles |

**Release Checklist:**
- [ ] Release readiness review completed and signed off
- [ ] Regression and smoke tests passed in staging/pre-prod
- [ ] Production deployment executed and verified
- [ ] Security controls validated in production
- [ ] Dashboards and alerts confirmed active in production
- [ ] Release notes published
- [ ] Customer communication sent
- [ ] Stakeholder announcement delivered

---

### Phase 5: Retrospective & Continuous Improvement

| Activity | Owner | Contributors | Consulted / Informed |
|---|---|---|---|
| Facilitate retrospective session | Project Manager | All roles | Stakeholders (optional) |
| Analyze post-release metrics and outcomes | Data Analyst | Product Manager | Project Manager, Stakeholders |
| Capture and prioritize improvement actions | Project Manager | Product Manager, EM/Tech Lead | All roles |
| Update process documentation | Project Manager | EM/Tech Lead, QA/Testing, Security Engineer | All roles |
| Review customer feedback post-launch | Support/Success Representative | Product Manager | Project Manager, Data Analyst |
| Archive project artifacts and lessons learned | Project Manager | All roles | Stakeholders |

**Retrospective Checklist:**
- [ ] Retrospective session held with all key roles present
- [ ] Post-launch metrics reviewed against success criteria
- [ ] Improvement actions documented and owners assigned
- [ ] Process documentation updated with lessons learned
- [ ] Customer feedback reviewed and fed into backlog
- [ ] Project artifacts archived and accessible

---

## Quick Reference: Who to Involve When

| Scenario | Primary Contact | Also Involve |
|---|---|---|
| New feature request or scope change | Product Manager | Project Manager, EM/Tech Lead |
| Production incident | DevOps/Platform | Developers, EM/Tech Lead, Project Manager, Security Engineer |
| Security vulnerability discovered | Security Engineer | EM/Tech Lead, Developers, Project Manager |
| Customer-reported bug or friction | Support/Success Representative | Product Manager, Developers, QA/Testing |
| Missed deadline or delivery risk | Project Manager | Product Manager, EM/Tech Lead, Stakeholders |
| UX or design feedback needed | UX/Product Designer | Product Manager, Developers |
| Data metric or analytics question | Data Analyst | Product Manager, Developers |
| Team capacity or skill gap | EM/Tech Lead | Project Manager, Product Manager |
| Release go/no-go decision | Project Manager | Product Manager, QA/Testing, Security Engineer, Stakeholders |

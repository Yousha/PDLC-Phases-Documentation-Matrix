# SDLC Phases & Documentation Matrix

A good reference matrix mapping documentation, diagrams, and deliverables to each phase of the Software(Product) Development Life Cycle. (with help of AI)

This shows the phases involved in producing a software product, and within each phase, what documents and diagrams need to be created.
So that the output of one phase becomes the input for the next phase.

💡 So instead of diving straight into code, making chaos, skipping the early project stages, or hiring a product designer at first... developers can rely on this!

> This framework supports both traditional waterfall projects and agile MVP/MLP development paths.

# Contents

- [Phase 0 - Ideation & Brainstorming](#phase-0---ideation--brainstorming)
- [Phase 1 - Conception & Feasibility](#phase-1---conception--feasibility)
- [Phase 2 - Planning & Requirements Analysis](#phase-2---planning--requirements-analysis)
- [Phase 3 - Design](#phase-3---design)
- [Phase 4 - Implementation](#phase-4---implementation)
- [Phase 5 - Testing](#phase-5---testing)
- [Phase 6 - Release & Deployment](#phase-6---release--deployment)
- [Phase 7 - Maintenance & Improvement](#phase-7---maintenance--improvement)
- [MVP/MLP Path](#mvpmlp-path)
- [Notes](#notes)

## Phase 0 - Ideation & Brainstorming

**Goal:** Identify real problems, market opportunities, capture raw ideas, and generate initial product concepts.

**Artifacts**

* Documents:
  * Ideas list
  * Research report
  * Market Validation Report
  * Risk register
  * JTBD
  * High-level user interview
* Diagrams:
  * Mind map

**Output**

* Documents
* Diagram
* Final validated idea

## Phase 1 - Conception & Feasibility

**Goal:** Determine if the product is viable and decide whether to build.

**Artifacts**

* Documents:
  * Project charter
  * High-level timeline roadmap
  * Feasibility study report
  * ROI Projection
  * Initial stakeholder register
  * Initial product requirements document (PRD)
  * Business case
* Diagrams:
  * System context digram (L1)
  * High-level feature map
  * Business process flow diagram

**Output**

* Documents
* Diagrams

## Phase 2 - Planning & Requirements Analysis

**Goal:** Define WHAT to build, priorities and WHAT the product must do.

**Artifacts**

* Documents:
  * Software requirements specification (SRS) – functional & non-functional
  * Full PRD
  * Performance Requirements Specification (PRS)
  * High-level security requirements
  * User stories with acceptance criteria
  * Requirements traceability matrix (RTM)
* Diagrams:
  * Use case diagrams
  * Container diagram (L2)
  * UI sketches / Lo-Fi Wireframe

**Output**

* Documents
* Diagrams
* Initial designs

## Phase 3 - Design

**Goal:** Define HOW the product will be built and define architectures.

**Artifacts**

* Documents:
  * Technical specification document (TSD)
  * System design document
  * Data architecture document
  * Database design document (DDD)
  * UI/UX design specifications
  * Security architecture
  * Deployment architecture
  * Scalability Documentation
  * Architecture decision records (ADRs)
  * API design and specifications
* Diagrams:
  * User flow diagrams
  * Design system / UI Kit
  * Data flow diagrams (L0, L1)
  * Component diagrams
  * Sequence diagrams
  * Entity-relationship diagrams (ERD)
  * Wireframes / mockups
  * Network and infrastructure topology

**Output**

* Documents
* Diagrams
* Final designs

## Phase 4 - Implementation

**Goal:** Build/Develop the product.

**Artifacts**

* Documents:
  * Developer guides
  * Code review checklist
  * Dependency update policy
  * DevOps Pipeline Documentation
  * Coding standards
* Diagrams:
  * Updated user flows
  * Updated data flows
  * Code architecture diagrams
  * Deployment topology

**Output**

* Documents
* Diagrams
* Product source code

## Phase 5 - Testing

**Goal:** Verify the product works correctly. Functionality, performance, & security.

**Artifacts**

* Documents:
  * Test strategy
  * Test plans
  * Test cases
  * Test results and reports
  * Security test report
* Diagrams:
  * Issue lifecycle flow

**Output**

* Documents
* Diagrams
* Reports
* Verified product source

## Phase 6 - Release & Deployment

**Goal:** Release/Deploy the product to users.

**Artifacts**

* Documents:
  * Release process documentation
  * Deployment runbook
  * Versioning scheme
  * Rollback procedure
  * End-user guides
  * Installation guide
  * Administrator guides
  * Changelog
* Diagrams:
  * CI/CD deployment pipeline
  * Environment topology

**Output**

* Documents
* Diagrams
* Stable product

## Phase 7 - Maintenance & Improvement

**Goal:** Keep system healthy; manage incidents and maintenance.

**Artifacts**

* Documents:
  * Incident response plan and post-incident report templates
  * Monitoring and observability guides
  * Backup and disaster recovery procedures
  * Vulnerability disclosure policy
  * Operations runbooks
  * Technical debt register
  * Compliance checklist
* Diagrams:
  * Incident response workflow

**Output**

* Documents
* Diagrams
* Reports

## **MVP/MLP Path**

For fast-paced or resource-constrained projects, focus on these essentials:

| **Phase**                   | **Essential Items** |
|-----------------------------|---------------------|
| **Conception/Feasibility**  | Project Charter • Short PRD • Stakeholder Register |
| **Planning/Analysis**       | High-Level SRS • Prioritized Backlog • Acceptance Criteria • Risk Register |
| **Design**                  | TSD + ADR Index • Data Model (ERD) • Deployment Architecture |
| **Implementation**          | Coding Standards • CI Spec • API Spec • Unit Test Target |
| **Testing**                 | Test Plan • Automated Test Suites • Test Environment Setup |
| **Release/Deployment**      | Release Checklist • Rollback Plan • Release Notes Template |
| **Maintenance/Improvement** | Monitoring Specification • SLOs • Incident Runbook • On-call Rota |

## **Abbreviations & Terms**

| Abbreviation | Meaning |
|--------------|---------|
| SRS          | Software Requirements Specification |
| PRD          | Product Requirements Document |
| TSD          | Technical Specification Document |
| ADR          | Architecture Decision Record |
| ERD          | Entity-Relationship Diagram |
| RTM          | Requirements Traceability Matrix |
| CI/CD        | Continuous Integration/Continuous Deployment |
| SLO          | Service Level Objective |
| JTBD         | Jobs To Be Done |
| MVP          | Minimum Viable Product |
| MLP          | Minimum Lovable Product |
| PoC          | Proof of Concept |
| QA           | Quality Assurance |
| UI/UX        | User Interface/User Experience |

### Notes

* **Full matrix:** for regulated/enterprise projects requiring thorough documentation.
* **MVP/MLP path:** for agile/startup environments or initial product versions.

https://github.com/Yousha/PDLC-Phases-Documentation-Matrix/

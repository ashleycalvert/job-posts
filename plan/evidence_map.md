# Evidence Map

This file makes the recommendations traceable without pretending that a subset of job ads is a formal competency framework.

## Dataset cautions

The existing [posting inventory](../analytics/posting_inventory.md) identifies 36 `R-` files, 35 substantive postings, one unusable boilerplate file (`R-0000179438`), and two near-duplicate pairs. Lead and Staff postings often share grade GG07, and stated experience ranges overlap. Therefore:

- role verbs and responsibilities are stronger signals than titles;
- frequency indicates demand, not a universal must-have checklist;
- specialized Staff AI, Staff platform, and people-manager roles should not be collapsed into one impossible profile;
- this development guide targets the common Data Engineering leadership core, with AI-specific capabilities as an optional specialization.

## Strong recurring signals

The [skill-demand matrix](../analytics/skill_demand_matrix.md) reports these corpus-wide signals across 35 substantive XYZ postings:

| Signal | Observed frequency | Implication for development |
|---|---:|---|
| Communication or collaboration | 33/35 (94%) | Clear communication is a baseline delivery capability, not polish added after technical work |
| Data quality, governance, lineage, or metadata | 30/35 (86%) | Trust, auditability, and control must be part of the design |
| Airflow or orchestration concepts | 28/35 (80%) | Workflow behavior, recovery, and operations matter broadly |
| Observability, monitoring, reliability, telemetry, or SRE | 26/35 (74%) | Production operation is part of engineering ownership |
| CI/CD or DevOps | 25/35 (71%) | Repeatable testing and deployment are normal expectations |
| Security, privacy, compliance, identity, or regulation | 25/35 (71%) | Risk and control thinking are essential in a regulated enterprise |
| Stakeholder engagement or business translation | 21/35 (60%) | Senior+ scope requires connecting technical work to business outcomes |
| Documentation or knowledge sharing | 19/35 (54%) | Durable context and enablement create organizational leverage |

Within the supplied role families, all six Lead Data postings mention Python, governance/quality, pipelines, and cloud; five of six mention orchestration, CI/CD, observability/reliability, and security/compliance. All seven Staff Data postings mention observability/reliability; six of seven mention Python and governance/quality. These counts support a production-first, regulated-platform quality bar rather than a tool-only curriculum.

## Lead evidence

| Observed responsibility | Example source evidence | Guide interpretation |
|---|---|---|
| End-to-end data-platform view and stakeholder translation | [R-0000168275](../posts/lead_data_engineer/R-0000168275.md) | Start from outcomes and system boundaries; connect architecture, SMEs, and stewards |
| Hands-on platform ownership and mentoring | [R-0000177488](../posts/lead_data_engineer/R-0000177488.md) | Lead is still a builder, but raises team quality through reviews, pairing, and standards |
| SLAs, retries, idempotency, alerts, HA/DR, incident response, cost | [R-0000177488](../posts/lead_data_engineer/R-0000177488.md) | Functional correctness alone is below the Lead production bar |
| Translate business/control objectives into roadmaps and reusable patterns | [R-0000177488](../posts/lead_data_engineer/R-0000177488.md) | Plans must expose value, controls, sequencing, and dependencies |
| Business relationships, alternative approaches, multiple high-risk projects | [R-0000178974](../posts/lead_data_engineer/R-0000178974.md) | Lead judgment includes prioritization and decisions under uncertainty |
| Independent ownership and delivery | [R-0000179810](../posts/lead_data_engineer/R-0000179810.md) | A lighter Lead variant still requires full ownership, production troubleshooting, and documentation |
| Team-lead experience, best-practice championing, innovation assessment | [R-0000182087](../posts/lead_data_engineer/R-0000182087.md) | A Lead creates delivery mechanisms and evaluates technology against real needs |

## Staff evidence

| Observed responsibility | Example source evidence | Guide interpretation |
|---|---|---|
| Establish platform consumption, storage, and workflow standards | [R-0000163646](../posts/staff_data_engineer/R-0000163646.md) | Staff converts expertise into practices others can apply |
| Lead architectural decisions, present trade-offs, influence without authority | [R-0000169987](../posts/staff_data_engineer/R-0000169987.md) | Staff-level output is decision quality and alignment across boundaries |
| Own complex, cross-cutting initiatives from design through production | [R-0000169987](../posts/staff_data_engineer/R-0000169987.md) | Staff scope crosses platform, security, compliance, developer experience, and operations |
| Set technical direction in real-time telemetry/evaluation | [R-0000177482](../posts/staff_data_engineer/R-0000177482.md) | Deep specialty is valuable when translated into a durable platform direction |
| Set AI-service architecture and software standards | [R-0000178205](../posts/staff_data_engineer/R-0000178205.md) | Staff joins distributed-system depth with standards and integration judgment |
| Build reusable patterns and enable other teams | [R-0000182778](../posts/staff_ai_engineer/R-0000182778.md) | Staff leverage is measured in other teams’ speed and quality, not personal code volume |
| Own ambiguous “good enough” judgments and auditable decisions | [R-0000180926](../posts/staff_ai_engineer/R-0000180926.md) | Make uncertainty and acceptance criteria explicit, especially in governance-sensitive work |
| Builder/product-owner hybrid; validate value with users | [R-0000182936](../posts/staff_ai_engineer/R-0000182936.md) | Technical direction begins with workflow value and includes adoption feedback |

## Senior-to-Lead/Staff progression evidence

The [position analysis](../analytics/job_position_analysis.md) summarizes the most reliable progression dimensions as:

1. prototype to deployed and operated production system;
2. component to workflow/service to domain/platform to enterprise pattern;
3. following patterns to selecting designs to defining standards and resolving cross-organizational trade-offs;
4. personal output to team delivery to reusable organizational leverage;
5. collaboration to mentoring to technical direction and influence.

This guide uses those dimensions as its assessment model. It does not recommend waiting until every technical area is expert-level. It recommends demonstrating safe ownership: recognize the limits of your knowledge, obtain the right expertise, make evidence-based decisions, and remain accountable for the integrated outcome.

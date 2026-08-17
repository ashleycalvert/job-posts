# Skill Demand and Role Matrix

## How to read the counts

Counts represent whether a skill or concept appears at least once in the core description, responsibilities, or requirements of each substantive posting. They do not count repeated mentions. Denominator: 35 substantive postings. The boilerplate-only file is excluded; two near-duplicate pairs remain included because they are separate supplied requisitions.

These are demand signals, not strict must-have counts. A mention may occur in responsibilities, must-have requirements, or nice-to-have requirements. Closely related terms are grouped (for example, “Airflow / orchestration”), so the results are more useful for capability analysis than literal keyword matching.

## Overall technical demand

| Rank | Capability | Postings | Share | Interpretation |
|---:|---|---:|---:|---|
| 1 | Python | 32 | 91% | Near-universal implementation language across data, ML, AI, services, and automation |
| 2 | Data quality, governance, lineage, or metadata | 30 | 86% | Regulated-enterprise trust and traceability are core engineering concerns |
| 3 | Airflow or orchestration concepts | 28 | 80% | Workflow coordination matters across pipelines, ML lifecycle, and agents |
| 4 | ETL/ELT or data pipelines | 26 | 74% | Foundational even in many AI roles |
| 4 | Observability, monitoring, reliability, telemetry, or SRE | 26 | 74% | Production operation is central, not ancillary |
| 6 | AWS | 25 | 71% | Most frequently named cloud; often paired with hybrid or multi-cloud requirements |
| 6 | CI/CD or DevOps | 25 | 71% | Automated testing and deployment are baseline production practices |
| 6 | Security, privacy, compliance, identity, or regulation | 25 | 71% | Particularly strong in platform and AI roles |
| 9 | Data modeling, warehouse, lakehouse, or schema design | 22 | 63% | Core to data roles and still relevant to AI/data product work |
| 9 | ML or model lifecycle | 22 | 63% | Extends well beyond explicitly titled AI roles |
| 11 | SQL or relational databases | 21 | 60% | Essential data foundation, though less explicit in agent/full-stack postings |
| 12 | LLMs or generative AI | 20 | 57% | A majority signal across the mixed corpus |
| 13 | Spark or PySpark | 19 | 54% | Leading distributed processing requirement |
| 13 | Azure | 19 | 54% | Strong second cloud and frequent enterprise/hybrid platform |
| 15 | Snowflake | 18 | 51% | Leading named data platform/warehouse |
| 15 | Containers, Kubernetes, or OpenShift | 18 | 51% | Common production packaging/runtime layer |
| 15 | Agentic AI or agents | 18 | 51% | Half of all supplied roles directly touch agents |
| 18 | APIs, microservices, REST, GraphQL, gRPC, or FastAPI | 16 | 46% | Data and AI capabilities are increasingly exposed as services |
| 18 | Streaming, Kafka, Kinesis, real-time, or event-driven systems | 16 | 46% | Important for real-time data, integration, and agent runtime work |
| 20 | Java | 15 | 43% | Common secondary/backend enterprise language |
| 21 | RAG or vector retrieval | 13 | 37% | Concentrated in AI and hybrid Data/AI roles |
| 21 | Prompt or context engineering | 13 | 37% | An engineering discipline in production agent roles, not merely prompt writing |
| 21 | AI evaluation or guardrails | 13 | 37% | Strong emerging differentiator for senior AI roles |
| 24 | Feature stores or ML data lifecycle | 9 | 26% | Specialized bridge between data engineering and ML production |
| 24 | Databricks or Delta | 9 | 26% | Concentrated in finance data and principal platform work |
| 24 | dbt | 9 | 26% | Concentrated in Senior/Lead data transformation roles |
| 24 | MLOps or LLMOps | 9 | 26% | Often described functionally without using the exact label, so this is conservative |
| 28 | GCP | 8 | 23% | Usually an acceptable third cloud rather than the primary environment |
| 29 | Infrastructure as code or Terraform | 7 | 20% | Stronger in platform, Staff, Principal, and advanced Lead roles |
| 29 | MCP or A2A | 7 | 20% | Highly concentrated in current agentic-AI hiring |
| 29 | Scala | 7 | 20% | Specialized Spark/big-data language |
| 32 | TypeScript/JavaScript/Node.js | 6 | 17% | Concentrated in full-stack AI and platform roles |

## Soft skills and ways of working

| Capability | Postings | Share | Level-sensitive interpretation |
|---|---:|---:|---|
| Communication or collaboration | 33 | 94% | Baseline at all levels; expands from team coordination to executive influence |
| Stakeholder engagement or business translation | 21 | 60% | Strong indicator of Senior+ scope and especially Lead/Staff/Director roles |
| Agile, adaptability, learning agility, or comfort with ambiguity | 21 | 60% | Important because tools and requirements evolve quickly |
| Documentation or knowledge sharing | 19 | 54% | Supports auditability, operations, reuse, and team enablement |
| Explicit problem solving, analytical, or critical thinking | 14 | 40% | Often assumed elsewhere; prominent in data leads and strategic roles |
| Explicit technical leadership/direction | 12 | 34% | Concentrated at Lead, Staff, Principal, and Director levels |
| Mentoring or coaching | 11 | 31% | Usually an IC leadership signal; only some roles imply direct reports |
| Ownership, accountability, or independent delivery | 11 | 31% | Becomes increasingly important from Senior upward |

The explicit counts understate implicit expectations. For example, every Staff/Principal role entails problem solving and ownership even if the exact words are absent.

## Capability concentration by role family

Each cell shows postings mentioning the capability divided by substantive postings in that supplied family.

| Family | Python | Data governance / quality | Orchestration | Pipelines / ETL | Cloud (AWS or Azure) | CI/CD / DevOps | Observability / reliability | LLM / GenAI | Agents | RAG / vector | Security / compliance |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Data Engineer (n=1) | 0/1 | 1/1 | 1/1 | 1/1 | 0/1 | 1/1 | 1/1 | 0/1 | 1/1 | 0/1 | 0/1 |
| AI Engineer (n=2) | 2/2 | 1/2 | 2/2 | 1/2 | 1/2 | 2/2 | 2/2 | 2/2 | 2/2 | 2/2 | 2/2 |
| Senior Data (n=7) | 6/7 | 6/7 | 5/7 | 7/7 | 6/7 | 4/7 | 2/7 | 3/7 | 2/7 | 1/7 | 3/7 |
| Senior AI (n=2) | 2/2 | 1/2 | 2/2 | 2/2 | 2/2 | 1/2 | 2/2 | 2/2 | 1/2 | 1/2 | 2/2 |
| Lead Data (n=6) | 6/6 | 6/6 | 5/6 | 6/6 | 6/6 | 5/6 | 5/6 | 1/6 | 1/6 | 0/6 | 5/6 |
| Staff Data (n=7) | 6/7 | 6/7 | 5/7 | 4/7 | 3/7 | 5/7 | 7/7 | 4/7 | 4/7 | 2/7 | 3/7 |
| Staff AI (n=7) | 7/7 | 6/7 | 7/7 | 3/7 | 6/7 | 5/7 | 5/7 | 7/7 | 6/7 | 6/7 | 7/7 |
| Principal Data (n=1) | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 1/1 |
| Principal AI (n=1) | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 |
| Director Data (n=1) | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 1/1 | 0/1 | 0/1 | 0/1 | 1/1 |

“Cloud” in the matrix is deliberately limited to explicit AWS or Azure mentions. A zero can therefore mean cloud was not named, not that the role is non-cloud. Likewise, the Director posting discusses integration and big-data technologies without using the exact ETL/pipeline grouping in its core text.

## Position-specific skill priorities

### Data Engineer

Prioritize data modeling, distributed systems, storage performance, batch/streaming pipelines, SQL/databases, production coding, DataOps/MLOps, feature stores, monitoring, and ML lifecycle awareness. Leadership is collaborative rather than organizational.

### AI Engineer

Prioritize production Python/TypeScript, agent orchestration, RAG/retrieval, knowledge management, CI/CD, governance, auditability, failure recovery, and secure integration. Security-focused roles add vector databases, Spark/Airflow, Kubernetes, threat controls, and regulatory standards.

### Senior Data Engineer

Prioritize advanced Python/SQL, ETL/ELT, data modeling, Snowflake, Spark/Databricks, Airflow/dbt, cloud, data quality/lineage, and production troubleshooting. Demonstrate end-to-end ownership and the ability to translate requirements into scalable designs.

### Senior AI Engineer

Prioritize deployed ML/LLM applications, model and data pipelines, evaluation and drift/fairness monitoring, MLOps/SRE, APIs, cloud/containers, and cross-functional delivery. Some roles require true full-stack capability through an executive-facing UI.

### Lead Data Engineer

Prioritize Python/SQL, AWS, Snowflake, Spark, Airflow, dbt, architecture, CI/CD, governance, performance/cost tuning, HA/DR, security, incident response, and stakeholder alignment. Evidence of technical direction and mentoring matters as much as tool breadth.

### Staff Data Engineer

Priorities vary by specialization, but the common bar is distributed-system and platform judgment, observability/reliability, secure APIs/services, governance, automation, and reusable architecture. Deep niches include Snowflake platform control planes, agent telemetry/evaluation runtime, Data/AI pipelines, and AI service hosting.

### Staff AI Engineer

Prioritize agent architecture, orchestration, tool use, memory/context, RAG, MCP, evaluation, guardrails, Python, APIs, containers, CI/CD, observability, and responsible AI. Strong candidates also show enablement, technical direction, and clear decisions under ambiguity. Full-stack and people-management depth are requisition-specific.

### Principal Data Engineer

Prioritize exceptional Spark/Databricks depth: Delta Lake, Unity Catalog, structured streaming, Spark performance tuning, MLflow/Feature Store/Model Serving, cloud infrastructure, CI/CD, POC leadership, cost optimization, and mandatory platform certifications.

### Principal AI Engineer

Prioritize systems breadth and synthesis: data architecture, agentic AI, RAG, evaluation, observability, backend services, secure runtime controls, DataOps/MLOps/LLMOps, reference architectures, and organizational reuse.

### Director Data Engineer

Prioritize business/data strategy, people leadership, executive storytelling, project portfolio direction, finance-domain understanding, analytical rigor, and enough hands-on fluency in SQL/Python/Spark/Snowflake/Databricks to guide teams credibly.

## Most valuable cross-role skill bundles

### Universal production data/AI engineer bundle

- Python, SQL, data structures and software design fundamentals
- Testing, version control, code review, CI/CD
- Data pipelines and orchestration
- Cloud and containers
- Data quality, lineage, governance, and security
- Monitoring, reliability, troubleshooting, and performance
- Communication and business-requirement translation

### Modern data platform bundle

- Spark/PySpark, Snowflake and/or Databricks
- Airflow and dbt
- AWS/Azure data services
- Batch, incremental, streaming, schema evolution, SCD/CDC
- Medallion/lakehouse and warehouse modeling
- Cost/performance tuning, HA/DR, IAM/secrets
- IaC, CI/CD, data-contract testing, observability

### Production agentic-AI bundle

- Strong production Python and backend/API design
- LLM application patterns, structured outputs, tool calling, orchestration
- RAG, embeddings, vector retrieval, chunking/reranking/grounding
- MCP and emerging multi-agent integration patterns
- Evaluation datasets/harnesses, prompt versioning, guardrails
- Tracing, telemetry, quality/latency/cost monitoring
- Authentication, privacy, responsible AI, fallback and human escalation

### Senior technical leadership bundle

- Architecture trade-off judgment
- End-to-end production accountability
- Standards, design/code reviews, documentation, and reusable components
- Mentoring and cross-team enablement
- Stakeholder alignment and technical storytelling
- Ownership of ambiguity, risk, delivery, and operational outcomes

## Demand interpretation

The highest-value profile is “T-shaped”: deep expertise in a primary domain plus credible production breadth. A data specialist gains value by understanding ML/AI serving and governance; an AI specialist gains value by understanding data pipelines, APIs, cloud runtime, security, and observability. At higher levels, tool count matters less than evidence that the candidate can make durable trade-offs and create leverage for multiple teams.

# Posting Inventory and Normalization Notes

This inventory accounts for every source file. “Normalized title” uses the visible title when present; where the file begins only with `Job Description`, the role is inferred from its body and supplied folder. “Experience” captures explicit numeric thresholds only. Missing means the source does not provide the field in the retained file.

## Data and AI Engineer postings

| Requisition | Supplied family | Normalized title | Grade | Explicit experience | Primary specialization | Notes |
|---|---|---|---|---|---|---|
| R-0000179728 | Data Engineer | Data/AI Engineer | GG08 | Not stated | AI data foundation, pipelines, feature stores, DataOps/MLOps | Substantive |
| R-0000174231 | AI Engineer | AI Engineer (Global Security) | GG08 | 2–5 years software; 2+ years ML/data science/AI | Security agents, RAG, context pipelines, controls | Substantive |
| R-0000182512 | AI Engineer | AI Engineer – AI Platform Engineering | GG07 | Not stated | Agent orchestration platform, knowledge/retrieval, governance/distribution | Substantive; title/grade illustrate overlap |

## Senior postings

| Requisition | Supplied family | Normalized title | Grade | Explicit experience | Primary specialization | Notes |
|---|---|---|---|---|---|---|
| R-0000159454 | Senior Data Engineer | Senior Data Engineer (Market Risk) | Missing | 5+ years Java/Scala and backend; 3+ big-data tools | Java/Spring backend, Spark/Hadoop/cloud data stores | Title inferred from body/folder; substantive but metadata section absent |
| R-0000164266 | Senior Data Engineer | Data Engineer (enterprise ETL) | Missing | 3–6 years data engineering/ETL | Informatica IICS, dbt, SQL, enterprise warehouse | Visible body says Data Engineer; supplied folder says Senior; metadata absent |
| R-0000174420 | Senior Data Engineer | Senior Data Engineer (HR data hub) | GG08 | 5–8 years SDLC/data; 5+ cloud ETL | Snowflake, Python/SQL, ETL, APIs, cloud platform | Substantive |
| R-0000179438 | Senior Data Engineer | Unknown | Missing | Unknown | Unknown | **Unusable:** only generic employer/talent-community boilerplate; no role description |
| R-0000179445 | Senior Data Engineer | Senior Data Engineer (Finance Data Platform) | GG07 | 5+ total; 2–3 years Spark/big data/Databricks/Airflow/dbt | Databricks, Airflow, dbt, Cloudera, finance data | Substantive |
| R-0000179775 | Senior Data Engineer | Senior Data Engineer (Insurance Data/Analytics) | GG08 | 3+ years SQL and Python | ETL/ELT, Snowflake, Airflow, enterprise analytics | Exact title inferred from folder; substantive |
| R-0000182096 | Senior Data Engineer | Senior Data Engineer (ML feature store) | GG08 | 4+ years programming/full-stack | Feature store, PySpark, MLOps, data governance | Exact title inferred from folder; substantive |
| R-0000182756 | Senior Data Engineer | Data Engineer (Wealth Data & AI) | GG08 | 2+ years data engineering | ETL, APIs, SQL/NoSQL, GenAI/prompt engineering support | Body uses Data Engineer despite Senior folder |
| R-0000179745 | Senior AI Engineer | Senior AI Engineer | GG07 | 2+ years hands-on model development | ML/NLP, MLOps, deployment, Airflow/SageMaker, SRE | Substantive |
| R-0000184043 | Senior AI Engineer | Senior AI Engineer | GG08 | 4+ years full-stack production applications | Agent evaluation, LLM-as-judge, APIs, dashboards, data pipelines | Substantive; role explicitly works with Lead/Staff on hardest decisions |

## Lead postings

| Requisition | Supplied family | Normalized title | Grade | Explicit experience | Primary specialization | Notes |
|---|---|---|---|---|---|---|
| R-0000168275 | Lead Data Engineer | Lead Data Engineer (Finance DaaS) | GG07 | 7+ years data engineering; 3+ integration/data/cloud architecture | Finance data platform, lakehouse, governance, cloud migration | Title taken from body |
| R-0000170663 | Lead Data Engineer | Lead Data Engineer | Missing | 3+ years data/software engineering | Unified pipelines, AWS, Spark/Airflow/dbt, AI automation | Metadata absent; relatively low tenure threshold for Lead |
| R-0000177488 | Lead Data Engineer | Lead Data Platform Engineer (AML) | GG07 | 7+ years | AWS platform, Snowflake, Spark, dbt, medallion, HA/DR | Senior IC/technical lead; explicitly 70–80% hands-on |
| R-0000178974 | Lead Data Engineer | Snowflake Lead Data Engineer | GG07 | 5+ years data engineering | Snowflake lakehouse, performance/cost, team leadership | Substantive |
| R-0000179810 | Lead Data Engineer | Lead Data Engineer | GG07 | 3+ years | Python/PySpark, SQL, AWS, Snowflake, dbt, Airflow | Exact title inferred from body/folder; delivery-oriented Lead variant |
| R-0000182087 | Lead Data Engineer | Lead Data Engineer (ML feature store) | GG07 | 8+ years; 3+ years team lead/similar | Feature store, PySpark, MLOps, full-stack/DevOps | Exact title inferred from supplied family and leadership requirements |

## Staff postings

| Requisition | Supplied family | Normalized title | Grade | Explicit experience | Primary specialization | Notes |
|---|---|---|---|---|---|---|
| R-0000163646 | Staff Data Engineer | Staff, Data Engineer (Global Security) | GG07 | Not stated | Snowflake ETL/ELT, Python/Airflow, governance/performance | Substantive |
| R-0000169632 | Staff Data Engineer | Staff Data/AI Engineer | GG07 | 5+ years | Data/ML pipelines, LLM/RAG/agents, DataOps/MLOps | Near-duplicate of R-0000175418; asks for master's degree |
| R-0000169987 | Staff Data Engineer | Staff Data Platform Engineer – Snowflake | GG07 | 7+ years platform/data/cloud/SRE; 3+ Snowflake | Snowflake control plane, multi-cloud security, responsible AI | Deep platform/security specialization |
| R-0000175418 | Staff Data Engineer | Staff Data/AI Engineer | GG07 | 5+ years | Data/ML pipelines, LLM/RAG/agents, DataOps/MLOps | Near-duplicate of R-0000169632; asks for bachelor's degree |
| R-0000175442 | Staff Data Engineer | Staff Data/AI Engineer | Missing | 3+ years | Next Best Action pipelines, feature stores, agents, ML lifecycle | Metadata absent; relatively low threshold for Staff |
| R-0000177482 | Staff Data Engineer | Staff AI Engineer | GG07 | 8+ years software/platform; 5+ SRE/realtime/observability | Agent trace ingestion, live evaluation, OpenTelemetry, guardrails | Supplied under Staff Data but visible title is Staff AI |
| R-0000178205 | Staff Data Engineer | Staff Software Engineer | GG07 | Not stated | Distributed AI services, APIs, hybrid cloud, model serving | Supplied under Staff Data but visible title is Staff Software |
| R-0000175710 | Staff AI Engineer | Staff Engineer — Agentic AI | GG07 | 5–8 years software; 1–3 years agentic AI/LLMs | MCP, RAG, orchestration, LoB implementation/enablement | 99.7% textual match to R-0000175847 |
| R-0000175847 | Staff AI Engineer | Staff Engineer – Agentic AI | GG07 | 5–8 years software; 1–3 years agentic AI/LLMs | MCP, RAG, orchestration, LoB implementation/enablement | 99.7% textual match to R-0000175710 |
| R-0000179592 | Staff AI Engineer | Senior Lead AI Application Engineer (Global Security) | GG07 | 5+ years full-stack production systems | Full-stack multi-agent apps, DevSecOps, APIs, observability | Visible title differs from supplied family; deep security/platform role |
| R-0000180926 | Staff AI Engineer | Staff AI Engineer | GG07 | 7+ years full-stack production applications | Agent evaluation, LLM-as-judge, full-stack dashboards/services | Staff counterpart to Senior AI R-0000184043 with greater independence |
| R-0000181724 | Staff AI Engineer | Staff ML Engineer | GG07 | 7+ years ML; 3+ leadership/mentorship | ML strategy, deployment, MLOps, formal team management | Explicit hiring, evaluation, career-development responsibilities |
| R-0000182778 | Staff AI Engineer | Staff AI Engineer | GG07 | 5–8 years software; 1–3 years production LLM/GenAI | Production agents, MCP, RAG, evaluation, enablement | Explicitly excludes POC-only experience |
| R-0000182936 | Staff AI Engineer | Lead Agentic AI Engineer | GG07 | 8–10 years total; 2–3+ agentic/LLM | Product-owner/builder, multi-agent workflows, RAG, Context Engineer management | Visible title differs from supplied Staff family |

## Principal and Director postings

| Requisition | Supplied family | Normalized title | Grade | Explicit experience | Primary specialization | Notes |
|---|---|---|---|---|---|---|
| R-0000173724 | Principal Data Engineer | Associate Director, Principal Data Engineer | GG07 | 8+ years production Spark/Databricks | Databricks/Spark solution architecture, POC-to-production, ML engineering | Two Databricks certifications are mandatory |
| R-0000167546 | Principal AI Engineer | Principal AI Engineer | GG06 | 10+ years software engineering | Enterprise data/agent/RAG/service reference architecture | Source body once misspells “Principle”; normalized to visible title |
| R-0000172230 | Director Data Engineer | Director, Data Engineer – Subledger Integration | GG06 | 7+ years analytics/data-driven work | People leadership, finance data integration, analytics strategy | Strongest formal people/portfolio leadership role |

## Data-quality findings

- Total files: **36**.
- Substantive postings: **35**.
- Boilerplate-only/unusable: **1** (`R-0000179438`).
- Substantive postings missing a grade: **4** (`R-0000170663`, `R-0000159454`, `R-0000164266`, `R-0000175442`). The unusable file also lacks a grade, making five grade-missing files in total.
- Near-duplicate substantive pairs: **2 pairs / 4 files**.
- Multiple folder/title mismatches exist, especially around Senior, Staff, Lead, AI, and Software Engineer labels.
- Experience requirements are not present in every posting and cannot be safely inferred from grade alone.

These limitations are why the main analysis treats role scope and stated responsibilities as stronger evidence than folder name, visible title, or grade in isolation.

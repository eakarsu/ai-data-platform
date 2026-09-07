# Feature status — AI agents, data & model operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 449 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 3 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 2 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 5 | 0 | Native records/view |
| Reports & analytics | report | 9 | 0 | Native records/view |
| Activity & audit trail | audit | 13 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Enterprise agent testing sandbox work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Memories | records | 1 | 0 | Native records/view |
| Subjects | records | 1 | 0 | Native records/view |
| Projections | records | 1 | 0 | Native records/view |
| Extractors | records | 1 | 0 | Native records/view |
| Retention Policies | records | 1 | 0 | Native records/view |
| AI · Insert Memory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Natural-Language Recall | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Time-Travel Query | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Contradiction Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Summary Rollup | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Extractor Tuner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Embedding Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subject browser | records | 1 | 0 | Native records/view |
| Time slider | records | 1 | 0 | Native records/view |
| Conflict resolve | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Relevance score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Importance score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Memory consolidate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rag chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pii redact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Memory graph extract | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Decay policy recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Semantic search | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cross agent share advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention dry run | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Auto merge advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pinned | records | 1 | 0 | Native records/view |
| Eval harness | records | 1 | 0 | Native records/view |
| Drift | records | 3 | 0 | Native records/view |
| Cost | records | 2 | 0 | Native records/view |
| Replay | records | 1 | 0 | Native records/view |
| Jobs | records | 1 | 0 | Native records/view |
| Knowledge graph | records | 1 | 0 | Native records/view |
| Acl | records | 1 | 0 | Native records/view |
| Memory conflicts | records | 1 | 0 | Native records/view |
| Traces | records | 1 | 0 | Native records/view |
| Prompts | records | 1 | 0 | Native records/view |
| Evals | records | 1 | 0 | Native records/view |
| Alerts | records | 3 | 0 | Native records/view |
| Prompt Versions | records | 1 | 0 | Native records/view |
| Eval Results | records | 1 | 0 | Native records/view |
| API Keys | records | 5 | 0 | Native records/view |
| AI · Regression Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Auto RCA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Drift Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anomaly Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Prompt Diff Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Cost Anomaly Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Eval Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Judge Calibrator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trace viewer | records | 1 | 0 | Native records/view |
| Otlp ingest | records | 1 | 0 | Native records/view |
| Blast radius | records | 1 | 0 | Native records/view |
| Production controls | records | 2 | 0 | Native records/view |
| Agent portfolio | records | 1 | 0 | Native records/view |
| Images | records | 1 | 0 | Native records/view |
| AI Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Hub | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Prior Studies | records | 1 | 0 | Native records/view |
| Appointments | records | 1 | 0 | Native records/view |
| Patients | records | 1 | 0 | Native records/view |
| Referring Docs | records | 1 | 0 | Native records/view |
| Radiologists | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Users | records | 4 | 0 | Native records/view |
| Report Templating | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prior Study Comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Turnaround Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incidental Findings | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| QA Audit (A vs B) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Pre-Auth | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient Portal Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Critical findings queue | records | 1 | 0 | Native records/view |
| Data Sources | records | 2 | 0 | Native records/view |
| Dashboards | records | 1 | 0 | Native records/view |
| AI Insights | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Queries | records | 1 | 0 | Native records/view |
| Query Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Log Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dashboard Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data Quality | records | 2 | 0 | Native records/view |
| Narratives | records | 1 | 0 | Native records/view |
| Pipeline Builder | records | 1 | 0 | Native records/view |
| AI Features (New) | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomalies | records | 1 | 0 | Native records/view |
| Exports | records | 3 | 0 | Native records/view |
| Scheduled Jobs | records | 1 | 0 | Native records/view |
| AI Assistant | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Data Explorer | records | 1 | 0 | Native records/view |
| Team | records | 3 | 0 | Native records/view |
| Ingestion Connectors | integration | 1 | 0 | Provider request records only |
| Parquet / Iceberg | records | 1 | 0 | Native records/view |
| Query Engine | records | 1 | 0 | Native records/view |
| dbt Transforms | records | 1 | 0 | Native records/view |
| Semantic Layer | records | 1 | 0 | Native records/view |
| Data Lineage | records | 1 | 0 | Native records/view |
| Access Policies | records | 1 | 0 | Native records/view |
| Materialized Views | records | 1 | 0 | Native records/view |
| Cell Grid | records | 1 | 0 | Native records/view |
| Formula Engine | records | 1 | 0 | Native records/view |
| AI Fill Down | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NL Formula | records | 1 | 0 | Native records/view |
| Pivot Engine | records | 1 | 0 | Native records/view |
| Charts API | records | 1 | 0 | Native records/view |
| Collab Presence | records | 1 | 0 | Native records/view |
| Cohort Comparison | records | 1 | 0 | Native records/view |
| Schema Advisor | records | 1 | 0 | Native records/view |
| Data Governance Crawler | records | 1 | 0 | Native records/view |
| Multi-Source Merger | records | 1 | 0 | Native records/view |
| Auto Alert Rules | records | 1 | 0 | Native records/view |
| Data Lineage Tracker | records | 1 | 0 | Native records/view |
| Query Cost Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forecast Accuracy Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SQL from Intent | records | 1 | 0 | Native records/view |
| Suggest Visualizations | records | 1 | 0 | Native records/view |
| Detect Anomalies | records | 1 | 0 | Native records/view |
| Semantic metric drift | records | 1 | 0 | Native records/view |
| Agentic sql query generation | records | 1 | 0 | Native records/view |
| Automated insights generation | records | 1 | 0 | Native records/view |
| Predictive analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data quality automation | records | 1 | 0 | Native records/view |
| Dashboard generation from intent | records | 1 | 0 | Native records/view |
| Missing query builder generate dashboard analyze data predic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No database connectors sql nosql cloud data warehouses only | integration | 1 | 0 | Provider request records only |
| No real time data streaming | records | 1 | 0 | Native records/view |
| No data quality monitoring engine | records | 1 | 0 | Native records/view |
| No advanced visualization library plotly d3 deck gl on backe | records | 1 | 0 | Native records/view |
| No sms notification | records | 1 | 0 | Native records/view |
| Datasets | records | 2 | 0 | Native records/view |
| Labels | records | 1 | 0 | Native records/view |
| Annotations | records | 1 | 0 | Native records/view |
| Auto Label | records | 2 | 0 | Native records/view |
| Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Services | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Guidelines | records | 1 | 0 | Native records/view |
| Comments | records | 3 | 0 | Native records/view |
| Data Imports | records | 1 | 0 | Native records/view |
| Quality | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tags | records | 4 | 0 | Native records/view |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Activity Feed | records | 1 | 0 | Native records/view |
| Saved Filters | records | 1 | 0 | Native records/view |
| Schema Drift | records | 1 | 0 | Native records/view |
| Conflict resolver | records | 1 | 0 | Native records/view |
| Results | records | 2 | 0 | Native records/view |
| Recommend label strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labeler quality score | records | 1 | 0 | Native records/view |
| Active learning engine | records | 1 | 0 | Native records/view |
| Crowd consensus conflict resolution | records | 1 | 0 | Native records/view |
| Label quality prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Semantic similarity clustering | records | 1 | 0 | Native records/view |
| Labeler quality scoring | records | 1 | 0 | Native records/view |
| Missing auto label suggest labels detect disagreement identi | records | 1 | 0 | Native records/view |
| No dataset management or versioning surface | records | 1 | 0 | Native records/view |
| No user labeler management and quality control workflows | records | 1 | 0 | Native records/view |
| No label schema definition and validation engine | records | 1 | 0 | Native records/view |
| No integration with ml training pipelines | integration | 1 | 0 | Provider request records only |
| No payment billing module | records | 1 | 0 | Native records/view |
| No calendar integration | integration | 1 | 0 | Provider request records only |
| Favorites | records | 3 | 0 | Native records/view |
| Fine-Tuning Jobs | records | 1 | 0 | Native records/view |
| Base Models | records | 1 | 0 | Native records/view |
| Custom Models | records | 1 | 0 | Native records/view |
| Evaluations | records | 3 | 0 | Native records/view |
| Training Configs | records | 1 | 0 | Native records/view |
| Model Comparisons | records | 1 | 0 | Native records/view |
| Prompt Templates | records | 3 | 0 | Native records/view |
| Deployments | records | 2 | 0 | Native records/view |
| Inference Playground | records | 1 | 0 | Native records/view |
| Bayesian HP Search | records | 1 | 0 | Native records/view |
| Prompt A/B Tester | records | 1 | 0 | Native records/view |
| Deployment Templates | records | 1 | 0 | Native records/view |
| Model Marketplace | records | 1 | 0 | Native records/view |
| Hugging Face Hub | records | 1 | 0 | Native records/view |
| Data Pipelines | records | 1 | 0 | Native records/view |
| Scheduled Tasks | records | 1 | 0 | Native records/view |
| Dataset Leakage | records | 1 | 0 | Native records/view |
| Team Management | records | 1 | 0 | Native records/view |
| Cost Estimator | records | 1 | 0 | Native records/view |
| Usage & Billing | records | 1 | 0 | Native records/view |
| Export Data | records | 1 | 0 | Native records/view |
| Backups | records | 1 | 0 | Native records/view |
| Admin Settings | records | 1 | 0 | Native records/view |
| Indexed Sources | records | 1 | 0 | Native records/view |
| Scheduled Macros | records | 1 | 0 | Native records/view |
| Agent Runs | records | 1 | 0 | Native records/view |
| On-Device Models | records | 1 | 0 | Native records/view |
| Privacy Audit | records | 1 | 0 | Native records/view |
| File Index | records | 1 | 0 | Native records/view |
| AI · Plan Local Task | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Semantic File Search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Define Scheduled Macro | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Draft Email Reply | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weekly Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Privacy Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Model Router | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Conflict Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Daily Digest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Macro scheduler | records | 1 | 0 | Native records/view |
| Local fallback orchestrator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conflict auto resolver | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rag rerank planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prompt redaction rewriter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crdt | records | 1 | 0 | Native records/view |
| Encrypted store | records | 1 | 0 | Native records/view |
| Plugins | records | 1 | 0 | Native records/view |
| Capabilities | records | 1 | 0 | Native records/view |
| Outbox | records | 1 | 0 | Native records/view |
| Sync oplog | records | 1 | 0 | Native records/view |
| Privacy budget | records | 1 | 0 | Native records/view |
| Model cache | records | 1 | 0 | Native records/view |
| Conflict provenance timeline | records | 1 | 0 | Native records/view |
| Products | records | 2 | 0 | Native records/view |
| Vendors | records | 2 | 0 | Native records/view |
| Categories | records | 3 | 0 | Native records/view |
| Duplicates | records | 2 | 0 | Native records/view |
| Merge History | records | 1 | 0 | Native records/view |
| Price Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk Imports | records | 1 | 0 | Native records/view |
| Detect Duplicates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Merge Rules Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pricing Trend Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Description Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Category Suggestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data Quality Reports | records | 1 | 0 | Native records/view |
| Golden record confidence | records | 1 | 0 | Native records/view |
| Cost Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage Monitoring | records | 1 | 0 | Native records/view |
| Model Benchmarks | records | 1 | 0 | Native records/view |
| Token Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Team Reports | records | 1 | 0 | Native records/view |
| Routing Rules | records | 1 | 0 | Native records/view |
| Budget Alerts | records | 1 | 0 | Native records/view |
| A/B Testing | records | 1 | 0 | Native records/view |
| Optimizations | records | 1 | 0 | Native records/view |
| Cost Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| LLM Proxy Tester | records | 1 | 0 | Native records/view |
| AI Results History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Model Registry | records | 1 | 0 | Native records/view |
| Prompt Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cache Management | records | 1 | 0 | Native records/view |
| Rate Limiting | records | 1 | 0 | Native records/view |
| Cost Allocation | records | 1 | 0 | Native records/view |
| Cost Anomaly Detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Model Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prompt Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stripe Billing Plan (NEEDS-CREDS) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OpenAI Cost Arbitrage (NEEDS-CREDS) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anthropic Cost Arbitrage (NEEDS-CREDS) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AWS Bedrock Arbitrage (NEEDS-CREDS) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alert Webhook (NEEDS-CREDS) | integration | 1 | 0 | Provider request records only |
| Register Custom Model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Record Latency Sample | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Record Error Event | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sla cost guardrail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergent behavior heatmap | records | 1 | 0 | Native records/view |
| Performance | records | 1 | 0 | Native records/view |
| Hallucinations | records | 1 | 0 | Native records/view |
| Prompt injection | records | 1 | 0 | Native records/view |
| llm cost latency dashboards | records | 1 | 0 | Native records/view |
| prompt regression detector | records | 1 | 0 | Native records/view |
| trace replay | records | 1 | 0 | Native records/view |
| eval harness integration | integration | 1 | 0 | Provider request records only |
| opentelemetry compatibility | records | 1 | 0 | Native records/view |
| explicit anomaly | records | 1 | 0 | Native records/view |
| root | records | 1 | 0 | Native records/view |
| authentication or rbac layer visible | records | 1 | 0 | Native records/view |
| billing usage metering | records | 1 | 0 | Native records/view |
| webhooks for alert delivery slack pagerduty | integration | 1 | 0 | Provider request records only |
| retention archival policies for telemetry | records | 1 | 0 | Native records/view |
| limited integrations only own sdk no opentelemetry | integration | 1 | 0 | Provider request records only |
| Customer Management | records | 1 | 0 | Native records/view |
| Data Residency Zones | records | 1 | 0 | Native records/view |
| Support Tickets | records | 1 | 0 | Native records/view |
| Network Infrastructure | records | 1 | 0 | Native records/view |
| SIM Card Management | records | 1 | 0 | Native records/view |
| Roaming Agreements | records | 1 | 0 | Native records/view |
| Regulatory Compliance | records | 1 | 0 | Native records/view |
| AI Real-Time Translation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Support Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Intent Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Compliance Reports | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Anomaly Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Churn Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roaming Consortium Advisor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| autonomous network optimization | records | 1 | 0 | Native records/view |
| multilingual support agent | records | 1 | 0 | Native records/view |
| compliance automation | records | 1 | 0 | Native records/view |
| existing stub files sentiment intentdetection tran | records | 1 | 0 | Native records/view |
| network monitoring without network | records | 1 | 0 | Native records/view |
| billing without cost | records | 1 | 0 | Native records/view |
| customers without churn | records | 1 | 0 | Native records/view |
| real | records | 1 | 0 | Native records/view |
| sla tracking and breach alerting | records | 1 | 0 | Native records/view |
| automated billing dispute resolution | records | 1 | 0 | Native records/view |
| limited customer self | records | 1 | 0 | Native records/view |
| integrations with major cloud providers aws azu | integration | 1 | 0 | Provider request records only |
| webhooks for external system events | integration | 1 | 0 | Provider request records only |
| file upload for invoice contract docs | records | 1 | 0 | Native records/view |
| Backlog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Connectors | integration | 1 | 0 | Provider request records only |
| App Consents | records | 1 | 0 | Native records/view |
| Disclosure Log | records | 1 | 0 | Native records/view |
| MCP Clients | records | 1 | 0 | Native records/view |
| Schemas | records | 1 | 0 | Native records/view |
| Redaction Rules | records | 1 | 0 | Native records/view |
| AI · Answer App Query | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Consent Policy Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Redaction Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Privacy Risk Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Intent Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Schema Extractor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consent center | records | 1 | 0 | Native records/view |
| Mcp server config | records | 1 | 0 | Native records/view |
| Context summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Relevance scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Query rewriter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conflict detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dp budgets | records | 1 | 0 | Native records/view |
| Share graph | records | 1 | 0 | Native records/view |
| Recall and forget | records | 1 | 0 | Native records/view |
| Context bundle | records | 1 | 0 | Native records/view |
| Mcp rpc console | records | 1 | 0 | Native records/view |
| Disclosure simulator | records | 1 | 0 | Native records/view |
| Versions | records | 1 | 0 | Native records/view |
| A/B Tests | records | 1 | 0 | Native records/view |
| Optimization | records | 1 | 0 | Native records/view |
| Playground | records | 2 | 0 | Native records/view |
| Chains | records | 1 | 0 | Native records/view |
| Library | records | 1 | 0 | Native records/view |
| Variables | records | 1 | 0 | Native records/view |
| Teams | records | 1 | 0 | Native records/view |
| Cost Tracking | records | 1 | 0 | Native records/view |
| Folders | records | 1 | 0 | Native records/view |
| Snippets | records | 1 | 0 | Native records/view |
| Trash | records | 1 | 0 | Native records/view |
| Ab test runner | records | 1 | 0 | Native records/view |
| Security scanner | records | 1 | 0 | Native records/view |
| Pii checker | records | 1 | 0 | Native records/view |
| Deployment manager | records | 1 | 0 | Native records/view |
| Version history | records | 1 | 0 | Native records/view |
| Template library | records | 1 | 0 | Native records/view |
| Classify prompt | records | 1 | 0 | Native records/view |
| regression test suite for prompts | records | 1 | 0 | Native records/view |
| modelspecific prompt compilation | records | 1 | 0 | Native records/view |
| cost prediction by volume | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| prompt lineage graph | records | 1 | 0 | Native records/view |
| ab test marketplace | records | 1 | 0 | Native records/view |
| agentic prompt refinement | records | 1 | 0 | Native records/view |
| ai prompt classification autotag by domai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multilanguage prompt translation | records | 1 | 0 | Native records/view |
| ai piiinjection security scanning ui stub | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai regression testing against golden outp | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai modelspecific prompt rewriter claude v | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| public prompt marketplace discovery forki | records | 1 | 0 | Native records/view |
| production model registry beyond deployme | records | 1 | 0 | Native records/view |
| limited realtime collaborative editing no cr | records | 1 | 0 | Native records/view |
| gitstyle visual diff for prompt versions | records | 1 | 0 | Native records/view |
| ssoenterprise auth provider integration | integration | 1 | 0 | Provider request records only |
| Knowledge Base | records | 1 | 0 | Native records/view |
| AI Summaries | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workspaces | records | 1 | 0 | Native records/view |
| Platform Ops | records | 1 | 0 | Native records/view |
| System Chat | records | 1 | 0 | Native records/view |
| multisource rag | records | 1 | 0 | Native records/view |
| conversational document analyst | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| comparison contradiction detection | records | 1 | 0 | Native records/view |
| knowledge graph extraction | records | 1 | 0 | Native records/view |
| citation source tracking | records | 1 | 0 | Native records/view |
| realtime document monitoring | records | 1 | 0 | Native records/view |
| explicit embed ingestion route exposed | records | 1 | 0 | Native records/view |
| summarize collectionlevel overview | records | 1 | 0 | Native records/view |
| recommendsources crossdocument discovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multisource rag apis dbs live web | records | 1 | 0 | Native records/view |
| contradictiondetection across docs | records | 1 | 0 | Native records/view |
| citationprovenance route | records | 1 | 0 | Native records/view |
| teamlevel access control role permissions | records | 1 | 0 | Native records/view |
| public webhookintegration system | integration | 1 | 0 | Provider request records only |
| bulk import s3 google drive sharepoint co | records | 1 | 0 | Native records/view |
| notification system | records | 1 | 0 | Native records/view |
| audit log of who queried what | records | 1 | 0 | Native records/view |
| exportshare workflow | records | 1 | 0 | Native records/view |
| Schema builder | records | 1 | 0 | Native records/view |
| Streaming | records | 1 | 0 | Native records/view |
| Schema infer | records | 1 | 0 | Native records/view |
| Redact pii | records | 1 | 0 | Native records/view |
| Distribution preserve | records | 1 | 0 | Native records/view |
| Edge cases | records | 1 | 0 | Native records/view |
| llm powered schema inference auto detecting schema from sample data | records | 1 | 0 | Native records/view |
| distribution learning capturing statistical properties from real data | records | 1 | 0 | Native records/view |
| differential privacy synthesis to prevent re identification | records | 1 | 0 | Native records/view |
| relational data generation respecting foreign keys and cardinality | records | 1 | 0 | Native records/view |
| targeted edge case and outlier generation for testing | records | 1 | 0 | Native records/view |
| domain specific generators healthcare finance with regulatory presets | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| synthetic data generation engine endpoint | records | 1 | 0 | Native records/view |
| schema inference from samples | records | 1 | 0 | Native records/view |
| distribution aware generation | records | 1 | 0 | Native records/view |
| data masking anonymization ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| schema editor backend | records | 1 | 0 | Native records/view |
| dataset preview endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| export to csv parquet json | records | 1 | 0 | Native records/view |
| privacy compliance pii redaction | records | 1 | 0 | Native records/view |
| notifications integrations audit log subsystems only stub | integration | 1 | 0 | Provider request records only |
| multi tenant project workspaces | records | 1 | 0 | Native records/view |
| Agents | records | 2 | 0 | Native records/view |
| Conversations | records | 1 | 0 | Native records/view |
| AI Debate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent Tasks | records | 1 | 0 | Native records/view |
| Quorum Planner | records | 1 | 0 | Native records/view |
| Samproject ragstudio work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Model Hub | records | 1 | 0 | Native records/view |
| Data Engine | records | 1 | 0 | Native records/view |
| Fine-Tuning | records | 1 | 0 | Native records/view |
| API Logs | records | 1 | 0 | Native records/view |
| Advanced Voice AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multilingual Support | records | 1 | 0 | Native records/view |
| Custom Domain Knowledge | records | 1 | 0 | Native records/view |
| Voice Biometrics | records | 1 | 0 | Native records/view |
| Noise Cancellation | records | 1 | 0 | Native records/view |
| Easy Integration | integration | 1 | 0 | Provider request records only |
| agentic playground | records | 1 | 0 | Native records/view |
| prompt library | records | 1 | 0 | Native records/view |
| search backend | records | 1 | 0 | Native records/view |
| usage analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| billing subscription | records | 1 | 0 | Native records/view |
| docs search | records | 1 | 0 | Native records/view |
| status page | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 449 feature pages were visited in the browser; 447 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 130 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

130 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

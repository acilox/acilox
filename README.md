# acilox

A small team that builds data infrastructure — pipelines, integrations,
and operator tooling — for product and analytics teams.

The repositories here are open-source reference implementations of the
patterns we keep building for clients across financial services,
healthcare, retail and logistics. They are deliberately self-contained:
small enough to read end-to-end, complete enough to deploy with real
credentials, and structured the way we structure code on paid work.

## Data engineering

- **[multi-source-finance-etl](https://github.com/acilox/multi-source-finance-etl)** — Oracle / SFTP / REST APIs / Postgres into Snowflake; fraud scoring and SOX checks
- **[healthcare-data-integration](https://github.com/acilox/healthcare-data-integration)** — FHIR / HL7 / EDI 837–835 into ADLS + Postgres + Elasticsearch, with HIPAA Safe-Harbor masking and a master patient index
- **[realtime-commerce-analytics](https://github.com/acilox/realtime-commerce-analytics)** — Kafka speed layer + Airflow batch for sessions, CLV and funnel analytics (Lambda-style)
- **[supply-chain-warehouse](https://github.com/acilox/supply-chain-warehouse)** — SAP / Oracle WMS / MQTT into a Snowflake Kimball star schema, with KPI and demand-forecast feature layers
- **[cross-cloud-data-sync](https://github.com/acilox/cross-cloud-data-sync)** — pluggable connector framework (S3 / Azure / BigQuery / Snowflake / Postgres / Oracle) with a Flask UI and CDC support

## AI tooling and automations

In progress. Agentic workflows, LLM-assisted operators, structured
output pipelines.

## Connections and integrations

In progress. Adapters and bridges between Alteryx, Python, and common
SaaS APIs.

## Working with us

These repositories are MIT-licensed — fork them, lift patterns, deploy
them in your stack.

For paid engagements — implementation, hardening, extending these
patterns to your environment, or building something custom — open an
issue on the most relevant repository and we'll route from there.

Typical engagements:

- Data platform builds and rebuilds (warehouse, lake, lakehouse)
- Source-to-target integration projects (databases, SaaS, EDI/FHIR/HL7)
- Real-time pipelines (Kafka / streaming) wired into existing batch stacks
- Operator UIs for ETL operations teams
- Migration off legacy ETL tools (Alteryx, Informatica, SSIS) onto Python

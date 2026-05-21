# hi

Data engineer. Most of my work sits between operational systems and the
warehouse — pipelines, integrations, light orchestration, and the
boring-but-important stuff like reconciliation, masking, and DQ gates.

Most of what I write is in Python. I lean on Snowflake, Airflow, Kafka,
Postgres and the usual cloud stores; I've been doing more with Flask and
Streamlit when the operators need a UI.

## Data engineering

- **[multi-source-finance-etl](https://github.com/acilox/multi-source-finance-etl)** — Oracle / SFTP / REST APIs / Postgres → Snowflake; fraud scoring + SOX checks
- **[healthcare-data-integration](https://github.com/acilox/healthcare-data-integration)** — FHIR / HL7 / EDI 837/835 → ADLS + Postgres + Elasticsearch with HIPAA Safe-Harbor masking
- **[realtime-commerce-analytics](https://github.com/acilox/realtime-commerce-analytics)** — Kafka clickstream + Airflow batch; sessions, CLV, funnels
- **[supply-chain-warehouse](https://github.com/acilox/supply-chain-warehouse)** — SAP / Oracle WMS / MQTT into a Kimball star schema; OTIF + demand-forecast features
- **[cross-cloud-data-sync](https://github.com/acilox/cross-cloud-data-sync)** — pluggable connectors + Flask UI for moving data between clouds

## AI automations

Coming soon — agentic workflows, LLM-assisted tooling, etc.

## Connections / integrations

Coming soon — Alteryx ↔ Python bridges, API clients, ETL adapters.

## Reach

- email: `dkumar191 [at] users.noreply.github.com`

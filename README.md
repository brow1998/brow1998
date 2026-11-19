<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Bruno Andrade Santos, Senior Data Engineer. A pipeline flowing from api to raw, staging, marts and reports." src="assets/banner-light.svg" width="100%">
</picture>

I move data from places that don't want to give it up to people who need to trust it. The goal is always the same: a pipeline nobody has to think about at 3 a.m.

### House rules

- **Run it twice, get the same answer.** Re-runs never create duplicates.
- **Every number has a receipt.** Any value in a report traces back to the exact response it came from.
- **One command from a clean checkout.** If setup needs a wiki page, the setup is the bug.
- **Tests don't need the internet.** Record real responses once, replay them forever.

<sub>Python · SQL · dbt · Dagster · Airflow · DuckDB · Postgres · ClickHouse · Kafka · Grafana · Docker</sub>

### Selected work

| Project | What it shows |
|---|---|
| [**worldbank-indicators-pipeline**](https://github.com/brow1998/worldbank-indicators-pipeline) | Config-driven ingestion from the World Bank API, content-addressed raw layer, dbt dimensional model on DuckDB, data-quality tests, Dagster assets with lineage |
| [**data-of-fire-challenge**](https://github.com/brow1998/data-of-fire-challenge) | Incremental loads of 733k San Francisco fire incidents into Postgres, a dbt star schema, and a receipt on every fact row |
| [**jobsity**](https://github.com/brow1998/jobsity) | CSV → Kafka → ClickHouse with content-hashed ids: re-sent files never double, offsets commit only after the insert |
| [**grafana-poc**](https://github.com/brow1998/grafana-poc) | Streaming telemetry for an LLM-as-a-Service platform: Redpanda → ClickHouse, Prometheus and Loki, five Grafana dashboards for five different audiences |
| [**hippo-challenge**](https://github.com/brow1998/hippo-challenge) | Pharmacy claim and revert streams deduplicated and validated into per-drug metrics, with every rejected row traced to its file and line |
| [**data_engineer_etl_test**](https://github.com/brow1998/data_engineer_etl_test) | Retail product master data in DuckDB: GTIN and CNPJ check digits validated in SQL, retried lookups resolved, nothing dropped silently |

### After hours

I can't stop building small products for problems I actually have. [**spotidraft**](https://github.com/brow1998/spotidraft) turns YouTube uploads into Spotify for Creators drafts, because doing it by hand twice was once too many. [**empreita**](https://github.com/brow1998/empreita) is a construction management PWA for architects and the clients who keep asking "how much is left?".

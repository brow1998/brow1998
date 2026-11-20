<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Bruno Andrade Santos, Senior Data Engineer. A pipeline flowing from api to raw, staging, marts and reports." src="assets/banner-light.svg" width="100%">
</picture>

I move data from places that don't want to give it up to people who need to trust it. The goal is always the same: a pipeline nobody has to think about at 3 a.m.

**Portfolio:** [brow1998.github.io](https://brow1998.github.io) · [LinkedIn](https://www.linkedin.com/in/brow1998)

### House rules

- **Run it twice, get the same answer.** Re-runs never create duplicates.
- **Every number has a receipt.** Any value in a report traces back to the exact response it came from.
- **One command from a clean checkout.** If setup needs a wiki page, the setup is the bug.
- **Tests don't need the internet.** Record real responses once, replay them forever.

<sub>Python · SQL · dbt · Dagster · Airflow · DuckDB · Postgres · ClickHouse · Kafka · Grafana · Docker</sub>

### Shipped and running

Three products I built and run on my own infrastructure, with 4,067 people signed up between them.

| Product | What it is | In production |
|---|---|---|
| [**Watchfolio**](https://usewatchfolio.com) | A diary for series, films and anime. Postgres with 17.4M episode watches and an 856k-title catalog synced from TMDB and TVDB; an MCP server so Claude can work with a user's library | 3,930 people, 1,691 active in the last 30 days |
| [**Shelfie**](https://useshelfie.com) | A household's collection on the phone. Barcode scans query 17 catalog providers merged into one 45k-product catalog | 123 people, 8,381 items |
| [**Pedro**](https://brow1998.github.io/?for=fde#pedro) | Internal tool that runs a video agency's production pipeline around one number: days of slack per channel. MCP server with 21 tools and its own OAuth consent | 706 videos, 14 channels |

<sub>Counts read from each production database on 2026-11-20. The code is private; ask me for a walkthrough.</sub>

### Selected work

| Project | What it shows |
|---|---|
| [**imdb-airflow-pipeline**](https://github.com/brow1998/imdb-airflow-pipeline) | Airflow 3 + DuckDB + dbt over the daily IMDb files: ETag-aware downloads into a content-addressed store, daily rating snapshots, idempotent backfills, dbt layers that stop on a failing test |
| [**worldbank-indicators-pipeline**](https://github.com/brow1998/worldbank-indicators-pipeline) | Config-driven ingestion from the World Bank API, content-addressed raw layer, dbt dimensional model on DuckDB, data-quality tests, Dagster assets with lineage |
| [**data-of-fire-challenge**](https://github.com/brow1998/data-of-fire-challenge) | Incremental loads of 733k San Francisco fire incidents into Postgres, a dbt star schema, and a receipt on every fact row |
| [**grafana-poc**](https://github.com/brow1998/grafana-poc) | Streaming telemetry for an LLM-as-a-Service platform: Redpanda → ClickHouse, Prometheus and Loki, five Grafana dashboards for five different audiences |
| [**jobsity**](https://github.com/brow1998/jobsity) | CSV → Kafka → ClickHouse with content-hashed ids: re-sent files never double, offsets commit only after the insert |
| [**data_engineer_etl_test**](https://github.com/brow1998/data_engineer_etl_test) | Retail product master data in DuckDB: GTIN and CNPJ check digits validated in SQL, retried lookups resolved, nothing dropped silently |

### After hours

I can't stop building small products for problems I actually have. [**spotidraft**](https://github.com/brow1998/spotidraft) turns YouTube uploads into Spotify for Creators drafts, because doing it by hand twice was once too many.

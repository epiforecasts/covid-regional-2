# covid-regional-2

> **Archived.** No longer maintained; last updated July 2020. It depends on the retired `EpiNow` and `NCoVUtils` packages and on national data sources as published at the time.

Results store for subnational Rt estimates for Afghanistan, Colombia and Russia shown on the epiforecasts COVID-19 website, held as a submodule of epiforecasts/covid alongside covid-regional. It was started afresh in June 2020; earlier results are in epiforecasts/covid-regional-2-archive. Later estimates are in epiforecasts/covid-rt-estimates.

- `update_nowcasts.sh`: updates the shared reporting delay (`update_delay.R`, saved as `delays.rds`) and runs each country's `update_nowcasts.R`, with Russia run on its own because of its number of regions.
- `afghanistan/`, `colombia/`, `russia/`: each has `regional/` (per-region estimates and plots), `regional-summary/` and `data/`, as in covid-regional.

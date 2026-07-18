# FMCSA Mirror Data

Daily automated mirror of two public-domain US DOT / FMCSA datasets from
data.transportation.gov, republished as GitHub release assets so that cloud
services blocked by the data portal's edge can still fetch them.

- `authority.csv` — Licensing & Insurance carrier authority (dataset 6eyk-hxee)
- `census.csv` — FMCSA Company Census (dataset az4n-8mr2)

Data is produced by the US federal government and is in the public domain.
Refreshed daily by the workflow in `.github/workflows/mirror.yml`; download the
latest copies from the `daily` release.

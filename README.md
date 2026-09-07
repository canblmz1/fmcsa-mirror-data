# FMCSA Mirror Data

Daily automated mirror of two public-domain U.S. DOT / FMCSA datasets from
data.transportation.gov, republished as GitHub release assets so cloud
services blocked by the data portal's edge can still fetch them.

- `authority.csv` — Licensing & Insurance carrier authority (dataset `6eyk-hxee`)
- `census.csv` — FMCSA Company Census (dataset `az4n-8mr2`)

The source data is produced by the U.S. federal government and is mirrored here
without a claim of copyright ownership over the dataset contents. Refreshed
daily by `.github/workflows/mirror.yml`; download the latest copies from the
`daily` release.

## Provenance and license

- The authoritative source is `data.transportation.gov` / FMCSA.
- Mirrored federal dataset contents are described in [NOTICE](NOTICE).
- Repository-authored automation and documentation are licensed under the
  [MIT License](LICENSE).

Consumers should use the original data portal for authoritative metadata,
field definitions, and source-side notices.

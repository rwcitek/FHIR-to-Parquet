# FHIR-to-Parquet

A project to convert FHIR/JSON data to parquet.

## Roadmap

## Phase 1
- [ ] Explore FHIR with jq
- [ ] Explort FHIR with Python
- [ ] Determine next steps

## Phase 2
- [ ] create bundle parquet file with bundle ID and JSON
- [ ] create unique list of resources across all bundles
- [ ] create a parquet file for one or two resouces mentioned in Kaggle project
  - [ ] use same fields as in Kaggle project and JSON for entire resource
- [ ] determine next steps

### Phase 3
- [ ] push resource parquet files to AWS S3
- [ ] query resource parquet files on AWS S3 using DuckDB and HTTPS
- [ ] try DuckDB Shell
- [ ] determine next steps

### Phase 4
- [ ] ...
- [ ] profit ?
- [ ] determine next steps


## Phase "eventually"
- [ ] put parquet files for each resource on AWS s3
- [ ] query resource parquet files on AWS S3 using DuckDB and HTTPS


## Stretch goals
- [ ] create catalog db and put on AWS S3 ( possible ? )
- [ ] create hive structure for each resource parquet file
- [ ] enable object listing for the parquet files on AWS S3




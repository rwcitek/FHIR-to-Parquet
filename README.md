# FHIR-to-Parquet

A project to convert FHIR/JSON data to parquet.

## Roadmap

## Phase 1
- [x] Explore FHIR with jq
- [x] Explort FHIR with Python
- [x] Determine next steps

## Phase 2
- [x] create bundle parquet file with bundle ID and JSON
- [x] create unique list of resources across all bundles
- [x] create a view for one or two resouces mentioned in Kaggle project
  - [x] use same fields as in Kaggle project and JSON for entire resource
- [x] determine next steps

### Phase 3
- [x] push bundle parquet file to AWS S3
- [x] query bundle parquet file on AWS S3 using DuckDB and HTTPS
- [x] try DuckDB Shell
  - [ ] didn't work; not sure why not; need to troubleshoot and fix
- [x] determine next steps

### Phase 4
- [ ] create a parquet file for one or two resouces mentioned in Kaggle project
- [ ] push resource parquet files to AWS S3
- [ ] query resource parquet files on AWS S3 using DuckDB and HTTPS
- [ ] determine next steps

## Phase 5
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




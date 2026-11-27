---
api_specs:
- filename: databricks-clusters-api-openapi.yml
  format: yaml
  label: Databricks Clusters API
  slug: databricks-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databricks/openapi/databricks-clusters-api-openapi.yml
- filename: databricks-jobs-api-openapi.yml
  format: yaml
  label: Databricks Jobs API
  slug: databricks-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databricks/openapi/databricks-jobs-api-openapi.yml
- filename: databricks-workspace-api-openapi.yml
  format: yaml
  label: Databricks Workspace API
  slug: databricks-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databricks/openapi/databricks-workspace-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you access the Sites on behalf of a legal entity, to that entity
    type: business
  minimum_age:
    text: BY ACCESSING OR USING ANY OF THE SITES, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: No competitive use of the Sites
    text: Use or apply the Sites in any manner directly or indirectly competitive with any business of Databricks.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Databricks
provenance_date: '2026-11-09'
provider_name: Databricks
provider_slug: databricks
slug: databricks-eligibility
source_date: '2026-11-09'
source_filename: databricks-eligibility.yml
source_heading: Eligibility
source_page: https://www.databricks.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Databricks\naid: databricks\nurl: https://www.databricks.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you access the Sites on behalf of a legal entity, to that entity\nrestricted_uses:\n- summary: No competitive use of the Sites\n  text: Use or apply the Sites in any manner directly or indirectly competitive with any business of Databricks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY ACCESSING OR USING ANY OF THE SITES, YOU REPRESENT\
  \ THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/databricks/eligibility/databricks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Databricks's own page on 2026-11-09.
synthetic: false
tags:
- Cleanroom
- Databricks
- Artificial Intelligence
- Analytics
- Apache Spark
- Big Data
- Cloud Computing
- Data
- Data Analytics
- Data Engineering
- Data Governance
- Delta Lake
- Delta Sharing
- ETL
- Lakehouse
- Machine Learning
- MLflow
- Model Serving
- Security
- SQL
- Unity Catalog
- Vector Search
- Visualize
- Data Catalog
---

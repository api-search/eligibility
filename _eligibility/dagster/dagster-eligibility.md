---
api_specs:
- filename: dagster-checks-api-openapi.yml
  format: yaml
  label: Dagster Checks API
  slug: dagster-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dagster/openapi/dagster-checks-api-openapi.yml
- filename: dagster-materializations-api-openapi.yml
  format: yaml
  label: Dagster Materializations API
  slug: dagster-materializations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dagster/openapi/dagster-materializations-api-openapi.yml
- filename: dagster-observations-api-openapi.yml
  format: yaml
  label: Dagster Observations API
  slug: dagster-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dagster/openapi/dagster-observations-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: copy and use the included Software and Documentation only as needed to access and use the Cloud Service, in each case, for Your internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the Cloud Service with any High Risk Activities or with activity prohibited by Applicable Laws
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
name: Dagster
provenance_date: '2026-11-09'
provider_name: Dagster
provider_slug: dagster
slug: dagster-eligibility
source_date: '2026-11-09'
source_filename: dagster-eligibility.yml
source_heading: Eligibility
source_page: https://dagster.io/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dagster\naid: dagster\nurl: https://dagster.io/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: copy and use the included Software and Documentation only as needed to access and use the Cloud Service,\n    in each case, for Your internal business purposes\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the Cloud Service with any High Risk Activities or with activity prohibited by Applicable Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/dagster/eligibility/dagster-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dagster's own page on 2026-11-09.
synthetic: false
tags:
- Data Engineering
- Data Orchestration
- Data Pipeline
- ETL
- Workflows
- Assets
- GraphQL
---

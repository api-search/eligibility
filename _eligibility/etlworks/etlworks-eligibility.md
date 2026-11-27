---
api_specs:
- filename: etlworks-openapi-generated.yml
  format: yaml
  label: Etlworks API
  slug: etlworks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etlworks/openapi/_ae-authored/etlworks-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: PHI processing requires BAA
    text: Required before processing PHI on Etlworks
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
name: Etlworks
provenance_date: '2026-11-09'
provider_name: Etlworks
provider_slug: etlworks
slug: etlworks-eligibility
source_date: '2026-11-09'
source_filename: etlworks-eligibility.yml
source_heading: Eligibility
source_page: https://etlworks.com/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Etlworks\naid: etlworks\nurl: https://etlworks.com/legal.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: PHI processing requires BAA\n  text: Required before processing PHI on Etlworks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/etlworks/eligibility/etlworks-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Etlworks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- Cloud
---

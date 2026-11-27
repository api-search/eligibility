---
api_specs:
- filename: expanso-ops-api-openapi.yml
  format: yaml
  label: Expanso Ops API
  slug: expanso-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/expanso/openapi/expanso-ops-api-openapi.yml
- filename: expanso-orchestrator-api-openapi.yml
  format: yaml
  label: Expanso Orchestrator API
  slug: expanso-orchestrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/expanso/openapi/expanso-orchestrator-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
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
name: Expanso
provenance_date: '2026-11-09'
provider_name: Expanso
provider_slug: expanso
slug: expanso-eligibility
source_date: '2026-11-09'
source_filename: expanso-eligibility.yml
source_heading: Eligibility
source_page: https://expanso.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Expanso\naid: expanso\nurl: https://expanso.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/expanso/eligibility/expanso-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Expanso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Distributed Computing
- Edge Computing
- Compute Orchestration
- Data Pipeline
- Data Governance
- Open Source
- Artificial Intelligence
- Job Orchestration
---

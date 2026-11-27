---
api_specs:
- filename: briq-cloud-v1-openapi.json
  format: json
  label: briq API V1 API
  slug: briq-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/briq-cloud/openapi/_original/briq-cloud-v1-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept for a company, you confirm you may bind it.
    type: business
  - text: Consumers keep their statutory rights.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: briq
provenance_date: '2026-11-09'
provider_name: briq
provider_slug: briq-cloud
slug: briq-cloud-eligibility
source_date: '2026-11-09'
source_filename: briq-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://briq.cloud/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: briq\naid: briq-cloud\nurl: https://briq.cloud/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept for a company, you confirm you may bind it.\n- type: individual\n  text: Consumers keep their statutory rights.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/briq-cloud/eligibility/briq-cloud-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from briq's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Sandbox
- Database
- Platform
- Company
---

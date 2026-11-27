---
api_specs:
- filename: zephyr-cloud-content-api-openapi.yml
  format: yaml
  label: Zephyr Cloud Content API
  slug: zephyr-cloud-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zephyr-cloud/openapi/zephyr-cloud-content-api-openapi.yml
- filename: zephyr-cloud-discovery-api-openapi.yml
  format: yaml
  label: Zephyr Cloud Discovery API
  slug: zephyr-cloud-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zephyr-cloud/openapi/zephyr-cloud-discovery-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services are built for developers and businesses.
    type: business
  - text: Some terms below apply differently to consumers, meaning individuals using the services outside their trade, business, or profession; where they do, we say so.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live, to create an account.
    value: '18'
  restricted_uses:
  - summary: Export controls and sanctions
    text: You may not use the services in violation of U.S., EU, UK, or other applicable export control or sanctions laws.
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
name: Zephyr Cloud
provenance_date: '2026-11-10'
provider_name: Zephyr Cloud
provider_slug: zephyr-cloud
slug: zephyr-cloud-eligibility
source_date: '2026-11-10'
source_filename: zephyr-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://zephyr-cloud.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zephyr Cloud\naid: zephyr-cloud\nurl: https://zephyr-cloud.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services are built for developers and businesses.\n- type: individual\n  text: Some terms below apply differently to consumers, meaning individuals using the services outside their trade,\n    business, or profession; where they do, we say so.\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: You may not use the services in violation of U.S., EU, UK, or other applicable export control or sanctions\n\
  \    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live, to create an account.\n"
source_yaml_url: https://artifacts.apis.io/zephyr-cloud/eligibility/zephyr-cloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zephyr Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Deployment
- DevOps
- Platform
---

---
api_specs:
- filename: datacircle-datacircle-api-openapi.yml
  format: yaml
  label: Datacircle Datacircle API
  slug: datacircle-datacircle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-datacircle-api-openapi.yml
- filename: datacircle-fetchin-api-openapi.yml
  format: yaml
  label: Datacircle Fetchin API
  slug: datacircle-fetchin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-fetchin-api-openapi.yml
- filename: datacircle-harvestapi-api-openapi.yml
  format: yaml
  label: Datacircle Harvest API
  slug: datacircle-harvestapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-harvestapi-api-openapi.yml
- filename: datacircle-up2data-api-openapi.yml
  format: yaml
  label: Datacircle Up2 Data API
  slug: datacircle-up2data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-up2data-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for a company, you agree for that company.
    type: business
  - text: Each person may have one account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use
    text: use the Service for anything illegal
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'We send you a code. Use an address you can read: you sign in with it.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datacircle
provenance_date: '2026-11-09'
provider_name: Datacircle
provider_slug: datacircle
slug: datacircle-eligibility
source_date: '2026-11-09'
source_filename: datacircle-eligibility.yml
source_heading: Eligibility
source_page: https://datacircle.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datacircle\naid: datacircle\nurl: https://datacircle.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for a company, you agree for that company.\n- type: individual\n  text: Each person may have one account.\nrestricted_uses:\n- summary: Illegal use\n  text: use the Service for anything illegal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'We send you a code. Use an address you can read: you sign in with it.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datacircle/eligibility/datacircle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Datacircle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B Data
- MCP
- API Directory
- Benchmarks
- Open Data
---

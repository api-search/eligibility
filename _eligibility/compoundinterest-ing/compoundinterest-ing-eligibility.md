---
api_specs:
- filename: compoundinterest-ing-openapi-generated.yml
  format: yaml
  label: Compound Interesting API
  slug: compoundinterest-ing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compoundinterest-ing/openapi/_ae-authored/compoundinterest-ing-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: for your personal or internal business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
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
name: Compound Interesting
provenance_date: '2026-11-09'
provider_name: Compound Interesting
provider_slug: compoundinterest-ing
slug: compoundinterest-ing-eligibility
source_date: '2026-11-09'
source_filename: compoundinterest-ing-eligibility.yml
source_heading: Eligibility
source_page: https://compoundinterest.ing/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compound Interesting\naid: compoundinterest-ing\nurl: https://compoundinterest.ing/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: for your personal or internal business purposes\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/compoundinterest-ing/eligibility/compoundinterest-ing-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Compound Interesting's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Market Intelligence
- Insider Trading
- Congressional Trades
- SEC Filings
- Institutional Holdings
- MCP
- Investing
---

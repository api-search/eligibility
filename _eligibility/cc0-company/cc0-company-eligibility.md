---
api_specs:
- filename: cc0-company-openapi-generated.yml
  format: yaml
  label: CC0 Company API
  slug: cc0-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cc0-company/openapi/_ae-authored/cc0-company-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old (or legal age in your jurisdiction)
    type: individual
  minimum_age:
    text: Be at least 18 years old (or legal age in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited items
    text: Sell illegal goods
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
name: CC0 Company
provenance_date: '2026-11-09'
provider_name: CC0 Company
provider_slug: cc0-company
slug: cc0-company-eligibility
source_date: '2026-11-09'
source_filename: cc0-company-eligibility.yml
source_heading: Eligibility
source_page: https://app.cc0.company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CC0 Company\naid: cc0-company\nurl: https://app.cc0.company/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old (or legal age in your jurisdiction)\nrestricted_uses:\n- summary: Illegal or prohibited items\n  text: Sell illegal goods\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old (or legal age in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/cc0-company/eligibility/cc0-company-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CC0 Company's own page on 2026-11-09.
synthetic: false
tags:
- Digital Art
- Social Network
- NFT
- live auctions
- Token Launch
- AI Agents
---

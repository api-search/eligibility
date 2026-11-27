---
api_specs:
- filename: open-banking-openapi-generated.yml
  format: yaml
  label: Tatic API
  slug: open-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-banking/openapi/_ae-authored/open-banking-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is for businesses and private users alike.
    type: business
  - text: The service is for businesses and private users alike.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only authorised bank accounts
    text: You may only connect bank accounts you are authorised to access.
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
name: Tatic
provenance_date: '2026-11-10'
provider_name: Tatic
provider_slug: open-banking
slug: open-banking-eligibility
source_date: '2026-11-10'
source_filename: open-banking-eligibility.yml
source_heading: Eligibility
source_page: https://open-banking.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tatic\naid: open-banking\nurl: https://open-banking.io/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is for businesses and private users alike.\n- type: individual\n  text: The service is for businesses and private users alike.\nrestricted_uses:\n- summary: Only authorised bank accounts\n  text: You may only connect bank accounts you are authorised to access.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/open-banking/eligibility/open-banking-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Tatic's own page on 2026-11-10.
synthetic: false
tags:
- Company
---

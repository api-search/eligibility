---
api_specs:
- filename: backquant-com-api-openapi.json
  format: json
  label: BackQuant API v2 API
  slug: backquant-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backquant-com/openapi/_original/backquant-com-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Commercial use requires separate agreement
    text: No commercial, redistribution, or white label rights are granted by default under any standard subscription plan.
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
name: BackQuant
provenance_date: '2026-11-09'
provider_name: BackQuant
provider_slug: backquant-com
slug: backquant-com-eligibility
source_date: '2026-11-09'
source_filename: backquant-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.backquant.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BackQuant\naid: backquant-com\nurl: https://www.backquant.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\nrestricted_uses:\n- summary: Commercial use requires separate agreement\n  text: No commercial, redistribution, or white label rights are granted by default under any standard subscription\n    plan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use\
  \ the Service.\n"
source_yaml_url: https://artifacts.apis.io/backquant-com/eligibility/backquant-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BackQuant's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Options
- Cryptocurrency
- Analytics
---

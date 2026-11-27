---
api_specs:
- filename: investormatch-pro-openapi.json
  format: json
  label: InvestorMatch.Pro API
  slug: investormatch-pro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/investormatch-pro/openapi/investormatch-pro-openapi.json
- filename: investormatch-pro-api-openapi.json
  format: json
  label: InvestorMatch.Pro API API
  slug: investormatch-pro-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/investormatch-pro/openapi/_original/investormatch-pro-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to enter into binding contracts to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to enter into binding contracts to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Use the Service for any unlawful purpose or in violation of these Terms
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
name: investormatch-pro
provenance_date: '2026-11-09'
provider_name: investormatch-pro
provider_slug: investormatch-pro
slug: investormatch-pro-eligibility
source_date: '2026-11-09'
source_filename: investormatch-pro-eligibility.yml
source_heading: Eligibility
source_page: https://investormatch.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: investormatch-pro\naid: investormatch-pro\nurl: https://investormatch.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to enter into binding contracts to use the\n    Service.\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Service for any unlawful purpose or in violation of these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the\
  \ legal capacity to enter into binding contracts to use the\n    Service.\n"
source_yaml_url: https://artifacts.apis.io/investormatch-pro/eligibility/investormatch-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from investormatch-pro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fundraising
- Venture Capital
- Startups
---

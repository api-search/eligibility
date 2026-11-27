---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the Codi Platform or register a Codi Account
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into legally binding contracts
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
name: Codi
provenance_date: '2026-11-09'
provider_name: Codi
provider_slug: codi
slug: codi-eligibility
source_date: '2026-11-09'
source_filename: codi-eligibility.yml
source_heading: Eligibility
source_page: https://www.codi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codi\naid: codi\nurl: https://www.codi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the\n    Codi Platform or register a Codi Account\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/codi/eligibility/codi-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Codi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Office Space
- Flexible Office
- Office Management
- Facilities Management
- Workplace
- Commercial Real Estate
- Co-Working
- San Francisco
- New York City
---

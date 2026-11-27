---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are permitted to use the Service only in the United States.
  entity_types:
  - text: 'You represent and warrant that: (1) you are at least 18 years of age'
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful use only; no competing service
    text: You may use the Service solely for lawful purposes, as intended through the provided functionality of the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Italic might require you to complete a registration process to access certain parts of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Italic
provenance_date: '2026-11-09'
provider_name: Italic
provider_slug: italic
slug: italic-eligibility
source_date: '2026-11-09'
source_filename: italic-eligibility.yml
source_heading: Eligibility
source_page: https://www.italic.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Italic\naid: italic\nurl: https://www.italic.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are permitted to use the Service only in the United States.\nentity_types:\n- type: individual\n  text: 'You represent and warrant that: (1) you are at least 18 years of age'\nrestricted_uses:\n- summary: Lawful use only; no competing service\n  text: You may use the Service solely for lawful purposes, as intended through the provided functionality of the\n    Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Italic might require you to complete a registration process to access certain parts of the Service.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/italic/eligibility/italic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Italic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Consumer
- Home Goods
- Direct to Consumer
- Marketplace
- Membership
---

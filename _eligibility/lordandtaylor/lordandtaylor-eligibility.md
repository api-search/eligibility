---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction), or have parental consent, to use this Site or make purchases.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction), or have parental consent, to use this Site or make purchases.
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
name: Lord & Taylor
provenance_date: '2026-11-09'
provider_name: Lord & Taylor
provider_slug: lordandtaylor
slug: lordandtaylor-eligibility
source_date: '2026-11-09'
source_filename: lordandtaylor-eligibility.yml
source_heading: Eligibility
source_page: https://lordandtaylor.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lord & Taylor\naid: lordandtaylor\nurl: https://lordandtaylor.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction), or have parental consent,\n    to use this Site or make purchases.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction), or have parental consent,\n\
  \    to use this Site or make purchases.\n"
source_yaml_url: https://artifacts.apis.io/lordandtaylor/eligibility/lordandtaylor-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Lord & Taylor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Apparel
- Shopping
- Department Store
- Agentic Commerce
- MCP
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, to create an account. One account is for one person.
    type: individual
  minimum_age:
    text: You must be at least 18, or the age of majority where you live, to create an account.
    value: '18'
  restricted_uses:
  - summary: Personal shopping only
    text: Pro is for one person's own shopping.
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
name: Laurel
provenance_date: '2026-11-09'
provider_name: Laurel
provider_slug: checklaurel-com
slug: checklaurel-com-eligibility
source_date: '2026-11-09'
source_filename: checklaurel-com-eligibility.yml
source_heading: Eligibility
source_page: https://checklaurel.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laurel\naid: checklaurel-com\nurl: https://checklaurel.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, to create an account. One account is for\n    one person.\nrestricted_uses:\n- summary: Personal shopping only\n  text: Pro is for one person's own shopping.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live, to create an account.\n"
source_yaml_url: https://artifacts.apis.io/checklaurel-com/eligibility/checklaurel-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Laurel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Products
- E-Commerce
- Product Discovery
- Low Tox
- Sustainability
- MCP
- Shopping
---

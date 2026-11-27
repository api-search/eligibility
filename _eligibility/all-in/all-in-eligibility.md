---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses
    text: (h) to collect or track the personal information of others
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
name: All In
provenance_date: '2026-11-09'
provider_name: All In
provider_slug: all-in
slug: all-in-eligibility
source_date: '2026-11-09'
source_filename: all-in-eligibility.yml
source_heading: Eligibility
source_page: https://allinfood.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: All In\naid: all-in\nurl: https://allinfood.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses\n  text: (h) to collect or track the personal information of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/all-in/eligibility/all-in-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from All In's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Snacks
- Nutrition
- Consumer Packaged Goods
- Commerce
- Agentic Commerce
- Shopify
- MCP
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Excludes Puerto Rico
  entity_types:
  - text: you represent that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: you are at least 13 years of age
    value: '13'
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
name: Cotopaxi
provenance_date: '2026-11-09'
provider_name: Cotopaxi
provider_slug: cotopaxi
slug: cotopaxi-eligibility
source_date: '2026-11-09'
source_filename: cotopaxi-eligibility.yml
source_heading: Eligibility
source_page: https://www.cotopaxi.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cotopaxi\naid: cotopaxi\nurl: https://www.cotopaxi.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Excludes Puerto Rico\nentity_types:\n- type: individual\n  text: you represent that you are of legal age to form a binding contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/cotopaxi/eligibility/cotopaxi-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Cotopaxi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Outdoor
- Apparel
- E-Commerce
- Retail
- Shopify
- MCP
---

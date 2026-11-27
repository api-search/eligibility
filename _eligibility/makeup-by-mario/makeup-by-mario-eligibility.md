---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 18 years old or the age of majority in your jurisdiction in order to make a purchase on the Site.
    value: '18'
  restricted_uses:
  - summary: No resale
    text: You may not sell or resell any of the products or services, or samples thereof, you purchase or otherwise receive from us.
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
name: Makeup by Mario
provenance_date: '2026-11-10'
provider_name: Makeup by Mario
provider_slug: makeup-by-mario
slug: makeup-by-mario-eligibility
source_date: '2026-11-10'
source_filename: makeup-by-mario-eligibility.yml
source_heading: Eligibility
source_page: https://www.makeupbymario.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Makeup by Mario\naid: makeup-by-mario\nurl: https://www.makeupbymario.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No resale\n  text: You may not sell or resell any of the products or services, or samples thereof, you purchase or otherwise\n    receive from us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years old or the age of majority in your jurisdiction in order to make a purchase on the\n    Site.\n"
source_yaml_url: https://artifacts.apis.io/makeup-by-mario/eligibility/makeup-by-mario-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Makeup by Mario's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Beauty
- Cosmetics
- Consumer Packaged Goods
- E-Commerce
- Direct to Consumer
- Retail
- Agentic Commerce
- Shopify
- GraphQL
- MCP
- Universal Commerce Protocol
---

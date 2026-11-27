---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This is a legal agreement between you (meaning you as an individual if acting on your own behalf
    type: individual
  - text: or the company that you represent if you are acting on behalf of such company)
    type: business
  minimum_age:
    text: be at all times in compliance with these Terms and applicable law, including the requirement to be 18 years of age or older.
    value: '18'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: All orders are subject to acceptance by Bartesian, and any rejection of an order shall be made in Bartesian’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bartesian
provenance_date: '2026-11-09'
provider_name: Bartesian
provider_slug: bartesian
slug: bartesian-eligibility
source_date: '2026-11-09'
source_filename: bartesian-eligibility.yml
source_heading: Eligibility
source_page: https://bartesian.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bartesian\naid: bartesian\nurl: https://bartesian.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This is a legal agreement between you (meaning you as an individual if acting on your own behalf\n- type: business\n  text: or the company that you represent if you are acting on behalf of such company)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: All orders are subject to acceptance by Bartesian, and any rejection of an order shall be made in Bartesian’s\n\
  \    sole discretion.\nminimum_age:\n  value: '18'\n  text: be at all times in compliance with these Terms and applicable law, including the requirement to be 18 years\n    of age or older.\n"
source_yaml_url: https://artifacts.apis.io/bartesian/eligibility/bartesian-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bartesian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Consumer Products
- Appliances
- Beverages
- Direct to Consumer
- Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---

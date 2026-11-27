---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region, or jurisdiction.
  entity_types:
  - text: By placing an order using our Services, you warrant and represent that you have capacity to form a binding contract with us because (1) you are at least the age of majority in your state or province of residence or (2) you have been granted such capacity by court order, operation of law, or other legal act.
    type: individual
  minimum_age:
    text: We offer the services of our website (“Website”) and SMS/MMS Mobile Messaging Program (collectively, “Services”) to you only if you are 13 years of age or older
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
name: Kizik
provenance_date: '2026-11-09'
provider_name: Kizik
provider_slug: kizik
slug: kizik-eligibility
source_date: '2026-11-09'
source_filename: kizik-eligibility.yml
source_heading: Eligibility
source_page: https://kizik.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kizik\naid: kizik\nurl: https://kizik.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region, or jurisdiction.\nentity_types:\n- type: individual\n  text: By placing an order using our Services, you warrant and represent that you have capacity to form a binding\n    contract with us because (1) you are at least the age of majority in your state or province of residence or\n    (2) you have been granted such capacity by court order,\
  \ operation of law, or other legal act.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We offer the services of our website (“Website”) and SMS/MMS Mobile Messaging Program (collectively, “Services”)\n    to you only if you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/kizik/eligibility/kizik-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Kizik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Footwear
- Consumer Goods
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
- Direct to Consumer
---

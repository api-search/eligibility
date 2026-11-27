---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Shipping to destinations outside the 48 continental United States is based on package weight and size. Due to shipping carrier regulations around high-capacity lithium-ion batteries, we cannot ship ebikes, or ebike batteries, outside of the 48 continental United States.
  entity_types:
  - text: The Services are intended solely for persons who are 16 years old or such higher age required in your country to use the Services.
    type: individual
  - text: Corporations or other entities or organizations of any kind are not eligible to participate in Rewards Programs.
    type: business
  minimum_age:
    text: The Services are intended solely for persons who are 16 years old or such higher age required in your country to use the Services.
    value: '16'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: The Sites and Services are for your personal and noncommercial use.
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
name: Aventon
provenance_date: '2026-11-09'
provider_name: Aventon
provider_slug: aventon
slug: aventon-eligibility
source_date: '2026-11-09'
source_filename: aventon-eligibility.yml
source_heading: Eligibility
source_page: https://www.aventon.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aventon\naid: aventon\nurl: https://www.aventon.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Shipping to destinations outside the 48 continental United States is based on package weight and size. Due\n    to shipping carrier regulations around high-capacity lithium-ion batteries, we cannot ship ebikes, or ebike\n    batteries, outside of the 48 continental United States.\nentity_types:\n- type: individual\n  text: The Services are intended solely for persons who are 16 years old or such higher age required in your country\n    to\
  \ use the Services.\n- type: business\n  text: Corporations or other entities or organizations of any kind are not eligible to participate in Rewards Programs.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: The Sites and Services are for your personal and noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are intended solely for persons who are 16 years old or such higher age required in your country\n    to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/aventon/eligibility/aventon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Aventon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Electric Bikes
- E-Commerce
- Retail
- Agentic Commerce
- Shopify
- Universal Commerce Protocol
---

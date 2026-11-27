---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability may vary depending on location.
  entity_types:
  - text: Black Buffalo products are intended for adults aged 21 or older who are consumers of nicotine or tobacco.
    type: individual
  minimum_age:
    text: You must be 21 or older to visit this website.
    value: '21'
  restricted_uses:
  - summary: Underage sale prohibited
    text: Underage sale prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your age will be verified at checkout.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Black Buffalo
provenance_date: '2026-11-09'
provider_name: Black Buffalo
provider_slug: black-buffalo
slug: black-buffalo-eligibility
source_date: '2026-11-09'
source_filename: black-buffalo-eligibility.yml
source_heading: Eligibility
source_page: https://blackbuffalo.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Black Buffalo\naid: black-buffalo\nurl: https://blackbuffalo.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability may vary depending on location.\nentity_types:\n- type: individual\n  text: Black Buffalo products are intended for adults aged 21 or older who are consumers of nicotine or tobacco.\nrestricted_uses:\n- summary: Underage sale prohibited\n  text: Underage sale prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your age will be verified at checkout.\nminimum_age:\n  value: '21'\n  text: You must\
  \ be 21 or older to visit this website.\n"
source_yaml_url: https://artifacts.apis.io/black-buffalo/eligibility/black-buffalo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Black Buffalo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Nicotine Pouches
- Smokeless Tobacco Alternative
- E-Commerce
- Direct to Consumer
- Retail
- Agentic Commerce
- Shopify
- GraphQL
- MCP
- Universal Commerce Protocol
---

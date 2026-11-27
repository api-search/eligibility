---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Dispute Resolution (SMS recipients in the USA only)
  entity_types:
  - text: You must have a wireless device of your own, capable of two-way messaging
    type: individual
  minimum_age:
    text: You may not use or engage with the Platform if you are under thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Prohibited message content
    text: Any product, service, or promotion that is unlawful where such product, service, or promotion thereof is received
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
name: True Botanicals
provenance_date: '2026-11-10'
provider_name: True Botanicals
provider_slug: true-botanicals
slug: true-botanicals-eligibility
source_date: '2026-11-10'
source_filename: true-botanicals-eligibility.yml
source_heading: Eligibility
source_page: https://truebotanicals.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: True Botanicals\naid: true-botanicals\nurl: https://truebotanicals.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Dispute Resolution (SMS recipients in the USA only)\nentity_types:\n- type: individual\n  text: You must have a wireless device of your own, capable of two-way messaging\nrestricted_uses:\n- summary: Prohibited message content\n  text: Any product, service, or promotion that is unlawful where such product, service, or promotion thereof is\n    received\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You may not use or engage with the Platform if you are under thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/true-botanicals/eligibility/true-botanicals-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from True Botanicals's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Beauty
- Skincare
- Consumer Goods
- Direct to Consumer
- Agentic Commerce
- Shopify
- MCP
- Universal Commerce Protocol
---

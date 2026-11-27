---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must have a wireless device of your own, capable of two-way messaging
    type: individual
  minimum_age:
    text: You may not use of engage with the Platform if you are under thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Prohibited message content
    text: Any fraudulent, libelous, defamatory, scandalous, threatening, harassing, or stalking activity
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
name: Lemon Perfect
provenance_date: '2026-11-09'
provider_name: Lemon Perfect
provider_slug: lemon-perfect
slug: lemon-perfect-eligibility
source_date: '2026-11-09'
source_filename: lemon-perfect-eligibility.yml
source_heading: Eligibility
source_page: https://lemonperfect.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lemon Perfect\naid: lemon-perfect\nurl: https://lemonperfect.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must have a wireless device of your own, capable of two-way messaging\nrestricted_uses:\n- summary: Prohibited message content\n  text: Any fraudulent, libelous, defamatory, scandalous, threatening, harassing, or stalking activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not use of engage with the Platform\
  \ if you are under thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/lemon-perfect/eligibility/lemon-perfect-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lemon Perfect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Consumer Packaged Goods
- E-Commerce
- Retail
- Direct to Consumer
- Agentic Commerce
- MCP
- GraphQL
- Universal Commerce Protocol
- Shopify
---

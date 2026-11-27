---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Dispute Resolution (SMS recipients in the USA only)
  minimum_age:
    text: null
    value: null
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
name: Numi Tea
provenance_date: '2026-11-10'
provider_name: Numi Tea
provider_slug: numi-tea
slug: numi-tea-eligibility
source_date: '2026-11-10'
source_filename: numi-tea-eligibility.yml
source_heading: Eligibility
source_page: https://numitea.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numi Tea\naid: numi-tea\nurl: https://numitea.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Dispute Resolution (SMS recipients in the USA only)\nentity_types: []\nrestricted_uses:\n- summary: Prohibited message content\n  text: Any fraudulent, libelous, defamatory, scandalous, threatening, harassing, or stalking activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/numi-tea/eligibility/numi-tea-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Numi Tea's own page on 2026-11-10.
synthetic: false
tags:
- Tea
- Beverages
- Consumer Packaged Goods
- Retail
- E-Commerce
- Organic
- Fair Trade
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---

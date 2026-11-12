---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Health information is not medical advice
    text: Health and supplement information on Coreplex is general information, not medical advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you create an account, keep your sign-in secure and give accurate details, especially when claiming a brand.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coreplex
provenance_date: '2026-11-09'
provider_name: Coreplex
provider_slug: coreplex-ai
slug: coreplex-ai-eligibility
source_date: '2026-11-09'
source_filename: coreplex-ai-eligibility.yml
source_heading: Eligibility
source_page: https://coreplex.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coreplex\naid: coreplex-ai\nurl: https://coreplex.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Health information is not medical advice\n  text: Health and supplement information on Coreplex is general information, not medical advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you create an account, keep your sign-in secure and give accurate details, especially when claiming a\n    brand.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coreplex-ai/eligibility/coreplex-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Coreplex's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ecommerce
- Shopping
- Shopify
- Product Comparison
- Price Comparison
- MCP
- AI Agents
---

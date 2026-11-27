---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use BuyLater only for lawful, personal, non-commercial purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Use BuyLater only for lawful, personal, non-commercial purposes.
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
name: BuyLater
provenance_date: '2026-11-09'
provider_name: BuyLater
provider_slug: buylater-com
slug: buylater-com-eligibility
source_date: '2026-11-09'
source_filename: buylater-com-eligibility.yml
source_heading: Eligibility
source_page: https://buylater.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuyLater\naid: buylater-com\nurl: https://buylater.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use BuyLater only for lawful, personal, non-commercial purposes.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Use BuyLater only for lawful, personal, non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buylater-com/eligibility/buylater-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BuyLater's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Notification
- AI Assistant
- MCP
- Shopping
---

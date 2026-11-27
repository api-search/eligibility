---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and allowed by the law of your country to trade the instruments you use.
    type: individual
  - text: You must only connect trading accounts that belong to you or that you are authorised to operate.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No market manipulation or breaking platform terms
    text: You must not use TraderWAI to break the law or your platform's terms, to manipulate markets
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
name: traderwai-com
provenance_date: '2026-11-10'
provider_name: traderwai-com
provider_slug: traderwai-com
slug: traderwai-com-eligibility
source_date: '2026-11-10'
source_filename: traderwai-com-eligibility.yml
source_heading: Eligibility
source_page: https://traderwai.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: traderwai-com\naid: traderwai-com\nurl: https://traderwai.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and allowed by the law of your country to trade the instruments you use.\n- type: business\n  text: You must only connect trading accounts that belong to you or that you are authorised to operate.\nrestricted_uses:\n- summary: No market manipulation or breaking platform terms\n  text: You must not use TraderWAI to break the law or your platform's terms, to manipulate markets\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/traderwai-com/eligibility/traderwai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from traderwai-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Trading
- Brokerage
- Automation
- Platform
---

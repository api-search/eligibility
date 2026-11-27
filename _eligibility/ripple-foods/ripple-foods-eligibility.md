---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We currently ship to select metropolitan areas within the US. Unfortunately, we do not currently ship to all states.
  entity_types:
  - text: you are 18 years of age or older
    type: individual
  minimum_age:
    text: you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Business advertising or sales without consent
    text: Use the Properties to advertise or offer to sell or buy any goods or services for any business purpose, without Ripple’s express prior written consent.
  - summary: Dealer, reseller or distributor orders
    text: We reserve the right to limit or prohibit Orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
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
name: Ripple Foods
provenance_date: '2026-11-10'
provider_name: Ripple Foods
provider_slug: ripple-foods
slug: ripple-foods-eligibility
source_date: '2026-11-10'
source_filename: ripple-foods-eligibility.yml
source_heading: Eligibility
source_page: https://ripplefoods.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ripple Foods\naid: ripple-foods\nurl: https://ripplefoods.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We currently ship to select metropolitan areas within the US. Unfortunately, we do not currently ship to\n    all states.\nentity_types:\n- type: individual\n  text: you are 18 years of age or older\nrestricted_uses:\n- summary: Business advertising or sales without consent\n  text: Use the Properties to advertise or offer to sell or buy any goods or services for any business purpose,\n    without Ripple’s express prior written consent.\n- summary:\
  \ Dealer, reseller or distributor orders\n  text: We reserve the right to limit or prohibit Orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/ripple-foods/eligibility/ripple-foods-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ripple Foods's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Food and Beverage
- Consumer Packaged Goods
- Plant-Based
- Direct to Consumer
- E-Commerce
---

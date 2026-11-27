---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Products and Services are only available for sale within the United States and U.S. territories.
  entity_types:
  - text: the Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: the Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only for materials
    text: Any use of any of the Kitu Life Materials other than for private, non-commercial use is strictly prohibited.
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
name: Super Coffee
provenance_date: '2026-11-10'
provider_name: Super Coffee
provider_slug: super-coffee
slug: super-coffee-eligibility
source_date: '2026-11-10'
source_filename: super-coffee-eligibility.yml
source_heading: Eligibility
source_page: https://www.drinksupercoffee.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Super Coffee\naid: super-coffee\nurl: https://www.drinksupercoffee.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Products and Services are only available for sale within the United States and U.S. territories.\nentity_types:\n- type: individual\n  text: the Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Non-commercial use only for materials\n  text: Any use of any of the Kitu Life Materials other\
  \ than for private, non-commercial use is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/super-coffee/eligibility/super-coffee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Super Coffee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food and Beverage
- Consumer Packaged Goods
- Retail
- E-Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---

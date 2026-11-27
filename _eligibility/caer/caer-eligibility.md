---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Use of the Sites is intended only for users who are 18 years of age or older and reside in the United States.
  entity_types:
  - text: Yumi Rewards is intended for personal use only. Commercial use is prohibited.
    type: individual
  minimum_age:
    text: Use of the Sites is intended only for users who are 18 years of age or older and reside in the United States.
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use of products
    text: You are not permitted to resell or otherwise use for commercial purposes Yumi’s food or other products.
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
name: Caer
provenance_date: '2026-11-09'
provider_name: Caer
provider_slug: caer
slug: caer-eligibility
source_date: '2026-11-09'
source_filename: caer-eligibility.yml
source_heading: Eligibility
source_page: https://helloyumi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caer\naid: caer\nurl: https://helloyumi.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Use of the Sites is intended only for users who are 18 years of age or older and reside in the United States.\nentity_types:\n- type: individual\n  text: Yumi Rewards is intended for personal use only. Commercial use is prohibited.\nrestricted_uses:\n- summary: No resale or commercial use of products\n  text: You are not permitted to resell or otherwise use for commercial purposes Yumi’s food or other products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Sites is intended only for users who are 18 years of age or older and reside in the United States.\n"
source_yaml_url: https://artifacts.apis.io/caer/eligibility/caer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Caer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Food and Beverage
- E-Commerce
- Baby and Kids
- Nutrition
- Direct to Consumer
- Subscription
---

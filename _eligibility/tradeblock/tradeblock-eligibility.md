---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Access where illegal prohibited
    text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Tradeblock
provenance_date: '2026-11-10'
provider_name: Tradeblock
provider_slug: tradeblock
slug: tradeblock-eligibility
source_date: '2026-11-10'
source_filename: tradeblock-eligibility.yml
source_heading: Eligibility
source_page: https://tradeblock.zendesk.com/hc/en-us/articles/14865208526871-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tradeblock\naid: tradeblock\nurl: https://tradeblock.zendesk.com/hc/en-us/articles/14865208526871-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Access where illegal prohibited\n  text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/tradeblock/eligibility/tradeblock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tradeblock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sneakers
- Marketplace
- Trading
- Consumer
- E-Commerce
- Mobile App
- Authentication
- Resale
---

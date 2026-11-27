---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Express Delivery is available only in Bengaluru, Mysore, New Delhi, Ghaziabad, Faridabad, Gurugram, Noida, Hyderabad, Chennai, and Pune.
  entity_types:
  - text: Building materials can be supplied to registered businesses (B2B) only.
    type: business
  - text: Individual customers (B2C) or end consumers can't purchase construction materials with Brick&Bolt
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful use
    text: use the Services for any unlawful purpose or contrary to these Terms
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
name: Brick&Bolt
provenance_date: '2026-11-09'
provider_name: Brick&Bolt
provider_slug: brick-and-bolt
slug: brick-and-bolt-eligibility
source_date: '2026-11-09'
source_filename: brick-and-bolt-eligibility.yml
source_heading: Eligibility
source_page: https://www.bricknbolt.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brick&Bolt\naid: brick-and-bolt\nurl: https://www.bricknbolt.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Express Delivery is available only in Bengaluru, Mysore, New Delhi, Ghaziabad, Faridabad, Gurugram, Noida,\n    Hyderabad, Chennai, and Pune.\nentity_types:\n- type: business\n  text: Building materials can be supplied to registered businesses (B2B) only.\n- type: individual\n  text: Individual customers (B2C) or end consumers can't purchase construction materials with Brick&Bolt\nrestricted_uses:\n- summary: No unlawful use\n  text: use the Services\
  \ for any unlawful purpose or contrary to these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brick-and-bolt/eligibility/brick-and-bolt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Brick&Bolt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Construction
- Homebuilding
- Real Estate
- PropTech
- India
- Project Management
---

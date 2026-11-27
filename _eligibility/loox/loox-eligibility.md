---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual over the age of 18, with full legal capacity
    type: individual
  - text: You may only download, install and use the Application if you are a legal corporation or an individual over the age of 18, with full legal capacity.
    type: business
  minimum_age:
    text: an individual over the age of 18, with full legal capacity
    value: '18'
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
name: Loox
provenance_date: '2026-11-09'
provider_name: Loox
provider_slug: loox
slug: loox-eligibility
source_date: '2026-11-09'
source_filename: loox-eligibility.yml
source_heading: Eligibility
source_page: https://loox.app/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loox\naid: loox\nurl: https://loox.app/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual over the age of 18, with full legal capacity\n- type: business\n  text: You may only download, install and use the Application if you are a legal corporation or an individual over\n    the age of 18, with full legal capacity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual over the age of 18, with full legal\
  \ capacity\n"
source_yaml_url: https://artifacts.apis.io/loox/eligibility/loox-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Loox's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Reviews
- Visual
- Shopify
- Marketing
---

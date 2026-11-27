---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Feature availability may vary by region and device
  entity_types:
  - text: Premium and Lifetime subscriptions are tied to individual Kudos accounts and cannot be shared or transferred to other users.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Kudos
provenance_date: '2026-11-09'
provider_name: Kudos
provider_slug: kudos
slug: kudos-eligibility
source_date: '2026-11-09'
source_filename: kudos-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinkudos.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kudos\naid: kudos\nurl: https://www.joinkudos.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Feature availability may vary by region and device\nentity_types:\n- type: individual\n  text: Premium and Lifetime subscriptions are tied to individual Kudos accounts and cannot be shared or transferred\n    to other users.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kudos/eligibility/kudos-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Kudos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit
- Credit Cards
- Rewards
- Cashback
- Fintech
- Consumer Finance
- Personal Finance
- Browser Extension
- Shopping
---

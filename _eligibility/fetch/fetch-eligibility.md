---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be of the age of majority in your jurisdiction to use our Services.
    type: individual
  minimum_age:
    text: You must be of the age of majority in your jurisdiction to use our Services. The Services are not directed at children under 13 years old
    value: age of majority
  restricted_uses:
  - summary: No resale or commercial use of Services
    text: The Services are for your own use only, and you may not resell, lease, or provide them in any other way to anyone else.
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
name: Fetch
provenance_date: '2026-11-09'
provider_name: Fetch
provider_slug: fetch
slug: fetch-eligibility
source_date: '2026-11-09'
source_filename: fetch-eligibility.yml
source_heading: Eligibility
source_page: https://fetch.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fetch\naid: fetch\nurl: https://fetch.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be of the age of majority in your jurisdiction to use our Services.\nrestricted_uses:\n- summary: No resale or commercial use of Services\n  text: The Services are for your own use only, and you may not resell, lease, or provide them in any other way\n    to anyone else.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text:\
  \ You must be of the age of majority in your jurisdiction to use our Services. The Services are not directed\n    at children under 13 years old\n"
source_yaml_url: https://artifacts.apis.io/fetch/eligibility/fetch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fetch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Rewards
- Loyalty
- Shopping
- Receipts
- Mobile App
- Advertising
- Consumer Packaged Goods
- ConsumerRewards
- Retail
- Fintech
---

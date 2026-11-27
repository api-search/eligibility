---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are only available to Users in certain jurisdictions who can use the Services as permitted under applicable law.
  entity_types:
  - text: You must be at least 18 years of age to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
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
name: Royal
provenance_date: '2026-11-10'
provider_name: Royal
provider_slug: royal
slug: royal-eligibility
source_date: '2026-11-10'
source_filename: royal-eligibility.yml
source_heading: Eligibility
source_page: https://royal.io/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Royal\naid: royal\nurl: https://royal.io/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are only available to Users in certain jurisdictions who can use the Services as permitted\n    under applicable law.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/royal/eligibility/royal-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Royal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Royalties
- Cryptocurrency
- Web3
- NFT
- Fan Engagement
---

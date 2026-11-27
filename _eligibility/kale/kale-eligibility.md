---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: We provide the Platform for use only by persons located in the United States and Canada (the " Territory ").
  entity_types:
  - text: This Platform is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Platform is offered and available to users who are 18 years of age or older.
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
name: Kale
provenance_date: '2026-11-09'
provider_name: Kale
provider_slug: kale
slug: kale-eligibility
source_date: '2026-11-09'
source_filename: kale-eligibility.yml
source_heading: Eligibility
source_page: https://www.getkale.com/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kale\naid: kale\nurl: https://www.getkale.com/policies/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: We provide the Platform for use only by persons located in the United States and Canada (the \" Territory\n    \").\nentity_types:\n- type: individual\n  text: This Platform is offered and available to users who are 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Platform is offered and available to users who are 18 years of age or\
  \ older.\n"
source_yaml_url: https://artifacts.apis.io/kale/eligibility/kale-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Kale's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Creator Economy
- User Generated Content
- Influencer Marketing
- Rewards
- Social Media
- Marketing
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Claim makes no representations that the Service is appropriate or available for use in all locations.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your applicable jurisdiction, to register an Account and use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your applicable jurisdiction, to register an Account and use the Service.
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
name: Claim
provenance_date: '2026-11-09'
provider_name: Claim
provider_slug: claim
slug: claim-eligibility
source_date: '2026-11-09'
source_filename: claim-eligibility.yml
source_heading: Eligibility
source_page: https://www.claim.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claim\naid: claim\nurl: https://www.claim.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Claim makes no representations that the Service is appropriate or available for use in all locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your applicable jurisdiction, to register an\n    Account and use the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old,\
  \ or the age of majority in your applicable jurisdiction, to register an\n    Account and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/claim/eligibility/claim-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Claim's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer App
- Rewards
- Loyalty
- Cashback
- Restaurant
- Food and Beverage
- Social Network
- Brand Marketing
- Mobile App
---

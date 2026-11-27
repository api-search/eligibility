---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Advertisers publishing ads may be individuals or professionals.
    type: individual
  - text: Advertisers will create an account and identify themselves as an individual, a real estate developer or a real estate agent.
    type: business
  minimum_age:
    text: If you are acting as an individual, you are not a minor.
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Lifull Connect Group may, from time to time, request Advertisers to submit documents to verify any information provided.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lamudi
provenance_date: '2026-11-09'
provider_name: Lamudi
provider_slug: lamudi
slug: lamudi-eligibility
source_date: '2026-11-09'
source_filename: lamudi-eligibility.yml
source_heading: Eligibility
source_page: https://www.lifullconnect.com/legal-notice-direct/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lamudi\naid: lamudi\nurl: https://www.lifullconnect.com/legal-notice-direct/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Advertisers publishing ads may be individuals or professionals.\n- type: business\n  text: Advertisers will create an account and identify themselves as an individual, a real estate developer or\n    a real estate agent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Lifull Connect Group may, from time to time, request Advertisers to submit documents to verify\
  \ any information\n    provided.\nminimum_age:\n  value: null\n  text: If you are acting as an individual, you are not a minor.\n"
source_yaml_url: https://artifacts.apis.io/lamudi/eligibility/lamudi-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Lamudi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Real Estate
- Property
- Classifieds
- Emerging Markets
- Philippines
- Indonesia
- Mexico
- Listings
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a United States Government embargo or similar laws of other countries where applicable
  entity_types:
  - text: 'Minimum Age: You are an individual at least 18 years of age and at least the legal age of majority in the state in which you reside'
    type: individual
  - text: with companies, such as child care agencies and child care centers, who want to provide those services
    type: business
  minimum_age:
    text: You are an individual at least 18 years of age
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
name: UrbanSitter
provenance_date: '2026-11-10'
provider_name: UrbanSitter
provider_slug: urbansitter
slug: urbansitter-eligibility
source_date: '2026-11-10'
source_filename: urbansitter-eligibility.yml
source_heading: Eligibility
source_page: https://blog.urbansitter.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UrbanSitter\naid: urbansitter\nurl: https://blog.urbansitter.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a United States Government\n    embargo or similar laws of other countries where applicable\nentity_types:\n- type: individual\n  text: 'Minimum Age: You are an individual at least 18 years of age and at least the legal age of majority in the\n    state in which you reside'\n- type: business\n  text: with companies, such as child care agencies and child\
  \ care centers, who want to provide those services\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are an individual at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/urbansitter/eligibility/urbansitter-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from UrbanSitter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Childcare
- Babysitting
- Marketplace
- Caregivers
- Pet Care
- Senior Care
- Tutoring
---

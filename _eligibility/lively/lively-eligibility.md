---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Lively Properties are controlled and offered by Company from its facilities in the United States of America. Lively makes no representations that Lively Properties are appropriate or available for use in other locations.
  entity_types:
  - text: You represent that you are (l) at least thirteen (13) years old; (m) of legal age to form a binding contract
    type: individual
  - text: YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
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
name: Lively
provenance_date: '2026-11-09'
provider_name: Lively
provider_slug: lively
slug: lively-eligibility
source_date: '2026-11-09'
source_filename: lively-eligibility.yml
source_heading: Eligibility
source_page: https://livelyme.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lively\naid: lively\nurl: https://livelyme.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Lively Properties are controlled and offered by Company from its facilities in the United States of America.\n    Lively makes no representations that Lively Properties are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You represent that you are (l) at least thirteen (13) years old; (m) of legal age to form a binding contract\n- type: business\n  text: YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF\
  \ OR THE ENTITY THAT YOU REPRESENT)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/lively/eligibility/lively-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Lively's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Health Tech
- Health Savings Account
- HSA
- FSA
- Employee Benefits
- Financial Services
- Insurance
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Although the Website is accessible worldwide, not all products referenced or described through or on the Website are available to all persons or in all geographic locations or are appropriate or available for use outside the United States.
  entity_types:
  - text: You are at least 18 years of age; this Website is not intended to be directed to children.
    type: individual
  - text: Enter into this agreement on behalf of another person or entity without consent or the legal capacity to make such agreements as a representative of an organization or entity
    type: business
  minimum_age:
    text: You are at least 18 years of age
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
name: Route 92 Medical
provenance_date: '2026-11-10'
provider_name: Route 92 Medical
provider_slug: r92m
slug: r92m-eligibility
source_date: '2026-11-10'
source_filename: r92m-eligibility.yml
source_heading: Eligibility
source_page: https://www.route92medical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Route 92 Medical\naid: r92m\nurl: https://www.route92medical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Although the Website is accessible worldwide, not all products referenced or described through or on the\n    Website are available to all persons or in all geographic locations or are appropriate or available for use\n    outside the United States.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age; this Website is not intended to be directed to children.\n- type: business\n  text: Enter into this agreement on behalf of another\
  \ person or entity without consent or the legal capacity to\n    make such agreements as a representative of an organization or entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/r92m/eligibility/r92m-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Route 92 Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Neurovascular
- Stroke Treatment
- Healthcare
- Medical Technology
- Interventional
---

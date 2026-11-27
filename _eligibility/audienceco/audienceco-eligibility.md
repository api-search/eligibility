---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The purpose of the Site is to provide consumers with ability to receive comparative insurance quotations
    type: individual
  minimum_age:
    text: You may only use the Site if you are 18 years old or older.
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
name: Audienceco
provenance_date: '2026-11-09'
provider_name: Audienceco
provider_slug: audienceco
slug: audienceco-eligibility
source_date: '2026-11-09'
source_filename: audienceco-eligibility.yml
source_heading: Eligibility
source_page: https://audienceco.com/termsandconditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Audienceco\naid: audienceco\nurl: https://audienceco.com/termsandconditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The purpose of the Site is to provide consumers with ability to receive comparative insurance quotations\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may only use the Site if you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/audienceco/eligibility/audienceco-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Audienceco's own page on 2026-11-09.
synthetic: false
tags:
- Performance Marketing
- Audience Acquisition
- Push Exchange
- Lead Generation
- Subscription Marketing
- Publisher Monetisation
- Fraud Prevention
---

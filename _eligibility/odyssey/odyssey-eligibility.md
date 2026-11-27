---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated from facilities in the United States. We make no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age
    type: individual
  - text: you have the right, power, and authority to enter into this Agreement
    type: developer
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    value: '13'
  restricted_uses:
  - summary: Harmful, illegal or inappropriate content via API
    text: use the API with any harmful, illegal, fraudulent, or inappropriate content.
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
name: Odyssey
provenance_date: '2026-11-10'
provider_name: Odyssey
provider_slug: odyssey
slug: odyssey-eligibility
source_date: '2026-11-10'
source_filename: odyssey-eligibility.yml
source_heading: Eligibility
source_page: https://odyssey.systems/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Odyssey\naid: odyssey\nurl: https://odyssey.systems/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated from facilities in the United States. We make no representations\n    that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age\n- type: developer\n  text: you have the right, power, and authority to enter into this Agreement\nrestricted_uses:\n- summary: Harmful, illegal or inappropriate content\
  \ via API\n  text: use the API with any harmful, illegal, fraudulent, or inappropriate content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n"
source_yaml_url: https://artifacts.apis.io/odyssey/eligibility/odyssey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Odyssey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- World Models
- Generative AI
- Video Generation
- Machine Learning
- Real-Time Streaming
- SDK
- WebRTC
---

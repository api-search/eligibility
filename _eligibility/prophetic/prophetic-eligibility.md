---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Product or Services only if you are 18 years or older and capable of forming a binding contract with Prophetic
    type: individual
  minimum_age:
    text: You may use the Product or Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Unauthorized devices
    text: You may not connect any device to the Services which was not manufactured, distributed, or sold by or on behalf of Prophetic
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prophetic
provenance_date: '2026-11-10'
provider_name: Prophetic
provider_slug: prophetic
slug: prophetic-eligibility
source_date: '2026-11-10'
source_filename: prophetic-eligibility.yml
source_heading: Eligibility
source_page: https://www.prophetic.com/tos.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prophetic\naid: prophetic\nurl: https://www.prophetic.com/tos.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Product or Services only if you are 18 years or older and capable of forming a binding contract\n    with Prophetic\nrestricted_uses:\n- summary: Unauthorized devices\n  text: You may not connect any device to the Services which was not manufactured, distributed, or sold by or on\n    behalf of Prophetic\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide\
  \ additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '18'\n  text: You may use the Product or Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/prophetic/eligibility/prophetic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Prophetic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Neurotechnology
- Wearables
- Consumer Hardware
- Lucid Dreaming
- Sleep Technology
- Brain-Computer Interface
- Artificial Intelligence
- Health and Wellness
---

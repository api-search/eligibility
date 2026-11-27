---
api_specs:
- filename: ubtech-subscriptions-api-openapi.yml
  format: yaml
  label: UBTech Subscriptions API
  slug: ubtech-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubtech/openapi/ubtech-subscriptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: UBTECH only permits you to a personal, revocable, non-transferable, non-exclusive, and non-commercial right to access and use this website
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: UBTECH only permits you to a personal, revocable, non-transferable, non-exclusive, and non-commercial right to access and use this website
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
name: UBTech
provenance_date: '2026-11-10'
provider_name: UBTech
provider_slug: ubtech
slug: ubtech-eligibility
source_date: '2026-11-10'
source_filename: ubtech-eligibility.yml
source_heading: Eligibility
source_page: https://www.ubtrobot.com/en/privacy/term-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UBTech\naid: ubtech\nurl: https://www.ubtrobot.com/en/privacy/term-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: UBTECH only permits you to a personal, revocable, non-transferable, non-exclusive, and non-commercial right\n    to access and use this website\nrestricted_uses:\n- summary: No commercial use\n  text: UBTECH only permits you to a personal, revocable, non-transferable, non-exclusive, and non-commercial right\n    to access and use this website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ubtech/eligibility/ubtech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from UBTech's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Humanoid Robots
- Education Technology
- Artificial Intelligence
- Consumer Electronics
- Service Robots
---

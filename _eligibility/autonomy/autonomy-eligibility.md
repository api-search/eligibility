---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: we hereby grant to you a limited ... license to use the App only in the United States
  entity_types:
  - text: The App and the Services are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: The App and the Services are offered and available to users who are 18 years of age or older.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We make a final decision once you select a vehicle, we verify your information, and you consent to various checks, such as driving history and a soft credit check
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Autonomy
provenance_date: '2026-11-09'
provider_name: Autonomy
provider_slug: autonomy
slug: autonomy-eligibility
source_date: '2026-11-09'
source_filename: autonomy-eligibility.yml
source_heading: Eligibility
source_page: https://autonomy.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autonomy\naid: autonomy\nurl: https://autonomy.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: we hereby grant to you a limited ... license to use the App only in the United States\nentity_types:\n- type: individual\n  text: The App and the Services are offered and available to users who are 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We make a final decision once you select a vehicle, we verify your information, and you consent to various\n    checks, such as driving history and a soft credit\
  \ check\nminimum_age:\n  value: '18'\n  text: The App and the Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/autonomy/eligibility/autonomy-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Autonomy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobility
- Subscription
- Car Sharing
- Automotive
---

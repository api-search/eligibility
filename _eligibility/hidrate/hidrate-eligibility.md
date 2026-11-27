---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Hidrate Service if you are over 13 years of age and are not barred from receiving services under applicable law.
    type: individual
  minimum_age:
    text: You represent that you are (a) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Medical use
    text: THE HIDRATE SERVICE IS NOT INTENDED TO DIAGNOSE, TREAT, CURE, OR PREVENT ANY DISEASE.
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
name: Hidrate
provenance_date: '2026-11-09'
provider_name: Hidrate
provider_slug: hidrate
slug: hidrate-eligibility
source_date: '2026-11-09'
source_filename: hidrate-eligibility.yml
source_heading: Eligibility
source_page: https://hidratespark.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hidrate\naid: hidrate\nurl: https://hidratespark.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Hidrate Service if you are over 13 years of age and are not barred from receiving services\n    under applicable law.\nrestricted_uses:\n- summary: Medical use\n  text: THE HIDRATE SERVICE IS NOT INTENDED TO DIAGNOSE, TREAT, CURE, OR PREVENT ANY DISEASE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You represent that you are (a) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/hidrate/eligibility/hidrate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hidrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Smart Water Bottle
- Hydration
- Consumer Hardware
- Wearables
- Health and Fitness
- Bluetooth
- IoT
- E-Commerce
- Shopify
---

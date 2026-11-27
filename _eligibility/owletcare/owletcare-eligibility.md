---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Owlet recommends that caregiver users be at least 18 years old to use our Products.
    type: individual
  minimum_age:
    text: Owlet recommends that caregiver users be at least 18 years old to use our Products.
    value: '18'
  restricted_uses:
  - summary: Prescription medical products
    text: Our medical products may require a prescription, and in those cases, such medical products may only be used by you for the child whom the prescription was issued.
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
name: Owletcare
provenance_date: '2026-11-10'
provider_name: Owletcare
provider_slug: owletcare
slug: owletcare-eligibility
source_date: '2026-11-10'
source_filename: owletcare-eligibility.yml
source_heading: Eligibility
source_page: https://owletcare.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Owletcare\naid: owletcare\nurl: https://owletcare.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Owlet recommends that caregiver users be at least 18 years old to use our Products.\nrestricted_uses:\n- summary: Prescription medical products\n  text: Our medical products may require a prescription, and in those cases, such medical products may only be used\n    by you for the child whom the prescription was issued.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Owlet recommends that caregiver users be at least 18 years old to use our Products.\n"
source_yaml_url: https://artifacts.apis.io/owletcare/eligibility/owletcare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Owletcare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Baby Care
- Health Monitoring
- Consumer Electronics
- Connected Devices
- IoT
- Sleep
- Wearables
---

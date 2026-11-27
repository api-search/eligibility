---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any person or entity who accesses or uses the Services or Products
    type: individual
  - text: applicable when the Protected Property is not a residential single-family property
    type: business
  minimum_age:
    text: Deep Sentinel recommends Authorized Users be adults over the age of 21.
    value: null
  restricted_uses:
  - summary: No professional medical care monitoring
    text: engages in remote monitoring to provide professional medical care for any individual
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain instances, Deep Sentinel may require proof of identity to create or access an Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Deep Sentinel
provenance_date: '2026-11-09'
provider_name: Deep Sentinel
provider_slug: deep-sentinel
slug: deep-sentinel-eligibility
source_date: '2026-11-09'
source_filename: deep-sentinel-eligibility.yml
source_heading: Eligibility
source_page: https://www.deepsentinel.com/end-user-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deep Sentinel\naid: deep-sentinel\nurl: https://www.deepsentinel.com/end-user-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any person or entity who accesses or uses the Services or Products\n- type: business\n  text: applicable when the Protected Property is not a residential single-family property\nrestricted_uses:\n- summary: No professional medical care monitoring\n  text: engages in remote monitoring to provide professional medical care for any individual\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: In certain instances, Deep Sentinel may require proof of identity to create or access an Account\nminimum_age:\n  value: null\n  text: Deep Sentinel recommends Authorized Users be adults over the age of 21.\n"
source_yaml_url: https://artifacts.apis.io/deep-sentinel/eligibility/deep-sentinel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Deep Sentinel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Physical Security
- Video Surveillance
- Home Security
- Artificial Intelligence
- Computer Vision
- Monitoring
- IoT
- Commerce
---

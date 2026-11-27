---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for medical decisions
    text: Medical decisions should never be made using Nanit growth data.
  - summary: Not a medical device
    text: Nanit is not a medical device.
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
name: Nanit
provenance_date: '2026-11-10'
provider_name: Nanit
provider_slug: nanit
slug: nanit-eligibility
source_date: '2026-11-10'
source_filename: nanit-eligibility.yml
source_heading: Eligibility
source_page: https://www.nanit.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nanit\naid: nanit\nurl: https://www.nanit.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for medical decisions\n  text: Medical decisions should never be made using Nanit growth data.\n- summary: Not a medical device\n  text: Nanit is not a medical device.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nanit/eligibility/nanit-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Nanit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Baby Monitor
- Smart Home
- IoT
- Sleep Tracking
- Connected Devices
- Computer Vision
- Parenting
---

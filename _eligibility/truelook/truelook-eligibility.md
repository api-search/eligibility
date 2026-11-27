---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: authorized for sale and use only within the United States and select countries outside the United States
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No biometric identification
    text: specifically shall not be used to gather any biometric identification information of persons on its premises
  - summary: No constant live streaming
    text: It may not be used for constant or uninterrupted streaming.
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
name: TrueLook
provenance_date: '2026-11-10'
provider_name: TrueLook
provider_slug: truelook
slug: truelook-eligibility
source_date: '2026-11-10'
source_filename: truelook-eligibility.yml
source_heading: Eligibility
source_page: https://www.truelook.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueLook\naid: truelook\nurl: https://www.truelook.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: authorized for sale and use only within the United States and select countries outside the United States\nentity_types: []\nrestricted_uses:\n- summary: No biometric identification\n  text: specifically shall not be used to gather any biometric identification information of persons on its premises\n- summary: No constant live streaming\n  text: It may not be used for constant or uninterrupted streaming.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truelook/eligibility/truelook-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from TrueLook's own page on 2026-11-10.
synthetic: false
tags:
- Construction
- Security
- Artificial Intelligence
- Video
- Monitoring
- Software-as-a-Service
---

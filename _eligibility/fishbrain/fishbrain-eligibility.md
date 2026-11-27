---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Fishbrain Shop is available only to U.S. Users of the Services.
  minimum_age:
    text: The Services are intended solely for persons who are 13 years old or such higher age required in your country to use the Services.
    value: '13'
  restricted_uses:
  - summary: No unpermitted or illegal fishing
    text: You agree not to use our Service in connection with any unpermitted, unauthorized, illegal, or dangerous (to you or others) fishing or other activities.
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
name: Fishbrain
provenance_date: '2026-11-09'
provider_name: Fishbrain
provider_slug: fishbrain
slug: fishbrain-eligibility
source_date: '2026-11-09'
source_filename: fishbrain-eligibility.yml
source_heading: Eligibility
source_page: https://fishbrain.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fishbrain\naid: fishbrain\nurl: https://fishbrain.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Fishbrain Shop is available only to U.S. Users of the Services.\nentity_types: []\nrestricted_uses:\n- summary: No unpermitted or illegal fishing\n  text: You agree not to use our Service in connection with any unpermitted, unauthorized, illegal, or dangerous\n    (to you or others) fishing or other activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended solely\
  \ for persons who are 13 years old or such higher age required in your country\n    to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/fishbrain/eligibility/fishbrain-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fishbrain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fishing
- Mobile App
- Social Network
- Outdoor Recreation
- Angling
- Sweden
---

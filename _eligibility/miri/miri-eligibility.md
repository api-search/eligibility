---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be at least 18 years old and located in the United States to use the App.
  entity_types:
  - text: You must be at least 18 years old and located in the United States to use the App.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and located in the United States to use the App.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: we grant you a limited, non-exclusive, non-transferable, revocable license to use the App on an Apple device you own or control for your personal use.
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
name: Miri
provenance_date: '2026-11-10'
provider_name: Miri
provider_slug: miri
slug: miri-eligibility
source_date: '2026-11-10'
source_filename: miri-eligibility.yml
source_heading: Eligibility
source_page: https://miri.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Miri\naid: miri\nurl: https://miri.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be at least 18 years old and located in the United States to use the App.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and located in the United States to use the App.\nrestricted_uses:\n- summary: Personal use only\n  text: we grant you a limited, non-exclusive, non-transferable, revocable license to use the App on an Apple device\n    you own or control for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and located in the United States to use the App.\n"
source_yaml_url: https://artifacts.apis.io/miri/eligibility/miri-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Miri's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellness
- Digital Health
- Telehealth
- Artificial Intelligence
- Patient Engagement
- Weight Loss
- SDK
- Webhook
---

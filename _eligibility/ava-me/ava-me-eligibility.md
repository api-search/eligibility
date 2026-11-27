---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Services, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Free and Community plans personal use only
    text: Ava's Free and Community Plans are intended strictly for personal, non-commercial use.
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
name: Ava
provenance_date: '2026-11-09'
provider_name: Ava
provider_slug: ava-me
slug: ava-me-eligibility
source_date: '2026-11-09'
source_filename: ava-me-eligibility.yml
source_heading: Eligibility
source_page: https://www.ava.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ava\naid: ava-me\nurl: https://www.ava.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Free and Community plans personal use only\n  text: Ava's Free and Community Plans are intended strictly for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Services, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/ava-me/eligibility/ava-me-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ava's own page on 2026-11-09.
synthetic: false
tags:
- Captions
- Transcription
- ASL Interpretation
- Accessibility
- Video Conferencing
- Education
- Healthcare
- Retail
---

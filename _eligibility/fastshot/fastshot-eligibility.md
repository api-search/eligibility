---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the age of digital consent in your jurisdiction) to use the Services. If you are under 18, you represent that you have parental consent.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the age of digital consent in your jurisdiction) to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You must comply with all export control and sanctions laws.
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
name: Fastshot
provenance_date: '2026-11-09'
provider_name: Fastshot
provider_slug: fastshot
slug: fastshot-eligibility
source_date: '2026-11-09'
source_filename: fastshot-eligibility.yml
source_heading: Eligibility
source_page: https://fastshot.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fastshot\naid: fastshot\nurl: https://fastshot.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the age of digital consent in your jurisdiction) to use the Services.\n    If you are under 18, you represent that you have parental consent.\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You must comply with all export control and sanctions laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You\
  \ must be at least 13 years old (or the age of digital consent in your jurisdiction) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/fastshot/eligibility/fastshot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fastshot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Mobile
- App Builder
- Artificial Intelligence
- Mobile Development
- App Development
- Y Combinator
---

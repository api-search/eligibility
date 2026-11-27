---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm, represent and warrant that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You confirm, represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not medical use
    text: are not medical and are not intended to be used as medical devices or as medical instruction.
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
name: Hatch
provenance_date: '2026-11-09'
provider_name: Hatch
provider_slug: hatch-co
slug: hatch-co-eligibility
source_date: '2026-11-09'
source_filename: hatch-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.hatch.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hatch\naid: hatch-co\nurl: https://www.hatch.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm, represent and warrant that you are at least 18 years of age.\nrestricted_uses:\n- summary: Not medical use\n  text: are not medical and are not intended to be used as medical devices or as medical instruction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You confirm, represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/hatch-co/eligibility/hatch-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hatch's own page on 2026-11-09.
synthetic: false
tags:
- Sleep
- Health
- Smart Home
- IoT
- Family
- Wellness
---

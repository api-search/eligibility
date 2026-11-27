---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and legally able to enter into these terms where you live.
    type: individual
  minimum_age:
    text: You must be at least 16 years old and legally able to enter into these terms where you live.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Use the service unlawfully or to harm, defraud, or harass others.
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
name: AnywhereRoles
provenance_date: '2026-11-09'
provider_name: AnywhereRoles
provider_slug: anywhereroles-com
slug: anywhereroles-com-eligibility
source_date: '2026-11-09'
source_filename: anywhereroles-com-eligibility.yml
source_heading: Eligibility
source_page: https://anywhereroles.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnywhereRoles\naid: anywhereroles-com\nurl: https://anywhereroles.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and legally able to enter into these terms where you live.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Use the service unlawfully or to harm, defraud, or harass others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and legally able to enter into these\
  \ terms where you live.\n"
source_yaml_url: https://artifacts.apis.io/anywhereroles-com/eligibility/anywhereroles-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AnywhereRoles's own page on 2026-11-09.
synthetic: false
tags:
- Remote Jobs
- Job Search
- Aggregator
- Software-as-a-Service
- Productivity
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Agency is a validly existing business in its state of formation and where operating
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors and benchmarking
    text: Agency shall not use the Services if Agency is a competitor of Wunderite or for purposes of monitoring the Services’ availability, performance or functionality, or for any other benchmarking or competitive purposes.
  - summary: HIPAA-governed data
    text: The Services are not designed to comply with industry-specific regulations such as the Health Insurance Portability and Accountability Act (HIPAA), so please do not submit any information or data governed by HIPAA to the Services.
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
name: Wunderite
provenance_date: '2026-11-10'
provider_name: Wunderite
provider_slug: wunderite
slug: wunderite-eligibility
source_date: '2026-11-10'
source_filename: wunderite-eligibility.yml
source_heading: Eligibility
source_page: https://wunderite.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wunderite\naid: wunderite\nurl: https://wunderite.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Agency is a validly existing business in its state of formation and where operating\nrestricted_uses:\n- summary: Competitors and benchmarking\n  text: Agency shall not use the Services if Agency is a competitor of Wunderite or for purposes of monitoring the\n    Services’ availability, performance or functionality, or for any other benchmarking or competitive purposes.\n- summary: HIPAA-governed data\n  text: The Services are\
  \ not designed to comply with industry-specific regulations such as the Health Insurance\n    Portability and Accountability Act (HIPAA), so please do not submit any information or data governed by HIPAA\n    to the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wunderite/eligibility/wunderite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Wunderite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- ACORD Forms
- Risk Data
- Digital Signature
- Insurance Applications
- Webhook
---

---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a healthcare provider using HEVA''s platform, the following terms apply to you:'
    type: business
  minimum_age:
    text: null
    value: null
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
name: heva
provenance_date: '2026-11-09'
provider_name: heva
provider_slug: heva
slug: heva-eligibility
source_date: '2026-11-09'
source_filename: heva-eligibility.yml
source_heading: Eligibility
source_page: https://heva.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: heva\naid: heva\nurl: https://heva.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a healthcare provider using HEVA''s platform, the following terms apply to you:'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heva/eligibility/heva-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from heva's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Tourism
- Practice Management
- Appointment Booking
- Artificial Intelligence
- Payments
- Cross-Border Care
- Health Tech
---

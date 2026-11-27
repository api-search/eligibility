---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and services it describes are available only to individuals who are at least 16 years old, unless we specify otherwise.
    type: individual
  minimum_age:
    text: available only to individuals who are at least 16 years old, unless we specify otherwise
    value: '16'
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
name: WeWork
provenance_date: '2026-11-10'
provider_name: WeWork
provider_slug: wework
slug: wework-eligibility
source_date: '2026-11-10'
source_filename: wework-eligibility.yml
source_heading: Eligibility
source_page: https://www.wework.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeWork\naid: wework\nurl: https://www.wework.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and services it describes are available only to individuals who are at least 16 years old, unless\n    we specify otherwise.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: available only to individuals who are at least 16 years old, unless we specify otherwise\n"
source_yaml_url: https://artifacts.apis.io/wework/eligibility/wework-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from WeWork's own page on 2026-11-10.
synthetic: false
tags:
- Co-Working
- Flexible Workspace
- Real Estate
- Workspace Booking
- Workplace Management
- Booking
- Inventory
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://www.trufla.com/legal/acceptable-use-policy/
    text: You or an entity for whom you work
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal use
    text: You will not use the Services for any fraudulent or illegal undertaking, or to interfere in any manner with the normal operation of the Services
  - summary: Truscore Client responsibilities on insurance products
    text: Trufla does not provide or offer any insurance products
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
name: Trufla
provenance_date: '2026-11-10'
provider_name: Trufla
provider_slug: trufla
slug: trufla-eligibility
source_date: '2026-11-10'
source_filename: trufla-eligibility.yml
source_heading: Eligibility
source_page: https://www.trufla.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trufla\naid: trufla\nurl: https://www.trufla.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.trufla.com/legal/acceptable-use-policy/\n  - https://www.trufla.com/legal/terms-of-service/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You or an entity for whom you work\n  source: https://www.trufla.com/legal/acceptable-use-policy/\nrestricted_uses:\n- summary: Fraudulent or illegal use\n  text: You will not use the Services for any fraudulent or illegal undertaking, or to interfere in any manner with\n    the\
  \ normal operation of the Services\n- summary: Truscore Client responsibilities on insurance products\n  text: Trufla does not provide or offer any insurance products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trufla/eligibility/trufla-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Trufla's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Insurtech
- Brokerage
- Agency Management
- CSIO
- Policy Administration
- Quote Bind Issue
- Digital Distribution
---

---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Purchase is offered to people acting for purposes related to their trade or profession.
    type: business
  - text: Where a consumer nonetheless buys, the statutory cancellation and digital content rights are honoured in full rather than excluded.
    type: individual
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
name: binstockly-com
provenance_date: '2026-11-09'
provider_name: binstockly-com
provider_slug: binstockly-com
slug: binstockly-com-eligibility
source_date: '2026-11-09'
source_filename: binstockly-com-eligibility.yml
source_heading: Eligibility
source_page: https://binstockly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: binstockly-com\naid: binstockly-com\nurl: https://binstockly.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Purchase is offered to people acting for purposes related to their trade or profession.\n- type: individual\n  text: Where a consumer nonetheless buys, the statutory cancellation and digital content rights are honoured in\n    full rather than excluded.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/binstockly-com/eligibility/binstockly-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from binstockly-com's own page on 2026-11-09.
synthetic: false
tags:
- Auto Parts
- Inventory
- Software
- Small Business
---

---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the buyer identified in the Order (“ Buyer ”), or Buyer’s subsidiaries or affiliates
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Unless otherwise specified in the Order, and subject to credit approval, the terms of payment are net thirty (30) days from the date of invoice.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HZO
provenance_date: '2026-11-09'
provider_name: HZO
provider_slug: hzo
slug: hzo-eligibility
source_date: '2026-11-09'
source_filename: hzo-eligibility.yml
source_heading: Eligibility
source_page: https://hzo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HZO\naid: hzo\nurl: https://hzo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the buyer identified in the Order (“ Buyer ”), or Buyer’s subsidiaries or affiliates\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Unless otherwise specified in the Order, and subject to credit approval, the terms of payment are net thirty\n    (30) days from the date of invoice.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hzo/eligibility/hzo-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from HZO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electronics
- Manufacturing
- Coatings
- Parylene
- Materials Science
- Conformal Coating
- Hardware
---

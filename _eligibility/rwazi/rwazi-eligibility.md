---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Platform as a business entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Data
    text: store, transmit or transfer any Restricted Data within or in connection with the Platform
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
name: Rwazi
provenance_date: '2026-11-10'
provider_name: Rwazi
provider_slug: rwazi
slug: rwazi-eligibility
source_date: '2026-11-10'
source_filename: rwazi-eligibility.yml
source_heading: Eligibility
source_page: https://rwazi.com/general-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rwazi\naid: rwazi\nurl: https://rwazi.com/general-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Platform as a business entity\nrestricted_uses:\n- summary: Restricted Data\n  text: store, transmit or transfer any Restricted Data within or in connection with the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rwazi/eligibility/rwazi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rwazi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Intelligence
- Consumer Data
- Decision AI
- Analytics
- Emerging Markets
- Data Provider
---

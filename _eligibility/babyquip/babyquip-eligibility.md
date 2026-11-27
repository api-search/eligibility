---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction to access and use the Platform.
    type: individual
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction to access and use the Platform.
    value: age of majority
  restricted_uses:
  - summary: Off-platform services
    text: You are not permitted to request or pay for Services (defined below) outside of the Platform.
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
name: BabyQuip
provenance_date: '2026-11-09'
provider_name: BabyQuip
provider_slug: babyquip
slug: babyquip-eligibility
source_date: '2026-11-09'
source_filename: babyquip-eligibility.yml
source_heading: Eligibility
source_page: https://www.babyquip.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BabyQuip\naid: babyquip\nurl: https://www.babyquip.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction to access and use the Platform.\nrestricted_uses:\n- summary: Off-platform services\n  text: You are not permitted to request or pay for Services (defined below) outside of the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your\
  \ jurisdiction to access and use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/babyquip/eligibility/babyquip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BabyQuip's own page on 2026-11-09.
synthetic: false
tags:
- BabyGear
- Rentals
- Marketplace
- Travel
- Family
---

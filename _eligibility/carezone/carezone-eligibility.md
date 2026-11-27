---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Insurance Services may not be available in every state.
  entity_types:
  - text: The Site and CareZone Services are intended solely for persons who are 13 or older.
    type: individual
  minimum_age:
    text: The Site and CareZone Services are intended solely for persons who are 13 or older.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Neither the CareZone Services, nor the Site, nor any CareZone Content, nor any Profile Content may be used in any instance for any unlawful purpose.
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
name: Carezone
provenance_date: '2026-11-09'
provider_name: Carezone
provider_slug: carezone
slug: carezone-eligibility
source_date: '2026-11-09'
source_filename: carezone-eligibility.yml
source_heading: Eligibility
source_page: https://carezone.com/tos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carezone\naid: carezone\nurl: https://carezone.com/tos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Insurance Services may not be available in every state.\nentity_types:\n- type: individual\n  text: The Site and CareZone Services are intended solely for persons who are 13 or older.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Neither the CareZone Services, nor the Site, nor any CareZone Content, nor any Profile Content may be used\n    in any instance for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '13'\n  text: The Site and CareZone Services are intended solely for persons who are 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/carezone/eligibility/carezone-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carezone's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Health
- Medication Management
- Digital Health
- Pharmacy
- Consumer Health
- Care Coordination
---

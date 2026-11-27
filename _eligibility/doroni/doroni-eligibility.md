---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you affirm that you are at least 18 years old or have the consent of a parent or guardian.
    type: individual
  minimum_age:
    text: By using the Site, you affirm that you are at least 18 years old or have the consent of a parent or guardian.
    value: '18'
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
name: Doroni
provenance_date: '2026-11-09'
provider_name: Doroni
provider_slug: doroni
slug: doroni-eligibility
source_date: '2026-11-09'
source_filename: doroni-eligibility.yml
source_heading: Eligibility
source_page: https://doroni.io/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doroni\naid: doroni\nurl: https://doroni.io/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you affirm that you are at least 18 years old or have the consent of a parent or guardian.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you affirm that you are at least 18 years old or have the consent of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/doroni/eligibility/doroni-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Doroni's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AirMobility
- eVTOL
- FlyingCars
- Aerospace
---

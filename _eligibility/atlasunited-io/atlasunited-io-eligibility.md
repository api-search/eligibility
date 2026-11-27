---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, able to enter binding contracts, and use the service only for lawful business purposes.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Lawful business purposes only
    text: use the service only for lawful business purposes.
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
name: Atlas United
provenance_date: '2026-11-09'
provider_name: Atlas United
provider_slug: atlasunited-io
slug: atlasunited-io-eligibility
source_date: '2026-11-09'
source_filename: atlasunited-io-eligibility.yml
source_heading: Eligibility
source_page: https://atlasunited.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas United\naid: atlasunited-io\nurl: https://atlasunited.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, able to enter binding contracts, and use the service only for lawful\n    business purposes.\nrestricted_uses:\n- summary: Lawful business purposes only\n  text: use the service only for lawful business purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/atlasunited-io/eligibility/atlasunited-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Atlas United's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Weather
- Forecast
- Storm
- Geolocation
---

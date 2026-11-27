---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer in the EU, you can withdraw from a new subscription within 14 days of subscribing by emailing us.
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
name: Open-Elevation
provenance_date: '2026-11-10'
provider_name: Open-Elevation
provider_slug: open-elevation
slug: open-elevation-eligibility
source_date: '2026-11-10'
source_filename: open-elevation-eligibility.yml
source_heading: Eligibility
source_page: https://open-elevation.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Open-Elevation\naid: open-elevation\nurl: https://open-elevation.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer in the EU, you can withdraw from a new subscription within 14 days of subscribing\n    by emailing us.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/open-elevation/eligibility/open-elevation-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Open-Elevation's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Elevation
- Geospatial
- Open Source
- Free
---

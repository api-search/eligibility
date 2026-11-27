---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If representing an organization, you must have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into this Agreement to integrate our public service into a website or application.
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
name: OpenFreeMap vector styles
provenance_date: '2026-11-10'
provider_name: OpenFreeMap vector styles
provider_slug: openfreemap
slug: openfreemap-eligibility
source_date: '2026-11-10'
source_filename: openfreemap-eligibility.yml
source_heading: Eligibility
source_page: https://openfreemap.org/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenFreeMap vector styles\naid: openfreemap\nurl: https://openfreemap.org/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If representing an organization, you must have authority to bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into this Agreement to integrate our public\n    service into a website or application.\n"
source_yaml_url: https://artifacts.apis.io/openfreemap/eligibility/openfreemap-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from OpenFreeMap vector styles's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Source
- Mapping
- GIS
- Vector Tiles
- Free Hosting
---

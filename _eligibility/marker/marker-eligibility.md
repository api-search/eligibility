---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be at least 18 years old and have been invited to take part in the alpha testing phase.
    type: individual
  minimum_age:
    text: You need to be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal, harmful or abusive conduct
    text: You should not use Marker to do anything illegal, harmful, or that you wouldn't be comfortable explaining to us.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: You need to be at least 18 years old and have been invited to take part in the alpha testing phase.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Marker
provenance_date: '2026-11-10'
provider_name: Marker
provider_slug: marker
slug: marker-eligibility
source_date: '2026-11-10'
source_filename: marker-eligibility.yml
source_heading: Eligibility
source_page: https://marker.page/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Marker\naid: marker\nurl: https://marker.page/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be at least 18 years old and have been invited to take part in the alpha testing phase.\nrestricted_uses:\n- summary: Illegal, harmful or abusive conduct\n  text: You should not use Marker to do anything illegal, harmful, or that you wouldn't be comfortable explaining\n    to us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: You need to be at least 18 years old and have been invited to take\
  \ part in the alpha testing phase.\nminimum_age:\n  value: '18'\n  text: You need to be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/marker/eligibility/marker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Marker's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Future Of Work
- Writing
- Productivity
- Text Editor
- Web App
---

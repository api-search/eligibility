---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Services.
    value: '16'
  restricted_uses:
  - summary: Competing use
    text: use or display the Services in competition with us, to develop competing products or services
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
name: boombox.io
provenance_date: '2026-11-09'
provider_name: boombox.io
provider_slug: boombox-io
slug: boombox-io-eligibility
source_date: '2026-11-09'
source_filename: boombox-io-eligibility.yml
source_heading: Eligibility
source_page: https://boombox.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: boombox.io\naid: boombox-io\nurl: https://boombox.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Competing use\n  text: use or display the Services in competition with us, to develop competing products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: You must be at least 16 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/boombox-io/eligibility/boombox-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from boombox.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Distribution
- AI Tools
- Platform
---

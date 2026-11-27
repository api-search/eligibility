---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of a company or other business, you further warrant that you personally have the authority to bind that company or business
    type: business
  minimum_age:
    text: you are at least 18 years old.
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
name: umbhost-net
provenance_date: '2026-11-10'
provider_name: umbhost-net
provider_slug: umbhost-net
slug: umbhost-net-eligibility
source_date: '2026-11-10'
source_filename: umbhost-net-eligibility.yml
source_heading: Eligibility
source_page: https://umbhost.net/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: umbhost-net\naid: umbhost-net\nurl: https://umbhost.net/legal/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of a company or other business, you further warrant that you personally have\n    the authority to bind that company or business\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/umbhost-net/eligibility/umbhost-net-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from umbhost-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hosting
- Cloud
- Sustainable
- DevOps
---

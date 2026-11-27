---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: to any individual or entity ("Customer," "you," or "your")
    type: individual
  - text: to any individual or entity ("Customer," "you," or "your")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: Use the Service only for lawful purposes
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
name: Hostie
provenance_date: '2026-11-09'
provider_name: Hostie
provider_slug: hostie
slug: hostie-eligibility
source_date: '2026-11-09'
source_filename: hostie-eligibility.yml
source_heading: Eligibility
source_page: https://hostie.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hostie\naid: hostie\nurl: https://hostie.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: to any individual or entity (\"Customer,\" \"you,\" or \"your\")\n- type: business\n  text: to any individual or entity (\"Customer,\" \"you,\" or \"your\")\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Use the Service only for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hostie/eligibility/hostie-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Hostie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Hospitality
- Conversational AI
- Voice AI
- Guest Communication
- Reservations
- Restaurant Technology
---

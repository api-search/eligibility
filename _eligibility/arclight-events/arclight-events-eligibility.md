---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 to host events.
    type: individual
  minimum_age:
    text: You must be at least 18 to host events.
    value: '18'
  restricted_uses:
  - summary: Hosting restrictions
    text: We may remove listings or suspend hosting privileges for fraudulent, unsafe, or misrepresented events.
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
name: Arclight
provenance_date: '2026-11-09'
provider_name: Arclight
provider_slug: arclight-events
slug: arclight-events-eligibility
source_date: '2026-11-09'
source_filename: arclight-events-eligibility.yml
source_heading: Eligibility
source_page: https://arclight.events/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arclight\naid: arclight-events\nurl: https://arclight.events/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 to host events.\nrestricted_uses:\n- summary: Hosting restrictions\n  text: We may remove listings or suspend hosting privileges for fraudulent, unsafe, or misrepresented events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 to host events.\n"
source_yaml_url: https://artifacts.apis.io/arclight-events/eligibility/arclight-events-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Arclight's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Artificial Intelligence
- Tech
- Concierge
- Planner
---

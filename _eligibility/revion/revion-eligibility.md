---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: They apply to the business that signs an Order Form or uses the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Contacting people without lawful basis or after opt-out
    text: (b) contact anyone without a lawful basis or after they have opted out;
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
name: Revion
provenance_date: '2026-11-10'
provider_name: Revion
provider_slug: revion
slug: revion-eligibility
source_date: '2026-11-10'
source_filename: revion-eligibility.yml
source_heading: Eligibility
source_page: https://revion.inc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revion\naid: revion\nurl: https://revion.inc/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: They apply to the business that signs an Order Form or uses the Services\nrestricted_uses:\n- summary: Contacting people without lawful basis or after opt-out\n  text: (b) contact anyone without a lawful basis or after they have opted out;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/revion/eligibility/revion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Revion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automotive
- Dealership Service
- Voice AI
- Repair Orders
- Workflow Automation
- Y Combinator
---

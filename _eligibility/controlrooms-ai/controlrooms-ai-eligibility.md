---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are entering into this Agreement on behalf of a company, organization, or another legal entity (an “Entity”), You are agreeing to this Agreement for that Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for time- or mission-critical functions
    text: Customer acknowledges and agrees that the ControlRooms Solution will not be used, and is not licensed for use, to enable any of Customer’s time-critical or mission-critical functions.
  - summary: No operational safety decisions
    text: Customer acknowledges that the ControlRooms Solution is not a safety protocol system or equipment control system, and Customer agrees it will not rely on the Output or ControlRooms Solution for any operational decisions related to Customer’s equipment, facilities, or business.
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
name: ControlRooms.ai
provenance_date: '2026-11-09'
provider_name: ControlRooms.ai
provider_slug: controlrooms-ai
slug: controlrooms-ai-eligibility
source_date: '2026-11-09'
source_filename: controlrooms-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.controlrooms.ai/terms-of-service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ControlRooms.ai\naid: controlrooms-ai\nurl: https://www.controlrooms.ai/terms-of-service-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are entering into this Agreement on behalf of a company, organization, or another legal entity (an\n    “Entity”), You are agreeing to this Agreement for that Entity\nrestricted_uses:\n- summary: Not for time- or mission-critical functions\n  text: Customer acknowledges and agrees that the ControlRooms Solution will not be used, and is not licensed for\n    use, to enable any of Customer’s\
  \ time-critical or mission-critical functions.\n- summary: No operational safety decisions\n  text: Customer acknowledges that the ControlRooms Solution is not a safety protocol system or equipment control\n    system, and Customer agrees it will not rely on the Output or ControlRooms Solution for any operational decisions\n    related to Customer’s equipment, facilities, or business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/controlrooms-ai/eligibility/controlrooms-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ControlRooms.ai's own page on 2026-11-09.
synthetic: false
tags:
- Anomaly Detection
- Plant Operations
- AI Troubleshooting
---

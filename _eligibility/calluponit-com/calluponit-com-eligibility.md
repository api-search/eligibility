---
api_specs:
- filename: calluponit-com-openapi-generated.yml
  format: yaml
  label: CallUpOnIt API
  slug: calluponit-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calluponit-com/openapi/_ae-authored/calluponit-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must use the service only for lawful, personal, non-abusive purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies or safety-critical use
    text: The service is not designed for emergencies, medical alerts, safety-critical reminders, or any use where delayed or failed delivery could cause harm.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification codes are used to confirm your phone number and sign you in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CallUpOnIt
provenance_date: '2026-11-09'
provider_name: CallUpOnIt
provider_slug: calluponit-com
slug: calluponit-com-eligibility
source_date: '2026-11-09'
source_filename: calluponit-com-eligibility.yml
source_heading: Eligibility
source_page: https://calluponit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallUpOnIt\naid: calluponit-com\nurl: https://calluponit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must use the service only for lawful, personal, non-abusive purposes\nrestricted_uses:\n- summary: Not for emergencies or safety-critical use\n  text: The service is not designed for emergencies, medical alerts, safety-critical reminders, or any use where\n    delayed or failed delivery could cause harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification codes are used to confirm\
  \ your phone number and sign you in.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calluponit-com/eligibility/calluponit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CallUpOnIt's own page on 2026-11-09.
synthetic: false
tags:
- Reminders
- voice-calls
- Email Scheduling
- AI Agents
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a US government embargo or designated a "terrorist supporting" country, and that you are not on any US government list of prohibited or restricted parties.
  entity_types:
  - text: You must be at least 16 years old to use Juno.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use Juno.
    value: '16'
  restricted_uses:
  - summary: Not a medical service
    text: Juno is NOT a licensed medical professional or therapist, and does not provide therapy, counseling, diagnosis, or treatment.
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
name: Juno Chat
provenance_date: '2026-11-09'
provider_name: Juno Chat
provider_slug: juno-chat
slug: juno-chat-eligibility
source_date: '2026-11-09'
source_filename: juno-chat-eligibility.yml
source_heading: Eligibility
source_page: https://junocompanion.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juno Chat\naid: juno-chat\nurl: https://junocompanion.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a US government embargo or designated a \"terrorist\n    supporting\" country, and that you are not on any US government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use Juno.\nrestricted_uses:\n- summary: Not a medical service\n  text: Juno is NOT a licensed medical professional or therapist, and does not provide therapy, counseling,\
  \ diagnosis,\n    or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Juno.\n"
source_yaml_url: https://artifacts.apis.io/juno-chat/eligibility/juno-chat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Juno Chat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Chronic Illness
- AI Health Assistant
- Symptom Tracking
- Consumer Health
- Mobile App
- Y Combinator
---

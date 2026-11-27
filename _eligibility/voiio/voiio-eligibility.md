---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: und Unternehmen, juristischen Personen des öffentlichen Rechts oder öffentlich-rechtlichen Sondervermögen
    type: business
  - text: juristischen Personen des öffentlichen Rechts
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorised use
    text: Bei unberechtigter Nutzung ist voiio berechtigt, eine angemessene Entschädigung auf Grundlage der zusätzlichen Nutzer zu berechnen.
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
name: Voiio
provenance_date: '2026-11-10'
provider_name: Voiio
provider_slug: voiio
slug: voiio-eligibility
source_date: '2026-11-10'
source_filename: voiio-eligibility.yml
source_heading: Eligibility
source_page: https://voiio.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voiio\naid: voiio\nurl: https://voiio.de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: und Unternehmen, juristischen Personen des öffentlichen Rechts oder öffentlich-rechtlichen Sondervermögen\n- type: government\n  text: juristischen Personen des öffentlichen Rechts\nrestricted_uses:\n- summary: Unauthorised use\n  text: Bei unberechtigter Nutzung ist voiio berechtigt, eine angemessene Entschädigung auf Grundlage der zusätzlichen\n    Nutzer zu berechnen.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voiio/eligibility/voiio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Voiio's own page on 2026-11-10.
synthetic: false
tags:
- Employee Assistance
- Human Resources
- Wellbeing
- Work-Life Balance
- EAP
- Germany
---

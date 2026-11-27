---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Der Partner handelt in eigenem Namen und auf eigenes Risiko als Unternehmer im Sinne des geltenden deutschen Rechts.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-compete during term
    text: Während der Laufzeit dieser Vereinbarung ist es dem Partner untersagt, an den Partner-Standorten unmittelbar oder mittelbar
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Der Partner muss den Status als Unternehmer nachweisen, indem er seinen Firmennamen, den Nachweis seiner Eintragung, seine Rechtsform, andere Einzelheiten und alle weiteren relevanten Unterlagen vorlegt.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lanch
provenance_date: '2026-11-09'
provider_name: Lanch
provider_slug: lanch
slug: lanch-eligibility
source_date: '2026-11-09'
source_filename: lanch-eligibility.yml
source_heading: Eligibility
source_page: https://lanch.com/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lanch\naid: lanch\nurl: https://lanch.com/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Der Partner handelt in eigenem Namen und auf eigenes Risiko als Unternehmer im Sinne des geltenden deutschen\n    Rechts.\nrestricted_uses:\n- summary: Non-compete during term\n  text: Während der Laufzeit dieser Vereinbarung ist es dem Partner untersagt, an den Partner-Standorten unmittelbar\n    oder mittelbar\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Der Partner muss den Status als Unternehmer nachweisen,\
  \ indem er seinen Firmennamen, den Nachweis seiner\n    Eintragung, seine Rechtsform, andere Einzelheiten und alle weiteren relevanten Unterlagen vorlegt.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lanch/eligibility/lanch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Lanch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Food
- Food Tech
- Food Delivery
- Restaurant
- Franchise
- Ghost Kitchen
- Creator Economy
- Germany
---

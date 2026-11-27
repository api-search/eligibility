---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not use or receive the Service where doing so would violate applicable export-control or sanctions law, including prohibited dealings with restricted persons.
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract.
    type: individual
  - text: If you accept on behalf of a company or other organization, you represent that you are authorized to bind it
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Prohibited data submission
    text: Do not submit credentials, secrets or deliberately collected personal identifiers through project metadata.
  - summary: Export-controlled use
    text: You must not use the Service for an end use prohibited by applicable export-control law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may pause admissions or introduce waiting lists when capacity is reached.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brain Scanner
provenance_date: '2026-11-09'
provider_name: Brain Scanner
provider_slug: brainscanner-dev
slug: brainscanner-dev-eligibility
source_date: '2026-11-09'
source_filename: brainscanner-dev-eligibility.yml
source_heading: Eligibility
source_page: https://brainscanner.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brain Scanner\naid: brainscanner-dev\nurl: https://brainscanner.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not use or receive the Service where doing so would violate applicable export-control or sanctions\n    law, including prohibited dealings with restricted persons.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract.\n- type: business\n  text: If you accept on behalf of a company or other organization, you represent that you are authorized to bind\n    it\nrestricted_uses:\n- summary: Prohibited\
  \ data submission\n  text: Do not submit credentials, secrets or deliberately collected personal identifiers through project metadata.\n- summary: Export-controlled use\n  text: You must not use the Service for an end use prohibited by applicable export-control law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may pause admissions or introduce waiting lists when capacity is reached.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/brainscanner-dev/eligibility/brainscanner-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Brain Scanner's own page on 2026-11-09.
synthetic: false
tags:
- AI Coding
- Code Review
- Session Replay
- Task Queue
---

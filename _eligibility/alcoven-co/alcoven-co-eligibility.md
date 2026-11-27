---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Alcoven is for people aged 16 or over.
    type: individual
  - text: If you use Alcoven for a company or another legal entity, you confirm that you may accept these terms for it, and “you” then means both you and that entity.
    type: business
  minimum_age:
    text: Alcoven is for people aged 16 or over.
    value: '16'
  restricted_uses:
  - summary: Non-consensual sexual content
    text: make sexual content of anyone without their consent, including intimate images and deepfakes, or any sexual content involving a minor
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
name: Alcoven
provenance_date: '2026-11-09'
provider_name: Alcoven
provider_slug: alcoven-co
slug: alcoven-co-eligibility
source_date: '2026-11-09'
source_filename: alcoven-co-eligibility.yml
source_heading: Eligibility
source_page: https://alcoven.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alcoven\naid: alcoven-co\nurl: https://alcoven.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Alcoven is for people aged 16 or over.\n- type: business\n  text: If you use Alcoven for a company or another legal entity, you confirm that you may accept these terms for\n    it, and “you” then means both you and that entity.\nrestricted_uses:\n- summary: Non-consensual sexual content\n  text: make sexual content of anyone without their consent, including intimate images and deepfakes, or any sexual\n    content involving a minor\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Alcoven is for people aged 16 or over.\n"
source_yaml_url: https://artifacts.apis.io/alcoven-co/eligibility/alcoven-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alcoven's own page on 2026-11-09.
synthetic: false
tags:
- AI Collaboration
- Project Management
- Team Collaboration
- Productivity
- ChatGPT
- Claude
---

---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: De abonnementen zijn bedoeld voor ondernemers en organisaties die handelen voor beroep of bedrijf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Public and destructive WordPress actions need approval
    text: Publieke en destructieve WordPress-acties vragen afzonderlijke goedkeuring en controle achteraf.
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
name: Samautomation
provenance_date: '2026-11-09'
provider_name: Samautomation
provider_slug: beheerjewp-nl
slug: beheerjewp-nl-eligibility
source_date: '2026-11-09'
source_filename: beheerjewp-nl-eligibility.yml
source_heading: Eligibility
source_page: https://beheerjewp.nl/voorwaarden
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Samautomation\naid: beheerjewp-nl\nurl: https://beheerjewp.nl/voorwaarden\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: De abonnementen zijn bedoeld voor ondernemers en organisaties die handelen voor beroep of bedrijf.\nrestricted_uses:\n- summary: Public and destructive WordPress actions need approval\n  text: Publieke en destructieve WordPress-acties vragen afzonderlijke goedkeuring en controle achteraf.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beheerjewp-nl/eligibility/beheerjewp-nl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Samautomation's own page on 2026-11-09.
synthetic: false
tags:
- WordPress
- Artificial Intelligence
- ChatGPT
- Claude
- Dutch
- Software-as-a-Service
---

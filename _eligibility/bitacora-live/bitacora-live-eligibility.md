---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: You may not use Bitácora if you are in a country or territory subject to comprehensive sanctions by the United States, the European Union or the United Nations (currently including Cuba, Iran, North Korea and the Crimea, Donetsk and Luhansk regions)
  entity_types:
  - text: You must be at least 16 years old
    type: individual
  - text: If you accept on behalf of a company, you confirm that you can bind it, and “you” includes that company.
    type: business
  minimum_age:
    text: You must be at least 16 years old . If you are in Brazil, you must be at least 18 years old .
    value: '16'
  restricted_uses:
  - summary: Sanctioned countries or persons
    text: Nor may you use it to provide services to those persons or territories.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitácora
provenance_date: '2026-11-09'
provider_name: Bitácora
provider_slug: bitacora-live
slug: bitacora-live-eligibility
source_date: '2026-11-09'
source_filename: bitacora-live-eligibility.yml
source_heading: Eligibility
source_page: https://bitacora.live/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitácora\naid: bitacora-live\nurl: https://bitacora.live/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: You may not use Bitácora if you are in a country or territory subject to comprehensive sanctions by the\n    United States, the European Union or the United Nations (currently including Cuba, Iran, North Korea and the\n    Crimea, Donetsk and Luhansk regions)\nentity_types:\n- type: individual\n  text: You must be at least 16 years old\n- type: business\n  text: If you accept on behalf of a company, you confirm that you can bind it, and “you” includes\
  \ that company.\nrestricted_uses:\n- summary: Sanctioned countries or persons\n  text: Nor may you use it to provide services to those persons or territories.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old . If you are in Brazil, you must be at least 18 years old .\n"
source_yaml_url: https://artifacts.apis.io/bitacora-live/eligibility/bitacora-live-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bitácora's own page on 2026-11-09.
synthetic: false
tags:
- Design
- Collaboration
- UI/UX
- Software-as-a-Service
- Free Tier
---

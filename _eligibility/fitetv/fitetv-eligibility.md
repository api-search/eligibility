---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you have reached the age of majority in the jurisdiction of your residence
    type: individual
  minimum_age:
    text: You affirm that you have reached the age of majority in the jurisdiction of your residence, or you are an emancipated minor
    value: age of majority
  restricted_uses:
  - summary: Personal and residential use only
    text: ALL Services are provided solely for personal and residential use.
  - summary: Commercial establishments need a licence
    text: Commercial establishments in any jurisdiction throughout the world are required to obtain a license from Flipps or the Content providers for all Services.
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
name: Fitetv
provenance_date: '2026-11-09'
provider_name: Fitetv
provider_slug: fitetv
slug: fitetv-eligibility
source_date: '2026-11-09'
source_filename: fitetv-eligibility.yml
source_heading: Eligibility
source_page: https://www.trillertv.com/p/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fitetv\naid: fitetv\nurl: https://www.trillertv.com/p/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you have reached the age of majority in the jurisdiction of your residence\nrestricted_uses:\n- summary: Personal and residential use only\n  text: ALL Services are provided solely for personal and residential use.\n- summary: Commercial establishments need a licence\n  text: Commercial establishments in any jurisdiction throughout the world are required to obtain a license from\n    Flipps or the\
  \ Content providers for all Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You affirm that you have reached the age of majority in the jurisdiction of your residence, or you are an\n    emancipated minor\n"
source_yaml_url: https://artifacts.apis.io/fitetv/eligibility/fitetv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fitetv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- Video
- Sports
- Combat Sports
- Boxing
- MMA
- Wrestling
- Pay Per View
- Entertainment
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 13 years or older and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 13 years or older
    value: '13'
  restricted_uses:
  - summary: No use for accessing unlicensed content
    text: 'You represent and warrant that: (i) you will not use our Services for accessing any Content, including music Content, that you do not have the right to access'
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
name: AmpMe
provenance_date: '2026-11-09'
provider_name: AmpMe
provider_slug: ampme
slug: ampme-eligibility
source_date: '2026-11-09'
source_filename: ampme-eligibility.yml
source_heading: Eligibility
source_page: https://ampme.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AmpMe\naid: ampme\nurl: https://ampme.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 13 years or older and are not barred from using the Services under\n    applicable law.\nrestricted_uses:\n- summary: No use for accessing unlicensed content\n  text: 'You represent and warrant that: (i) you will not use our Services for accessing any Content, including\n    music Content, that you do not have the right to access'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/ampme/eligibility/ampme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AmpMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Audio
- Streaming
- Consumer
- Mobile
- Entertainment
---

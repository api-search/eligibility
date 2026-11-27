---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  - text: THE AUTHORITY TO ENTER INTO THESE TERMS PERSONALLY OR ON BEHALF OF THE ENTITY YOU REPRESENT
    type: business
  minimum_age:
    text: You affirm that you are more than 18 years of age
    value: '18'
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
name: Xfactor.io
provenance_date: '2026-11-10'
provider_name: Xfactor.io
provider_slug: xfactorio
slug: xfactorio-eligibility
source_date: '2026-11-10'
source_filename: xfactorio-eligibility.yml
source_heading: Eligibility
source_page: https://www.xfactor.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xfactor.io\naid: xfactorio\nurl: https://www.xfactor.io/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are more than 18 years of age, or an emancipated minor, or possess legal parental or\n    guardian consent\n- type: business\n  text: THE AUTHORITY TO ENTER INTO THESE TERMS PERSONALLY OR ON BEHALF OF THE ENTITY YOU REPRESENT\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are more than\
  \ 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/xfactorio/eligibility/xfactorio-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Xfactor.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Services
- Revenue Operations
- Artificial Intelligence
- Analytics
- Forecasting
- Go-To-Market
- Software-as-a-Service
---

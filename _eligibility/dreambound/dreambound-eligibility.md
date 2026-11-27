---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Site Offerings are available only to individuals who: (a) can enter into legally binding contracts under applicable law; and (b) are eighteen (18) years of age or older'
    type: individual
  minimum_age:
    text: are eighteen (18) years of age or older (or the applicable age of majority, if greater than eighteen (18) years of age in their respective jurisdictions of residency)
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
name: Dreambound
provenance_date: '2026-11-09'
provider_name: Dreambound
provider_slug: dreambound
slug: dreambound-eligibility
source_date: '2026-11-09'
source_filename: dreambound-eligibility.yml
source_heading: Eligibility
source_page: https://dreambound.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dreambound\naid: dreambound\nurl: https://dreambound.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The Site Offerings are available only to individuals who: (a) can enter into legally binding contracts\n    under applicable law; and (b) are eighteen (18) years of age or older'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are eighteen (18) years of age or older (or the applicable age of majority, if greater than\
  \ eighteen (18)\n    years of age in their respective jurisdictions of residency)\n"
source_yaml_url: https://artifacts.apis.io/dreambound/eligibility/dreambound-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Dreambound's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Workforce Development
- Career Training
- Vocational Education
- Marketplace
- Healthcare Training
---

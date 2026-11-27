---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use Lumosity you must be, and represent and warrant that you are, of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age) and competent to agree to these TOS.
    type: individual
  minimum_age:
    text: 18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age
    value: '13'
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
name: Lumosity
provenance_date: '2026-11-10'
provider_name: Lumosity
provider_slug: lumosity
slug: lumosity-eligibility
source_date: '2026-11-10'
source_filename: lumosity-eligibility.yml
source_heading: Eligibility
source_page: https://www.lumosity.com/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lumosity\naid: lumosity\nurl: https://www.lumosity.com/en/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use Lumosity you must be, and represent and warrant that you are, of legal age (18 years of age or older\n    or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age) and competent\n    to agree to these TOS.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: 18 years of age or\
  \ older or otherwise of legal age in your jurisdiction, or, if you have parental consent,\n    13 years of age\n"
source_yaml_url: https://artifacts.apis.io/lumosity/eligibility/lumosity-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Lumosity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Brain Training
- Cognitive Training
- Consumer App
- Health and Wellness
- Mobile
- Games
---

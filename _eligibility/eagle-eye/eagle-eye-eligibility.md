---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You/your refers to you, the individual accessing the API Documentation, including any legal entity you may represent or act on behalf of.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: API Documentation only for evaluating a potential collaboration
    text: except to evaluate and analyse the API Documentation for the purpose of entering into discussions with us in respect of a potential commercial collaboration and agreement between us (Purpose)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By clicking 'Accept Terms and Create Account', you agree to be legally bound by the terms of this NDA.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eagle Eye
provenance_date: '2026-11-09'
provider_name: Eagle Eye
provider_slug: eagle-eye
slug: eagle-eye-eligibility
source_date: '2026-11-09'
source_filename: eagle-eye-eligibility.yml
source_heading: Eligibility
source_page: https://eagleeye.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eagle Eye\naid: eagle-eye\nurl: https://eagleeye.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You/your refers to you, the individual accessing the API Documentation, including any legal entity you may\n    represent or act on behalf of.\nrestricted_uses:\n- summary: API Documentation only for evaluating a potential collaboration\n  text: except to evaluate and analyse the API Documentation for the purpose of entering into discussions with us\n    in respect of a potential commercial collaboration and agreement\
  \ between us (Purpose)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By clicking 'Accept Terms and Create Account', you agree to be legally bound by the terms of this NDA.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eagle-eye/eligibility/eagle-eye-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Eagle Eye's own page on 2026-11-09.
synthetic: false
tags:
- Loyalty
- Personalization
- Promotions
- Retail
- Artificial Intelligence
- Omnichannel
- Gift Cards
---

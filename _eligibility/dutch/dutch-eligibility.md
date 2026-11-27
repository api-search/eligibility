---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Dutch
provenance_date: '2026-11-09'
provider_name: Dutch
provider_slug: dutch
slug: dutch-eligibility
source_date: '2026-11-09'
source_filename: dutch-eligibility.yml
source_heading: Eligibility
source_page: https://www.dutch.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dutch\naid: dutch\nurl: https://www.dutch.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority\
  \ in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/dutch/eligibility/dutch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dutch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Veterinary
- Pets
- Consumer
- Direct to Consumer
- Prescriptions
---

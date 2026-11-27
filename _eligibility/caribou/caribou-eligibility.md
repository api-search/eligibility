---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you represent that you are a United States resident, located in the United States, and at least the age of majority in your state of residence
  entity_types:
  - text: you represent that you are a United States resident, located in the United States, and at least the age of majority in your state of residence
    type: individual
  minimum_age:
    text: at least the age of majority in your state of residence
    value: age of majority
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Caribou does not guarantee that a lending partner will make you an offer to refinance your loan, or that a lending partner will approve your application to refinance
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Caribou
provenance_date: '2026-11-09'
provider_name: Caribou
provider_slug: caribou
slug: caribou-eligibility
source_date: '2026-11-09'
source_filename: caribou-eligibility.yml
source_heading: Eligibility
source_page: https://caribou.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caribou\naid: caribou\nurl: https://caribou.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you represent that you are a United States resident, located in the United States, and at least the age\n    of majority in your state of residence\nentity_types:\n- type: individual\n  text: you represent that you are a United States resident, located in the United States, and at least the age\n    of majority in your state of residence\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Caribou does not guarantee\
  \ that a lending partner will make you an offer to refinance your loan, or that\n    a lending partner will approve your application to refinance\nminimum_age:\n  value: age of majority\n  text: at least the age of majority in your state of residence\n"
source_yaml_url: https://artifacts.apis.io/caribou/eligibility/caribou-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Caribou's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Auto-Refinance
- Lending
- Consumer Finance
- Auto Loans
- Personal Finance
---

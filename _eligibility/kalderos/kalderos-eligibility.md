---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are of legal age and are otherwise capable of forming a legally binding contract
    type: individual
  - text: If you are registering an account or using the Services on behalf of an individual or entity other than yourself, you represent that you are authorized by such individual or entity to accept this Agreement on such individual’s or entity’s behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No violation of law or third-party rights
    text: the Materials and your use of the Service shall not violate any applicable law or regulation or cause injury to any person
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
name: Kalderos
provenance_date: '2026-11-09'
provider_name: Kalderos
provider_slug: kalderos
slug: kalderos-eligibility
source_date: '2026-11-09'
source_filename: kalderos-eligibility.yml
source_heading: Eligibility
source_page: https://www.kalderos.com/company/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kalderos\naid: kalderos\nurl: https://www.kalderos.com/company/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are of legal age and are otherwise capable of forming a legally binding contract\n- type: business\n  text: If you are registering an account or using the Services on behalf of an individual or entity other than\n    yourself, you represent that you are authorized by such individual or entity to accept this Agreement on such\n    individual’s or entity’s behalf.\nrestricted_uses:\n- summary: No violation\
  \ of law or third-party rights\n  text: the Materials and your use of the Service shall not violate any applicable law or regulation or cause injury\n    to any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kalderos/eligibility/kalderos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kalderos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- 340B
- Drug Discounts
- Rebate Management
- Compliance
- Life Sciences
- Pharmaceuticals
- Medicaid
- Health Tech
---

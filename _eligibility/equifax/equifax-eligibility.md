---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - CU
    - SY
    - SD
    - IQ
    - LB
    served: []
    text: comprehensive economic sanctions under the EAR, OFAC, or Israeli regulations, which currently include Iran, North Korea, Cuba, Syria and Sudan, as well as Iraq and Lebanon
  entity_types:
  - text: You represent that you are 18 years of age or over, have the authority and capacity to accept these Terms
    type: individual
  - text: If you open a Equifax account on behalf of a company, organization, or other entity, then (i) “you” includes you and that entity
    type: business
  minimum_age:
    text: You represent that you are 18 years of age or over
    value: '18'
  restricted_uses:
  - summary: FCRA-covered purposes
    text: you shall not design an application that allows or facilitates the use of the Data in any manner related to credit granting, credit monitoring, account review, insurance underwriting, employment, background screening or any other purpose covered by the Fair Credit Reporting Act
  - summary: Sanctioned persons
    text: any and all API usage by any person or entity that is subject to U.S. or international sanctions regardless of location is prohibited
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Prior to formal approval of your request to create an Equifax Developer Portal account, you will have to verify your contact information via email.
excluded_countries:
- IR
- KP
- CU
- SY
- SD
- IQ
- LB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Equifax
provenance_date: '2026-11-09'
provider_name: Equifax
provider_slug: equifax
slug: equifax-eligibility
source_date: '2026-11-09'
source_filename: equifax-eligibility.yml
source_heading: Eligibility
source_page: https://developer.equifax.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Equifax\naid: equifax\nurl: https://developer.equifax.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - CU\n  - SY\n  - SD\n  - IQ\n  - LB\n  text: comprehensive economic sanctions under the EAR, OFAC, or Israeli regulations, which currently include Iran,\n    North Korea, Cuba, Syria and Sudan, as well as Iraq and Lebanon\nentity_types:\n- type: individual\n  text: You represent that you are 18 years of age or over, have the authority and capacity to accept these Terms\n- type: business\n  text: If you open a Equifax account on behalf of a company, organization,\
  \ or other entity, then (i) “you” includes\n    you and that entity\nrestricted_uses:\n- summary: FCRA-covered purposes\n  text: you shall not design an application that allows or facilitates the use of the Data in any manner related\n    to credit granting, credit monitoring, account review, insurance underwriting, employment, background screening\n    or any other purpose covered by the Fair Credit Reporting Act\n- summary: Sanctioned persons\n  text: any and all API usage by any person or entity that is subject to U.S. or international sanctions regardless\n    of location is prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Prior to formal approval of your request to create an Equifax Developer Portal account, you will have to\n    verify your contact information via email.\nminimum_age:\n  value: '18'\n  text: You represent that you are 18 years of age or over\n"
source_yaml_url: https://artifacts.apis.io/equifax/eligibility/equifax-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Equifax's own page on 2026-11-09.
synthetic: false
tags:
- Credit
- Credit History
- Credit Reporting
- Identity
- Fraud Prevention
- Fortune 1000
---

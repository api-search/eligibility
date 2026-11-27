---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Included Health makes no representation that all products, services and/or material described on the Sites, or the Services available through the Sites, are appropriate or available for use in locations outside the United States or all states and territories within the United States.
  minimum_age:
    text: Included Health’s Sites are not intended for children under the age of 13.
    value: '13'
  restricted_uses:
  - summary: No use of EMO in legal disputes
    text: an EMO will not be used in any legal dispute including but not limited to litigation, arbitration, claim for disability benefits, claim for worker’s compensation and/or malpractice claims without the prior written consent of the Company.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sites require users to create unique identifiers (such as a username and password) in order to log into many areas of the Sites. We utilize these unique identifiers to verify the user’s identity and eligibility
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Doctor on Demand
provenance_date: '2026-11-09'
provider_name: Doctor on Demand
provider_slug: doctor-on-demand
slug: doctor-on-demand-eligibility
source_date: '2026-11-09'
source_filename: doctor-on-demand-eligibility.yml
source_heading: Eligibility
source_page: https://includedhealth.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doctor on Demand\naid: doctor-on-demand\nurl: https://includedhealth.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Included Health makes no representation that all products, services and/or material described on the Sites,\n    or the Services available through the Sites, are appropriate or available for use in locations outside the United\n    States or all states and territories within the United States.\nentity_types: []\nrestricted_uses:\n- summary: No use of EMO in legal disputes\n  text: an EMO will not be used in any legal dispute including but not limited\
  \ to litigation, arbitration, claim\n    for disability benefits, claim for worker’s compensation and/or malpractice claims without the prior written\n    consent of the Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sites require users to create unique identifiers (such as a username and password) in order to log into\n    many areas of the Sites. We utilize these unique identifiers to verify the user’s identity and eligibility\nminimum_age:\n  value: '13'\n  text: Included Health’s Sites are not intended for children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/doctor-on-demand/eligibility/doctor-on-demand-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Doctor on Demand's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telehealth
- Healthcare
- Digital Health
- Mental Health
- Virtual Care
---

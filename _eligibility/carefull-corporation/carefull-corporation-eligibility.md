---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users of the Service include Service Beneficiaries, Trusted Contacts, and Advisors.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Trusted Contact access limited to receiving the Service
    text: you agree to access and use the intended Service Beneficiary’s Account Data solely for the purpose of receiving the Service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree to provide documentation to prove your relationship to the Service Beneficiary if requested by Carefull.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carefull
provenance_date: '2026-11-09'
provider_name: Carefull
provider_slug: carefull-corporation
slug: carefull-corporation-eligibility
source_date: '2026-11-09'
source_filename: carefull-corporation-eligibility.yml
source_heading: Eligibility
source_page: https://getcarefull.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carefull\naid: carefull-corporation\nurl: https://getcarefull.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users of the Service include Service Beneficiaries, Trusted Contacts, and Advisors.\nrestricted_uses:\n- summary: Trusted Contact access limited to receiving the Service\n  text: you agree to access and use the intended Service Beneficiary’s Account Data solely for the purpose of receiving\n    the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree to\
  \ provide documentation to prove your relationship to the Service Beneficiary if requested by\n    Carefull.\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/carefull-corporation/eligibility/carefull-corporation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Carefull's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Safety
- Fraud Prevention
- Identity Theft Protection
- Elder Care
- Financial Caregiving
- AccountMonitoring
- Consumer Finance
---

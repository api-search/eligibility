---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least eighteen (18) years of age and legally competent to enter into binding contracts
    type: individual
  minimum_age:
    text: You are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful, abusive or discriminatory use
    text: access or use the Platform or Services for unlawful, unethical, abusive, or exploitative purposes, including profiling, discrimination, harassment, or targeting individuals based on protected characteristics
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
name: Bureau
provenance_date: '2026-11-09'
provider_name: Bureau
provider_slug: bureau
slug: bureau-eligibility
source_date: '2026-11-09'
source_filename: bureau-eligibility.yml
source_heading: Eligibility
source_page: https://bureau.id/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bureau\naid: bureau\nurl: https://bureau.id/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least eighteen (18) years of age and legally competent to enter into binding contracts\nrestricted_uses:\n- summary: Unlawful, abusive or discriminatory use\n  text: access or use the Platform or Services for unlawful, unethical, abusive, or exploitative purposes, including\n    profiling, discrimination, harassment, or targeting individuals based on protected characteristics\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/bureau/eligibility/bureau-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bureau's own page on 2026-11-09.
synthetic: false
tags:
- Fraud Prevention
- Identity Verification
- KYC
- AML
- Fintech
---

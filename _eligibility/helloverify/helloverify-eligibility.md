---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted content of user comments
    text: Be or contain libelous or otherwise unlawful, abusive, or obscene material or constitute the misappropriation of the trade secrets of any third party
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
name: HelloVerify
provenance_date: '2026-11-09'
provider_name: HelloVerify
provider_slug: helloverify
slug: helloverify-eligibility
source_date: '2026-11-09'
source_filename: helloverify-eligibility.yml
source_heading: Eligibility
source_page: https://www.helloverify.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HelloVerify\naid: helloverify\nurl: https://www.helloverify.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted content of user comments\n  text: Be or contain libelous or otherwise unlawful, abusive, or obscene material or constitute the misappropriation\n    of the trade secrets of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/helloverify/eligibility/helloverify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from HelloVerify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Background Verification
- Employee Screening
- Identity Verification
- KYC
- Primary Source Verification
- Compliance
- Human Resources
---

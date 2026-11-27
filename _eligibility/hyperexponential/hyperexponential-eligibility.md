---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use our website for your own personal and business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our website
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use our website in any way that is unlawful, illegal, fraudulent or harmful, or in connection with any unlawful, illegal, fraudulent or harmful purpose or activity
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
name: hyperexponential
provenance_date: '2026-11-09'
provider_name: hyperexponential
provider_slug: hyperexponential
slug: hyperexponential-eligibility
source_date: '2026-11-09'
source_filename: hyperexponential-eligibility.yml
source_heading: Eligibility
source_page: https://www.hyperexponential.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hyperexponential\naid: hyperexponential\nurl: https://www.hyperexponential.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may only use our website for your own personal and business purposes\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use our website in any way that is unlawful, illegal, fraudulent or harmful, or in connection with any unlawful,\n    illegal, fraudulent or harmful purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use our website\n"
source_yaml_url: https://artifacts.apis.io/hyperexponential/eligibility/hyperexponential-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from hyperexponential's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Underwriting
- Pricing
- Property and Casualty
- Actuarial
- Software-as-a-Service
---

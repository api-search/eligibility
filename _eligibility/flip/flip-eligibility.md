---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: send money abroad from Indonesia with better rates via Flip Globe
  entity_types:
  - text: Sign up and verify your account with your national ID
    type: individual
  - text: to small business owners looking to trim operational costs
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Sign up and verify your account with your national ID
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flip
provenance_date: '2026-11-09'
provider_name: Flip
provider_slug: flip
slug: flip-eligibility
source_date: '2026-11-09'
source_filename: flip-eligibility.yml
source_heading: Eligibility
source_page: https://flip.id/syarat-ketentuan
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flip\naid: flip\nurl: https://flip.id/syarat-ketentuan\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: send money abroad from Indonesia with better rates via Flip Globe\nentity_types:\n- type: individual\n  text: Sign up and verify your account with your national ID\n- type: business\n  text: to small business owners looking to trim operational costs\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Sign up and verify your account with your national ID\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flip/eligibility/flip-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 4 quoted statements, read from Flip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Payment Gateway
- Money Transfer
- Disbursements
- Remittances
- Fintech
- Indonesia
- International Transfer
- Banking
---

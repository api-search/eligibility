---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be 1) a legal resident of the United States
  entity_types:
  - text: You must be at least 18 years old or the age of majority in your state of residence.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your state of residence.
    value: '18'
  restricted_uses:
  - summary: Transacting only with known people
    text: BEEM SHOULD ONLY BE USED TO TRANSACT WITH PEOPLE YOU KNOW AND TRUST.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to use certain Services, Beem may be required to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beem
provenance_date: '2026-11-09'
provider_name: Beem
provider_slug: beem
slug: beem-eligibility
source_date: '2026-11-09'
source_filename: beem-eligibility.yml
source_heading: Eligibility
source_page: https://trybeem.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beem\naid: beem\nurl: https://trybeem.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be 1) a legal resident of the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in your state of residence.\nrestricted_uses:\n- summary: Transacting only with known people\n  text: BEEM SHOULD ONLY BE USED TO TRANSACT WITH PEOPLE YOU KNOW AND TRUST.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to use certain Services, Beem may be required to verify\
  \ your identity.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your state of residence.\n"
source_yaml_url: https://artifacts.apis.io/beem/eligibility/beem-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Beem's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Consumer Finance
- Cash Advance
- Personal Loans
- Banking
- Payments
- Mobile App
---

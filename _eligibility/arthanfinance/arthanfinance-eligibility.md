---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unsecured Business Loans are designed to meet the ever-growing aspirations of business owners
    type: business
  minimum_age:
    text: most of our best match happens when you age is between 25 years and 65 years.
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: KYC documents of the applicant (PAN card and address proof)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arthanfinance
provenance_date: '2026-11-09'
provider_name: Arthanfinance
provider_slug: arthanfinance
slug: arthanfinance-eligibility
source_date: '2026-11-09'
source_filename: arthanfinance-eligibility.yml
source_heading: Eligibility
source_page: https://arthan.finance/Termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arthanfinance\naid: arthanfinance\nurl: https://arthan.finance/Termsandconditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Unsecured Business Loans are designed to meet the ever-growing aspirations of business owners\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: KYC documents of the applicant (PAN card and address proof)\nminimum_age:\n  value: null\n  text: most of our best match happens when you age is between 25 years and 65 years.\n"
source_yaml_url: https://artifacts.apis.io/arthanfinance/eligibility/arthanfinance-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Arthanfinance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Loans
- Small Business
- India
---

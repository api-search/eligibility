---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not a 'Politically Exposed Person' resident outside India in terms of the KYC Framework.
  entity_types:
  - text: '"Applicant" refers to an individual who submits a formal request to the Bank for the opening any account or availing any Services'
    type: individual
  minimum_age:
    text: You confirm that you are at least 18 years of age to avail the Services. However, if you are less than 18 years but more than 10 years of age, you can avail specific Services of the Bank only with the consent and approval of a lawful guardian.
    value: '18'
  restricted_uses:
  - summary: No use for unlawful purposes
    text: You agree to use the Services only for purposes that are permitted by these Terms and in accordance with applicable laws.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: the availing of Services is subject to verification, and the Bank reserves the right to reject the request of the Applicant to open an account or avail any Services without providing any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Slice
provenance_date: '2026-11-10'
provider_name: Slice
provider_slug: slice-cards
slug: slice-cards-eligibility
source_date: '2026-11-10'
source_filename: slice-cards-eligibility.yml
source_heading: Eligibility
source_page: https://slice.bank.in/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Slice\naid: slice-cards\nurl: https://slice.bank.in/terms-of-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You are not a 'Politically Exposed Person' resident outside India in terms of the KYC Framework.\nentity_types:\n- type: individual\n  text: '\"Applicant\" refers to an individual who submits a formal request to the Bank for the opening any account\n    or availing any Services'\nrestricted_uses:\n- summary: No use for unlawful purposes\n  text: You agree to use the Services only for purposes that are permitted by these Terms and in accordance with\n\
  \    applicable laws.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: the availing of Services is subject to verification, and the Bank reserves the right to reject the request\n    of the Applicant to open an account or avail any Services without providing any reason.\nminimum_age:\n  value: '18'\n  text: You confirm that you are at least 18 years of age to avail the Services. However, if you are less than 18\n    years but more than 10 years of age, you can avail specific Services of the Bank only with the consent and approval\n    of a lawful guardian.\n"
source_yaml_url: https://artifacts.apis.io/slice-cards/eligibility/slice-cards-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Slice's own page on 2026-11-10.
synthetic: false
tags:
- Banking
- Neobank
- Small Finance Bank
- Consumer Finance
- Credit Cards
- Prepaid Cards
- Buy Now Pay Later
- UPI
- Payments
- Payouts
- Merchant API
- Savings Accounts
- Fixed Deposits
- Fintech
- India
- Gen Z
---

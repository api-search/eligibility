---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: 'To be eligible as a borrower you must: be an individual residing in the UK'
  entity_types:
  - text: 'To be eligible as a borrower you must: be an individual residing in the UK; be at least 18 years old'
    type: individual
  - text: You represent a company, partnership, or trust
    type: business
  minimum_age:
    text: You confirm that you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: use of our Website is permitted is solely for your personal use
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 'As part of our loan approval process we may: make identity, fraud, income and credit checks; obtain a credit rating for you from the credit reference agency we use; and carry out anti-money laundering checks on you. All loan applications are subject to our approval'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lendable
provenance_date: '2026-11-09'
provider_name: Lendable
provider_slug: lendable
slug: lendable-eligibility
source_date: '2026-11-09'
source_filename: lendable-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendable.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendable\naid: lendable\nurl: https://www.lendable.co.uk/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: 'To be eligible as a borrower you must: be an individual residing in the UK'\nentity_types:\n- type: individual\n  text: 'To be eligible as a borrower you must: be an individual residing in the UK; be at least 18 years old'\n- type: business\n  text: You represent a company, partnership, or trust\nrestricted_uses:\n- summary: Personal use only\n  text: use of our Website is permitted is solely for your personal use\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ true\n  text: 'As part of our loan approval process we may: make identity, fraud, income and credit checks; obtain a credit\n    rating for you from the credit reference agency we use; and carry out anti-money laundering checks on you. All\n    loan applications are subject to our approval'\nminimum_age:\n  value: '18'\n  text: You confirm that you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/lendable/eligibility/lendable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Lendable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Personal Loans
- Consumer Credit
- Fintech
- United Kingdom
---

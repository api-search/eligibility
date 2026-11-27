---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (b) all Users and Your Organization or Individual, as appropriate, reside in the United States
  entity_types:
  - text: If You use the Service on behalf of another, whether a natural person (an “Individual”) or legal non-natural person or entity (an “Organization”)
    type: individual
  - text: if You are a corporation, partnership, or other Organization, then Your User(s) may access Your Docyt account from outside of the country where You hold Your Docyt account.
    type: business
  minimum_age:
    text: (a) all Users are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Evaluation licenses restricted to internal or pre-release use
    text: Evaluation Use Licenses for trials are restricted to use for internal evaluation.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We, and banks that offer services through Docyt, will ask You for Your name, address, date of birth, and if You are located within the United States, Your social security number (SSN) and/or Employer Identification Number (EIN)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docyt
provenance_date: '2026-11-09'
provider_name: Docyt
provider_slug: docyt
slug: docyt-eligibility
source_date: '2026-11-09'
source_filename: docyt-eligibility.yml
source_heading: Eligibility
source_page: https://www.docyt.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docyt\naid: docyt\nurl: https://www.docyt.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (b) all Users and Your Organization or Individual, as appropriate, reside in the United States\nentity_types:\n- type: individual\n  text: If You use the Service on behalf of another, whether a natural person (an “Individual”) or legal non-natural\n    person or entity (an “Organization”)\n- type: business\n  text: if You are a corporation, partnership, or other Organization, then Your User(s) may access Your Docyt account\n    from outside of the country where\
  \ You hold Your Docyt account.\nrestricted_uses:\n- summary: Evaluation licenses restricted to internal or pre-release use\n  text: Evaluation Use Licenses for trials are restricted to use for internal evaluation.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We, and banks that offer services through Docyt, will ask You for Your name, address, date of birth, and\n    if You are located within the United States, Your social security number (SSN) and/or Employer Identification\n    Number (EIN)\nminimum_age:\n  value: '18'\n  text: (a) all Users are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/docyt/eligibility/docyt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Docyt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Bookkeeping
- Financial Operations
- Accounts Payable
- Expense Management
- Reconciliation
- Hospitality
- Artificial Intelligence
- Software-as-a-Service
---

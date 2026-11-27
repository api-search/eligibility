---
claim_count: 2
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
  - summary: Sanctioned jurisdictions
    text: (b) provided to or used for any transaction involving an individual, organization, country, or jurisdiction that is blocked or sanctioned by the United States
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: We will conduct due diligence on you for know-your-customer purposes before approving your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aspire
provenance_date: '2026-11-09'
provider_name: Aspire
provider_slug: aspire
slug: aspire-eligibility
source_date: '2026-11-09'
source_filename: aspire-eligibility.yml
source_heading: Eligibility
source_page: https://aspireapp.com/en-sg/tnc/master-service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aspire\naid: aspire\nurl: https://aspireapp.com/en-sg/tnc/master-service-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: (b) provided to or used for any transaction involving an individual, organization, country, or jurisdiction\n    that is blocked or sanctioned by the United States\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: We will conduct due diligence on you for know-your-customer purposes before approving your account.\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/aspire/eligibility/aspire-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Aspire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Business Banking
- Payments
- Payouts
- Card Issuance
- Foreign Exchange
- Expense Management
- Financial Services
- Singapore
---

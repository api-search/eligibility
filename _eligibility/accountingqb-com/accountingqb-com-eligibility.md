---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and capable of forming a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age and capable of forming a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: No professional advice reliance
    text: no output of the Service constitutes tax, legal, accounting, or financial advice.
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
name: AccountingQB
provenance_date: '2026-11-09'
provider_name: AccountingQB
provider_slug: accountingqb-com
slug: accountingqb-com-eligibility
source_date: '2026-11-09'
source_filename: accountingqb-com-eligibility.yml
source_heading: Eligibility
source_page: https://accountingqb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccountingQB\naid: accountingqb-com\nurl: https://accountingqb.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and capable of forming a binding contract to use the Service.\nrestricted_uses:\n- summary: No professional advice reliance\n  text: no output of the Service constitutes tax, legal, accounting, or financial advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and capable\
  \ of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/accountingqb-com/eligibility/accountingqb-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AccountingQB's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Artificial Intelligence
- Bookkeeping
- Financial Analysis
- Invoice Reconciliation
- CPA Handoff
---

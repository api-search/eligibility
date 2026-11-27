---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Transfers must be from within Singapore, otherwise they would be rejected.
  entity_types:
  - text: You warrant that you are an individual acting solely on your own behalf and are acting for a purpose other than a trade, business or profession.
    type: individual
  minimum_age:
    text: you are either at least 18 years old or represent or warrant you have obtained parental consent for use of Get
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: use the Get Services for any illegal purposes, including, but not limited to fraud and money laundering
  - summary: Debt collection
    text: use the Get Services to engage in debt-collection activities
  - summary: Speculative FX
    text: use the Get Services to trade FX for speculative purposes or for FX arbitrage
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
name: Get
provenance_date: '2026-11-09'
provider_name: Get
provider_slug: get
slug: get-eligibility
source_date: '2026-11-09'
source_filename: get-eligibility.yml
source_heading: Eligibility
source_page: https://useget.com/personal/personal-legal/personal-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Get\naid: get\nurl: https://useget.com/personal/personal-legal/personal-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Transfers must be from within Singapore, otherwise they would be rejected.\nentity_types:\n- type: individual\n  text: You warrant that you are an individual acting solely on your own behalf and are acting for a purpose other\n    than a trade, business or profession.\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Get Services for any illegal purposes, including, but not limited to fraud and money laundering\n\
  - summary: Debt collection\n  text: use the Get Services to engage in debt-collection activities\n- summary: Speculative FX\n  text: use the Get Services to trade FX for speculative purposes or for FX arbitrage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are either at least 18 years old or represent or warrant you have obtained parental consent for use\n    of Get\n"
source_yaml_url: https://artifacts.apis.io/get/eligibility/get-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Get's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Financial Literacy
- Prepaid Cards
- Family
- Payments
- Singapore
---

---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Transactions may not be available in all locations and may be restricted or declined where required by applicable law.
  entity_types:
  - text: These Terms apply when you purchase products or services through a checkout experience powered by Outpost. Global – Consumer Purchases
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Outpost
provenance_date: '2026-11-10'
provider_name: Outpost
provider_slug: outpost
slug: outpost-eligibility
source_date: '2026-11-10'
source_filename: outpost-eligibility.yml
source_heading: Eligibility
source_page: https://outpost.ai/terms/merchant-of-record/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outpost\naid: outpost\nurl: https://outpost.ai/terms/merchant-of-record/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Transactions may not be available in all locations and may be restricted or declined where required by applicable\n    law.\nentity_types:\n- type: individual\n  text: These Terms apply when you purchase products or services through a checkout experience powered by Outpost.\n    Global – Consumer Purchases\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/outpost/eligibility/outpost-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Outpost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Merchant of Record
- Tax of Record
- Cross-Border Commerce
- Payments
- Tax Compliance
- E-Commerce
- VAT
- Fintech
- Invoicing
- Onboarding
---

---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Celtic Bank’s online services are not intended for children under 18
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you warrant to Celtic Bank that you will not use the Celtic Bank website or mobile app for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Celtic Bank
provenance_date: '2026-11-09'
provider_name: Celtic Bank
provider_slug: celtic-bank
slug: celtic-bank-eligibility
source_date: '2026-11-09'
source_filename: celtic-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.celticbank.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celtic Bank\naid: celtic-bank\nurl: https://www.celticbank.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you warrant to Celtic Bank that you will not use the Celtic Bank website or mobile app for any purpose that\n    is unlawful or prohibited by these terms, conditions, and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Celtic Bank’s online services are not intended for children under 18\n"
source_yaml_url: https://artifacts.apis.io/celtic-bank/eligibility/celtic-bank-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Celtic Bank's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- SBA Loans
- Commercial Lending
- Fintech
---

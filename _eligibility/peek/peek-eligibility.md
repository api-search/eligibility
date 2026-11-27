---
claim_count: 1
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
  - summary: No storing customer card data
    text: Merchant shall not store any Customer credit card information or other information prohibited by applicable law in or by use of the Peek Professional Software
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
name: Peek
provenance_date: '2026-11-10'
provider_name: Peek
provider_slug: peek
slug: peek-eligibility
source_date: '2026-11-10'
source_filename: peek-eligibility.yml
source_heading: Eligibility
source_page: https://www.peekpro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peek\naid: peek\nurl: https://www.peekpro.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No storing customer card data\n  text: Merchant shall not store any Customer credit card information or other information prohibited by applicable\n    law in or by use of the Peek Professional Software\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/peek/eligibility/peek-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Peek's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Tourism
- Booking
- Reservations
- Experience
- Tours and Activities
- Payments
- Marketplace
- MCP
- OCTO
- Software-as-a-Service
---

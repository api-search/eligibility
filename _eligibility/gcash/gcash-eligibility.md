---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The GCash Card is only available for Philippine-registered GCash users and is subject to the terms and conditions set by the card issuer.
  entity_types:
  - text: You must be at least eighteen (18) years old to register for a GCash account.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old to register for a GCash account.
    value: '18'
  restricted_uses:
  - summary: No commercial use without authorization
    text: You further agree not to use the GCash App and GCash Services for any commercial or business use, without prior written authorization from GCash.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may also verify your registration information through a third-party verification service provider, as we deem necessary.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GCash
provenance_date: '2026-11-09'
provider_name: GCash
provider_slug: gcash
slug: gcash-eligibility
source_date: '2026-11-09'
source_filename: gcash-eligibility.yml
source_heading: Eligibility
source_page: https://gcash.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GCash\naid: gcash\nurl: https://gcash.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The GCash Card is only available for Philippine-registered GCash users and is subject to the terms and conditions\n    set by the card issuer.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to register for a GCash account.\nrestricted_uses:\n- summary: No commercial use without authorization\n  text: You further agree not to use the GCash App and GCash Services for any commercial or business use, without\n    prior\
  \ written authorization from GCash.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may also verify your registration information through a third-party verification service provider, as\n    we deem necessary.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to register for a GCash account.\n"
source_yaml_url: https://artifacts.apis.io/gcash/eligibility/gcash-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from GCash's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Mobile Wallet
- E-Money
- Fintech
- Digital Payments
- Philippines
- QR Payments
---

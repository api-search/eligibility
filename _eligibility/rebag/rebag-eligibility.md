---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old and capable of forming a binding contract to create an account or transact with Rebag.
    type: individual
  - text: the term "you" or "your" means an individual or entity exercising rights under this Agreement
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Money laundering or unlawful use
    text: (vi) use the Rebag Services for money laundering, structuring, or any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Rebag may verify your identity, billing address and payment method before accepting or fulfilling an order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rebag
provenance_date: '2026-11-10'
provider_name: Rebag
provider_slug: rebag
slug: rebag-eligibility
source_date: '2026-11-10'
source_filename: rebag-eligibility.yml
source_heading: Eligibility
source_page: https://www.rebag.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rebag\naid: rebag\nurl: https://www.rebag.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old and capable of forming a binding contract to create an account\n    or transact with Rebag.\n- type: business\n  text: the term \"you\" or \"your\" means an individual or entity exercising rights under this Agreement\nrestricted_uses:\n- summary: Money laundering or unlawful use\n  text: (vi) use the Rebag Services for money laundering, structuring, or any unlawful purpose\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Rebag may verify your identity, billing address and payment method before accepting or fulfilling an order\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/rebag/eligibility/rebag-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rebag's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Luxury
- Resale
- E-Commerce
- Marketplace
- Fashion
- Handbags
- Secondhand
- Retail
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Buyer Protection applies to natural persons ... who are resident in United Kingdom and have an active PriceRunner member account
  entity_types:
  - text: The Buyer Protection applies to natural persons (“the Buyer”), who are resident in United Kingdom and have an active PriceRunner member account
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You may download, display and print one copy of the material presented on this site for your personal, non-commercial use only.
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
name: Pricerunner
provenance_date: '2026-11-10'
provider_name: Pricerunner
provider_slug: pricerunner
slug: pricerunner-eligibility
source_date: '2026-11-10'
source_filename: pricerunner-eligibility.yml
source_heading: Eligibility
source_page: https://www.pricerunner.com/info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pricerunner\naid: pricerunner\nurl: https://www.pricerunner.com/info/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Buyer Protection applies to natural persons ... who are resident in United Kingdom and have an active\n    PriceRunner member account\nentity_types:\n- type: individual\n  text: The Buyer Protection applies to natural persons (“the Buyer”), who are resident in United Kingdom and have\n    an active PriceRunner member account\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You may download, display and print one copy of the material\
  \ presented on this site for your personal, non-commercial\n    use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pricerunner/eligibility/pricerunner-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pricerunner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Price Comparison
- E-Commerce
- Shopping
- Product Data
- Retail
- Klarna
---

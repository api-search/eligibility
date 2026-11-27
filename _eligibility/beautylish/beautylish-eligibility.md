---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you must be 16 years or older and have the requisite power and authority to enter into these Terms of Service
    type: individual
  minimum_age:
    text: you must be 16 years or older
    value: '16'
  restricted_uses:
  - summary: Personal use only
    text: As a retailer, Beautylish sells merchandise for personal use only.
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
name: Beautylish
provenance_date: '2026-11-09'
provider_name: Beautylish
provider_slug: beautylish
slug: beautylish-eligibility
source_date: '2026-11-09'
source_filename: beautylish-eligibility.yml
source_heading: Eligibility
source_page: https://www.beautylish.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beautylish\naid: beautylish\nurl: https://www.beautylish.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you must be 16 years or older and have the requisite power and authority to enter into these Terms of Service\nrestricted_uses:\n- summary: Personal use only\n  text: As a retailer, Beautylish sells merchandise for personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you must be 16 years or older\n"
source_yaml_url: https://artifacts.apis.io/beautylish/eligibility/beautylish-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Beautylish's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Beauty
- Cosmetics
- Consumer
- Marketplace
- Direct to Consumer
---

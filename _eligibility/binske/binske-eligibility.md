---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: These Sites are offered and available only to users who are 21 years of age or older.
    value: '21'
  restricted_uses:
  - summary: Cannabis residency limit
    text: to the extent it pertains to cannabis, our products and Services are only available to residents of states and localities with laws authorizing and/or regulating the medical or recreational use of cannabis and only to the extent permitted by such laws.
  - summary: Hemp sales age limit
    text: THE SALE OF HEMP OR HEMP EXTRACT INTENDED FOR HUMAN CONSUMPTION TO PERSONS UNDER THE AGE OF 21 IS PROHIBITED.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: PROOF OF AGE IS REQUIRED FOR PURCHASE.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Binske
provenance_date: '2026-11-09'
provider_name: Binske
provider_slug: binske
slug: binske-eligibility
source_date: '2026-11-09'
source_filename: binske-eligibility.yml
source_heading: Eligibility
source_page: https://binske.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Binske\naid: binske\nurl: https://binske.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Cannabis residency limit\n  text: to the extent it pertains to cannabis, our products and Services are only available to residents of states\n    and localities with laws authorizing and/or regulating the medical or recreational use of cannabis and only\n    to the extent permitted by such laws.\n- summary: Hemp sales age limit\n  text: THE SALE OF HEMP OR HEMP EXTRACT INTENDED FOR HUMAN CONSUMPTION TO PERSONS UNDER THE\
  \ AGE OF 21 IS PROHIBITED.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: PROOF OF AGE IS REQUIRED FOR PURCHASE.\nminimum_age:\n  value: '21'\n  text: These Sites are offered and available only to users who are 21 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/binske/eligibility/binske-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Binske's own page on 2026-11-09.
synthetic: false
tags:
- Cannabis
- Consumer Packaged Goods
- Direct to Consumer
- E-Commerce
- Retail
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Storefront
---

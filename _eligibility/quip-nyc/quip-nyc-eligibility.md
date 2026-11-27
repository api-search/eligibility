---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Personal use only for products
    text: All orders of our products must be for personal use only.
  - summary: Services for user's own use only
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: Quip NYC
provenance_date: '2026-11-10'
provider_name: Quip NYC
provider_slug: quip-nyc
slug: quip-nyc-eligibility
source_date: '2026-11-10'
source_filename: quip-nyc-eligibility.yml
source_heading: Eligibility
source_page: https://www.getquip.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quip NYC\naid: quip-nyc\nurl: https://www.getquip.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal use only for products\n  text: All orders of our products must be for personal use only.\n- summary: Services for user's own use only\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are\
  \ at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/quip-nyc/eligibility/quip-nyc-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Quip NYC's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Oral Care
- Consumer Health
- Personal Care
- Retail
- E-Commerce
- Direct to Consumer
- Subscription
- Agentic Commerce
- Shopify
---

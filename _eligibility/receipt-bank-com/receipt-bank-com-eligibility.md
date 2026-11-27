---
api_specs:
- filename: receipt-bank-com-openapi-generated.yml
  format: yaml
  label: Dext API
  slug: receipt-bank-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/receipt-bank-com/openapi/_ae-authored/receipt-bank-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '“Partner”: means You and Your Authorised Users, where You are an accountancy or bookkeeping firm'
    type: business
  - text: '“Client”: means You and Your Authorised Users as users of the Dext Products, if You are a business owner who is not a Partner'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'You shall not: access, store, distribute or transmit any worms, trojan horses, viruses and other similar things or devices, or any material during the course of Your use of the Dext Products that: is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing'
  - summary: Fair use policy compliance
    text: You shall comply with Our Fair Use Policy by, for example, only using the Dext Products to request a reasonable volume of pages for extraction.
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
name: Dext
provenance_date: '2026-11-10'
provider_name: Dext
provider_slug: receipt-bank-com
slug: receipt-bank-com-eligibility
source_date: '2026-11-10'
source_filename: receipt-bank-com-eligibility.yml
source_heading: Eligibility
source_page: https://dext.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dext\naid: receipt-bank-com\nurl: https://dext.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '“Partner”: means You and Your Authorised Users, where You are an accountancy or bookkeeping firm'\n- type: individual\n  text: '“Client”: means You and Your Authorised Users as users of the Dext Products, if You are a business owner\n    who is not a Partner'\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'You shall not: access, store, distribute or transmit any worms, trojan\
  \ horses, viruses and other similar\n    things or devices, or any material during the course of Your use of the Dext Products that: is unlawful, harmful,\n    threatening, defamatory, obscene, infringing, harassing'\n- summary: Fair use policy compliance\n  text: You shall comply with Our Fair Use Policy by, for example, only using the Dext Products to request a reasonable\n    volume of pages for extraction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/receipt-bank-com/eligibility/receipt-bank-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Dext's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bookkeeping
- Automation
- Accounting
- Artificial Intelligence
---

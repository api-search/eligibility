---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Enhanced SMS is currently available only to businesses based in the United States and Canada .
  entity_types:
  - text: Each YouCanBook.Me subscription may be used to process bookings for just one organisation or trading entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cryptocurrency products
    text: Involves the marketing, promotion or operation of any cryptocurrency product or service
  - summary: Investment or financial products with risk of loss
    text: Involves the marketing, promotion or operation of any investment or financial products or service
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
name: YouCanBook.me
provenance_date: '2026-11-10'
provider_name: YouCanBook.me
provider_slug: youcanbook-me
slug: youcanbook-me-eligibility
source_date: '2026-11-10'
source_filename: youcanbook-me-eligibility.yml
source_heading: Eligibility
source_page: https://youcanbook.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YouCanBook.me\naid: youcanbook-me\nurl: https://youcanbook.me/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Enhanced SMS is currently available only to businesses based in the United States and Canada .\nentity_types:\n- type: business\n  text: Each YouCanBook.Me subscription may be used to process bookings for just one organisation or trading entity.\nrestricted_uses:\n- summary: Cryptocurrency products\n  text: Involves the marketing, promotion or operation of any cryptocurrency product or service\n- summary: Investment or financial products with risk of loss\n\
  \  text: Involves the marketing, promotion or operation of any investment or financial products or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/youcanbook-me/eligibility/youcanbook-me-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from YouCanBook.me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Software-as-a-Service
- Automation
- Integration
---

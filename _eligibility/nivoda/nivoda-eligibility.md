---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Website offers a powerful marketplace for businesses to buy and sell diamonds.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of content
    text: You must not use any part of the content on our Website for commercial purposes without obtaining a licence to do so from us or our licensors.
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: Compliance in full with our AML Policy and the KYC procedures set out therein must be completed before any supply or purchase can be processed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nivoda
provenance_date: '2026-11-10'
provider_name: Nivoda
provider_slug: nivoda
slug: nivoda-eligibility
source_date: '2026-11-10'
source_filename: nivoda-eligibility.yml
source_heading: Eligibility
source_page: https://nivoda.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nivoda\naid: nivoda\nurl: https://nivoda.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Website offers a powerful marketplace for businesses to buy and sell diamonds.\nrestricted_uses:\n- summary: Commercial use of content\n  text: You must not use any part of the content on our Website for commercial purposes without obtaining a licence\n    to do so from us or our licensors.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: Compliance in full with our AML Policy and the KYC procedures\
  \ set out therein must be completed before any\n    supply or purchase can be processed.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nivoda/eligibility/nivoda-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Nivoda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Diamonds
- Gemstones
- Jewelry
- Marketplace
- B2B
- GraphQL
- Inventory
- E-Commerce
---

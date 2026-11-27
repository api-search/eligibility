---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, the Site is solely for use within the United States.
  entity_types:
  - text: You agree that by using this Site and registering for membership, you are at least 18 years of age if you are a resident of the United States or otherwise the age of majority in your jurisdiction of residence, or at least 13 years of age, visiting under the supervision and consent of a parent or guardian
    type: individual
  minimum_age:
    text: at least 13 years of age, visiting under the supervision and consent of a parent or guardian
    value: '13'
  restricted_uses:
  - summary: No use for illegal purposes
    text: Use of the Site for any illegal or unauthorized purpose is strictly prohibited.
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
name: Artofsport
provenance_date: '2026-11-09'
provider_name: Artofsport
provider_slug: artofsport
slug: artofsport-eligibility
source_date: '2026-11-09'
source_filename: artofsport-eligibility.yml
source_heading: Eligibility
source_page: https://artofsport.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artofsport\naid: artofsport\nurl: https://artofsport.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, the Site is solely for use within the United States.\nentity_types:\n- type: individual\n  text: You agree that by using this Site and registering for membership, you are at least 18 years of age if you\n    are a resident of the United States or otherwise the age of majority in your jurisdiction of residence, or at\n    least 13 years of age, visiting under the supervision and consent of a parent or guardian\nrestricted_uses:\n\
  - summary: No use for illegal purposes\n  text: Use of the Site for any illegal or unauthorized purpose is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: at least 13 years of age, visiting under the supervision and consent of a parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/artofsport/eligibility/artofsport-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Artofsport's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Personal Care
- Skincare
- Body Care
- Athletics
- Direct to Consumer
- E-Commerce
- Shopify
---

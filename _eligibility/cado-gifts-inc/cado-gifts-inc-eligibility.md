---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform does not deal with any individual, user or entity that has international sanctions; the page refers to OFAC sanctioned countries without naming them.
  entity_types:
  - text: You are an individual of 18 years and older, are legally allowed to view and transact on the Platform (if and as required)
    type: individual
  - text: or are a properly and validly licensed entity in accordance with applicable laws
    type: business
  minimum_age:
    text: You are an individual of 18 years and older
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: If you are one of such sanctioned individuals or entities, belong to a sanctioned country or entity or region, or regularly deal with sanctioned individuals or entities, please DO NOT use the Platform.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We retain complete rights at any time and without reason, advance notice, limitation or liability, to terminate or restrict your access to the Platform or not accept or decline Registration of a user account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cado Gifts
provenance_date: '2026-11-09'
provider_name: Cado Gifts
provider_slug: cado-gifts-inc
slug: cado-gifts-inc-eligibility
source_date: '2026-11-09'
source_filename: cado-gifts-inc-eligibility.yml
source_heading: Eligibility
source_page: https://cadogifting.com/en-ae/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cado Gifts\naid: cado-gifts-inc\nurl: https://cadogifting.com/en-ae/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Platform does not deal with any individual, user or entity that has international sanctions; the page\n    refers to OFAC sanctioned countries without naming them.\nentity_types:\n- type: individual\n  text: You are an individual of 18 years and older, are legally allowed to view and transact on the Platform (if\n    and as required)\n- type: business\n  text: or are a properly and validly licensed entity in accordance with applicable laws\n\
  restricted_uses:\n- summary: Sanctioned persons\n  text: If you are one of such sanctioned individuals or entities, belong to a sanctioned country or entity or region,\n    or regularly deal with sanctioned individuals or entities, please DO NOT use the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We retain complete rights at any time and without reason, advance notice, limitation or liability, to terminate\n    or restrict your access to the Platform or not accept or decline Registration of a user account\nminimum_age:\n  value: '18'\n  text: You are an individual of 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/cado-gifts-inc/eligibility/cado-gifts-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cado Gifts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gifts
- Corporate Gifting
- Luxury Goods
- E-Commerce
- Retail
- Shopify
- United Arab Emirates
---

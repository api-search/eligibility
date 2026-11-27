---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform is controlled and operated from the United States. Users who access the Platform from outside the United States are solely responsible for compliance with all applicable local laws.
  entity_types:
  - text: Be at least 18 years of age, or the age of legal majority in your jurisdiction if higher;
    type: individual
  minimum_age:
    text: Be at least 18 years of age, or the age of legal majority in your jurisdiction if higher;
    value: '18'
  restricted_uses:
  - summary: Illegal financial activity
    text: Using the Platform for money laundering, terrorist financing, or any illegal financial activity;
  - summary: Circumventing geographic restrictions
    text: Using VPNs, proxies, or other tools to circumvent geographic access restrictions.
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
name: Dripshop
provenance_date: '2026-11-09'
provider_name: Dripshop
provider_slug: dripshop
slug: dripshop-eligibility
source_date: '2026-11-09'
source_filename: dripshop-eligibility.yml
source_heading: Eligibility
source_page: https://www.dripshop.live/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dripshop\naid: dripshop\nurl: https://www.dripshop.live/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Platform is controlled and operated from the United States. Users who access the Platform from outside\n    the United States are solely responsible for compliance with all applicable local laws.\nentity_types:\n- type: individual\n  text: Be at least 18 years of age, or the age of legal majority in your jurisdiction if higher;\nrestricted_uses:\n- summary: Illegal financial activity\n  text: Using the Platform for money laundering, terrorist financing,\
  \ or any illegal financial activity;\n- summary: Circumventing geographic restrictions\n  text: Using VPNs, proxies, or other tools to circumvent geographic access restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age, or the age of legal majority in your jurisdiction if higher;\n"
source_yaml_url: https://artifacts.apis.io/dripshop/eligibility/dripshop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dripshop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Live Shopping
- Collectibles
- Trading Cards
- Marketplace
- E-Commerce
- Auctions
- Live Streaming
- Payments
- GraphQL
---

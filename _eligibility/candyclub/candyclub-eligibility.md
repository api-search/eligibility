---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent that: (1) you are at least 18 years of age; (2) you are of legal age to form a binding contract'
    type: individual
  minimum_age:
    text: 'You represent that: (1) you are at least 18 years of age'
    value: '18'
  restricted_uses:
  - summary: Resale purchases
    text: The purchase of products for resale through Candy Club’s website is strictly prohibited.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right at any time after receipt of your order to accept or decline your order for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CandyClub
provenance_date: '2026-11-09'
provider_name: CandyClub
provider_slug: candyclub
slug: candyclub-eligibility
source_date: '2026-11-09'
source_filename: candyclub-eligibility.yml
source_heading: Eligibility
source_page: https://candyclub.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CandyClub\naid: candyclub\nurl: https://candyclub.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent that: (1) you are at least 18 years of age; (2) you are of legal age to form a binding contract'\nrestricted_uses:\n- summary: Resale purchases\n  text: The purchase of products for resale through Candy Club’s website is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We reserve the right at any time after receipt of your order to accept or\
  \ decline your order for any reason.\nminimum_age:\n  value: '18'\n  text: 'You represent that: (1) you are at least 18 years of age'\n"
source_yaml_url: https://artifacts.apis.io/candyclub/eligibility/candyclub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CandyClub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Candy
- Confectionery
- E-Commerce
- Subscription
- Retail
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
---

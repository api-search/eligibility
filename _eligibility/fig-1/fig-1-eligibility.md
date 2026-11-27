---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: a resident of the United States in order to make a purchase or use the Services on our Site. The Site and Services are not intended for use outside the United States.
  entity_types:
  - text: You must be the age of majority in your jurisdiction of residence
    type: individual
  minimum_age:
    text: You must be the age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Personal use only for product orders
    text: All orders of Products must be for your personal use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We also reserve the right, in our sole discretion, to take steps to verify your identity to process your order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fig 1
provenance_date: '2026-11-09'
provider_name: Fig 1
provider_slug: fig-1
slug: fig-1-eligibility
source_date: '2026-11-09'
source_filename: fig-1-eligibility.yml
source_heading: Eligibility
source_page: https://fig-1.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fig 1\naid: fig-1\nurl: https://fig-1.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: a resident of the United States in order to make a purchase or use the Services on our Site. The Site and\n    Services are not intended for use outside the United States.\nentity_types:\n- type: individual\n  text: You must be the age of majority in your jurisdiction of residence\nrestricted_uses:\n- summary: Personal use only for product orders\n  text: All orders of Products must be for your personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: We also reserve the right, in our sole discretion, to take steps to verify your identity to process your\n    order.\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/fig-1/eligibility/fig-1-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fig 1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Skincare
- Beauty
- E-Commerce
- Direct to Consumer
- Consumer
- Shopify
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: For orders placed on our gymshark.com website, we ship to the United States.
  entity_types:
  - text: To order our products, you must be at least 18 years old and be authorized to use the payment method which you use to pay for the products you order. If you are under 18, you may place an order only with involvement of a parent or guardian.
    type: individual
  minimum_age:
    text: To order our products, you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: We only supply the products for private use.
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
name: Gymshark
provenance_date: '2026-11-09'
provider_name: Gymshark
provider_slug: gymshark
slug: gymshark-eligibility
source_date: '2026-11-09'
source_filename: gymshark-eligibility.yml
source_heading: Eligibility
source_page: https://www.gymshark.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gymshark\naid: gymshark\nurl: https://www.gymshark.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: For orders placed on our gymshark.com website, we ship to the United States.\nentity_types:\n- type: individual\n  text: To order our products, you must be at least 18 years old and be authorized to use the payment method which\n    you use to pay for the products you order. If you are under 18, you may place an order only with involvement\n    of a parent or guardian.\nrestricted_uses:\n- summary: Personal use only\n  text: We only supply the products\
  \ for private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To order our products, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/gymshark/eligibility/gymshark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gymshark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Apparel
- Fitness
- Consumer
- Direct to Consumer
- Identity
---

---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Eligibility is limited to individuals in the US only. (Refer-a-Friend program). AG1 may reject orders where the stated delivery address is outside the United States.
  entity_types:
  - text: In order to use the Websites, you must be 18 years or older and have the power to enter into a binding contract with us
    type: individual
  - text: AG1 Refer-a-Friend Program cannot be used by businesses or corporations or for affiliate lead generation.
    type: business
  minimum_age:
    text: you must be 18 years or older
    value: '18'
  restricted_uses:
  - summary: Personal use only; no resale
    text: AG1 only accepts orders for personal use. You cannot resell items offered on the Websites.
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
name: AG1
provenance_date: '2026-11-09'
provider_name: AG1
provider_slug: athletic-greens
slug: athletic-greens-eligibility
source_date: '2026-11-09'
source_filename: athletic-greens-eligibility.yml
source_heading: Eligibility
source_page: https://drinkag1.com/about-us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AG1\naid: athletic-greens\nurl: https://drinkag1.com/about-us/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Eligibility is limited to individuals in the US only. (Refer-a-Friend program). AG1 may reject orders where\n    the stated delivery address is outside the United States.\nentity_types:\n- type: individual\n  text: In order to use the Websites, you must be 18 years or older and have the power to enter into a binding contract\n    with us\n- type: business\n  text: AG1 Refer-a-Friend Program cannot be used by businesses or corporations or for affiliate\
  \ lead generation.\nrestricted_uses:\n- summary: Personal use only; no resale\n  text: AG1 only accepts orders for personal use. You cannot resell items offered on the Websites.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/athletic-greens/eligibility/athletic-greens-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AG1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Health
- Nutrition
- Supplements
- Direct to Consumer
- E-Commerce
- Subscription
- Wellness
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Shopify
- GraphQL
---

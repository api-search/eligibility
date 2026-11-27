---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine
  entity_types:
  - text: The Service is available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to bind the entity to this Agreement.
    type: business
  minimum_age:
    text: The Service is available only to, and may only be used by, individuals who are 18 years and older
    value: '18'
  restricted_uses:
  - summary: Alcohol purchases require age 21
    text: authorizes that he/she is 21 years of age
  - summary: No commercial resale of products
    text: You hereby agree not to resell or distribute any products for commercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The shipper reserves the right to request a scan of any customer’s photo ID for age verification before shipping any item.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Goldbelly
provenance_date: '2026-11-09'
provider_name: Goldbelly
provider_slug: goldbely
slug: goldbely-eligibility
source_date: '2026-11-09'
source_filename: goldbely-eligibility.yml
source_heading: Eligibility
source_page: https://www.goldbelly.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goldbelly\naid: goldbely\nurl: https://www.goldbelly.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a)\n    in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine\nentity_types:\n- type: individual\n  text: The Service is available only to, and may only be used by, individuals who are 18 years and older who can\n    form legally binding contracts under applicable law.\n- type: business\n  text: If you are registering\
  \ as a business entity, you personally guarantee that you have the authority to bind\n    the entity to this Agreement.\nrestricted_uses:\n- summary: Alcohol purchases require age 21\n  text: authorizes that he/she is 21 years of age\n- summary: No commercial resale of products\n  text: You hereby agree not to resell or distribute any products for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The shipper reserves the right to request a scan of any customer’s photo ID for age verification before\n    shipping any item.\nminimum_age:\n  value: '18'\n  text: The Service is available only to, and may only be used by, individuals who are 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/goldbely/eligibility/goldbely-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Goldbelly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- E-Commerce
- Marketplace
- Gourmet Food
- Gifting
- Food Delivery
- Consumer
---

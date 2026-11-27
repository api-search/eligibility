---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: 18+, UK residents only.
  entity_types:
  - text: In order to contract with us you must be over 18 years of age and possess a valid credit or debit card issued by a bank acceptable to us.
    type: individual
  minimum_age:
    text: In order to contract with us you must be over 18 years of age
    value: '18'
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
name: Fy
provenance_date: '2026-11-09'
provider_name: Fy
provider_slug: fy
slug: fy-eligibility
source_date: '2026-11-09'
source_filename: fy-eligibility.yml
source_heading: Eligibility
source_page: https://www.iamfy.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fy\naid: fy\nurl: https://www.iamfy.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: 18+, UK residents only.\nentity_types:\n- type: individual\n  text: In order to contract with us you must be over 18 years of age and possess a valid credit or debit card issued\n    by a bank acceptable to us.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to contract with us you must be over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/fy/eligibility/fy-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Fy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- E-Commerce
- Retail
- Wall Art
- Home Decor
- Consumer
- Shopify
---

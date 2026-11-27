---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The content and services are based in the United States and provided for access and use only by persons located in the United States.
  entity_types:
  - text: The Platform is intended solely for users who are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Platform is intended solely for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unauthorized products
    text: 'Among unauthorized Marketplace Offerings are the following: intoxicants of any sort; illegal drugs or other illegal products; alcoholic beverages; games of chance; and pornography or graphic adult content, images, or other adult products.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Platform in order to access the Marketplace Offerings.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Buncha
provenance_date: '2026-11-09'
provider_name: Buncha
provider_slug: buncha
slug: buncha-eligibility
source_date: '2026-11-09'
source_filename: buncha-eligibility.yml
source_heading: Eligibility
source_page: https://www.gobuncha.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buncha\naid: buncha\nurl: https://www.gobuncha.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The content and services are based in the United States and provided for access and use only by persons\n    located in the United States.\nentity_types:\n- type: individual\n  text: The Platform is intended solely for users who are at least 18 years of age.\nrestricted_uses:\n- summary: Unauthorized products\n  text: 'Among unauthorized Marketplace Offerings are the following: intoxicants of any sort; illegal drugs or other\n    illegal products; alcoholic beverages;\
  \ games of chance; and pornography or graphic adult content, images, or\n    other adult products.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Platform in order to access the Marketplace Offerings.\nminimum_age:\n  value: '18'\n  text: The Platform is intended solely for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/buncha/eligibility/buncha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Buncha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Grocery
- Delivery
- Logistics
- Consumer
- Sustainability
- Retail
---

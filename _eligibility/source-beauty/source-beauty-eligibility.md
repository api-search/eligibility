---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: Deliveries can be made only to Egypt.
  entity_types:
  - text: We only supply Products for domestic and private use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial, business or resale use
    text: You agree not to use the Products for any commercial, business or resale purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to make a purchase through the Site or to use the services or features made available to you on the Site, you will be required to register.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Source Beauty
provenance_date: '2026-11-10'
provider_name: Source Beauty
provider_slug: source-beauty
slug: source-beauty-eligibility
source_date: '2026-11-10'
source_filename: source-beauty-eligibility.yml
source_heading: Eligibility
source_page: https://sourcebeauty.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Source Beauty\naid: source-beauty\nurl: https://sourcebeauty.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: Deliveries can be made only to Egypt.\nentity_types:\n- type: individual\n  text: We only supply Products for domestic and private use.\nrestricted_uses:\n- summary: No commercial, business or resale use\n  text: You agree not to use the Products for any commercial, business or resale purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to make a purchase through the Site or to use the services or\
  \ features made available to you on\n    the Site, you will be required to register.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/source-beauty/eligibility/source-beauty-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Source Beauty's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Beauty
- Cosmetics
- E-Commerce
- Retail
- Marketplace
- Wellness
- Egypt
- Skincare
- Consumer
---

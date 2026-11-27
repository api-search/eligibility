---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Marketplace is only available to Users of legal age and entrepreneurs with legal capacity within the meaning of § 14 BGB
    type: individual
  - text: entrepreneurs with legal capacity within the meaning of § 14 BGB (German Civil Code)
    type: business
  minimum_age:
    text: Marketplace is only available to Users of legal age
    value: null
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
name: Brandback
provenance_date: '2026-11-09'
provider_name: Brandback
provider_slug: brandback
slug: brandback-eligibility
source_date: '2026-11-09'
source_filename: brandback-eligibility.yml
source_heading: Eligibility
source_page: https://www.brandback.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandback\naid: brandback\nurl: https://www.brandback.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Marketplace is only available to Users of legal age and entrepreneurs with legal capacity within the\n    meaning of § 14 BGB\n- type: business\n  text: entrepreneurs with legal capacity within the meaning of § 14 BGB (German Civil Code)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Marketplace is only available to Users\
  \ of legal age\n"
source_yaml_url: https://artifacts.apis.io/brandback/eligibility/brandback-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Brandback's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Resale
- Recommerce
- E-Commerce
- Retail
- Sustainability
- Fashion
- Circular Economy
---

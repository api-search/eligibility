---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: HOW SHOPPING WORKS (CONSUMERS)
    type: individual
  - text: you confirm that you are acting in the course of business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Age-restricted products
    text: Some products may be age-restricted. Makers are responsible for age-verification and compliance with applicable laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: DELLI may require you to provide business information as part of onboarding.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DELLI
provenance_date: '2026-11-09'
provider_name: DELLI
provider_slug: delli
slug: delli-eligibility
source_date: '2026-11-09'
source_filename: delli-eligibility.yml
source_heading: Eligibility
source_page: https://www.delli.market/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DELLI\naid: delli\nurl: https://www.delli.market/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: HOW SHOPPING WORKS (CONSUMERS)\n- type: business\n  text: you confirm that you are acting in the course of business\nrestricted_uses:\n- summary: Age-restricted products\n  text: Some products may be age-restricted. Makers are responsible for age-verification and compliance with applicable\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: DELLI may require you to provide business\
  \ information as part of onboarding.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delli/eligibility/delli-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from DELLI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Food and Beverage
- E-Commerce
- Consumer
- Independent Makers
- Food Tech
- Shopify
---

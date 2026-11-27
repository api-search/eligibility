---
api_specs:
- filename: aon-pro-openapi-generated.yml
  format: yaml
  label: AON API
  slug: aon-pro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aon-pro/openapi/_ae-authored/aon-pro-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service, and old enough to form a binding contract in your jurisdiction to transact with any partner.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service
    value: '13'
  restricted_uses:
  - summary: Prohibited goods
    text: Use the Service to acquire, attempt to acquire, or solicit offers for goods that are prohibited under applicable law
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
name: AON
provenance_date: '2026-11-09'
provider_name: AON
provider_slug: aon-pro
slug: aon-pro-eligibility
source_date: '2026-11-09'
source_filename: aon-pro-eligibility.yml
source_heading: Eligibility
source_page: https://www.aon.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AON\naid: aon-pro\nurl: https://www.aon.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service, and old enough to form a binding contract in your\n    jurisdiction to transact with any partner.\nrestricted_uses:\n- summary: Prohibited goods\n  text: Use the Service to acquire, attempt to acquire, or solicit offers for goods that are prohibited under applicable\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You must be at least 13 years old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/aon-pro/eligibility/aon-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AON's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Commerce
- Monetization
- OfferNetwork
- Platform
---

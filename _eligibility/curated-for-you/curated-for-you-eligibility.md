---
api_specs:
- filename: curated-for-you-companies-api-openapi.yml
  format: yaml
  label: Curated for You Companies API
  slug: curated-for-you-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-companies-api-openapi.yml
- filename: curated-for-you-curations-api-openapi.yml
  format: yaml
  label: Curated for You Curations API
  slug: curated-for-you-curations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-curations-api-openapi.yml
- filename: curated-for-you-users-api-openapi.yml
  format: yaml
  label: Curated for You Users API
  slug: curated-for-you-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Application and Member Services are available only to individuals that are at least eighteen (18) years of age and that can enter into legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: The Application and Member Services are available only to individuals that are at least eighteen (18) years of age and that can enter into legally binding contracts under applicable law.
    value: '18'
  restricted_uses:
  - summary: Alcohol delivery age
    text: The common carrier will only deliver the package if someone over the age of 21 can sign this label upon receipt.
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
name: Curated for You
provenance_date: '2026-11-09'
provider_name: Curated for You
provider_slug: curated-for-you
slug: curated-for-you-eligibility
source_date: '2026-11-09'
source_filename: curated-for-you-eligibility.yml
source_heading: Eligibility
source_page: https://www.curatedforyou.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curated for You\naid: curated-for-you\nurl: https://www.curatedforyou.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Application and Member Services are available only to individuals that are at least eighteen (18) years\n    of age and that can enter into legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Alcohol delivery age\n  text: The common carrier will only deliver the package if someone over the age of 21 can sign this label upon\n    receipt.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Application and Member Services are available only to individuals that are at least eighteen (18) years\n    of age and that can enter into legally binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/curated-for-you/eligibility/curated-for-you-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Curated for You's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Product Discovery
- Personalization
- Artificial Intelligence
- Curation
- Shopify
- Lifestyle Commerce
---

---
api_specs:
- filename: bybe-clips-api-openapi.yml
  format: yaml
  label: BYBE Clips API
  slug: bybe-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-clips-api-openapi.yml
- filename: bybe-consumers-api-openapi.yml
  format: yaml
  label: BYBE Consumers API
  slug: bybe-consumers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-consumers-api-openapi.yml
- filename: bybe-manufacturers-api-openapi.yml
  format: yaml
  label: BYBE Manufacturers API
  slug: bybe-manufacturers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-manufacturers-api-openapi.yml
- filename: bybe-offers-api-openapi.yml
  format: yaml
  label: BYBE Offers API
  slug: bybe-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-offers-api-openapi.yml
- filename: bybe-products-api-openapi.yml
  format: yaml
  label: BYBE Products API
  slug: bybe-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-products-api-openapi.yml
- filename: bybe-redemptions-api-openapi.yml
  format: yaml
  label: BYBE Redemptions API
  slug: bybe-redemptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-redemptions-api-openapi.yml
- filename: bybe-stores-api-openapi.yml
  format: yaml
  label: BYBE Stores API
  slug: bybe-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bybe/openapi/bybe-stores-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least twenty-one (21) years old to participate in the BYBE rebate program service.
    type: individual
  minimum_age:
    text: You must be at least twenty-one (21) years old to participate in the BYBE rebate program service.
    value: '21'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Additional verification for Account may be asked upon redemption.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BYBE
provenance_date: '2026-11-09'
provider_name: BYBE
provider_slug: bybe
slug: bybe-eligibility
source_date: '2026-11-09'
source_filename: bybe-eligibility.yml
source_heading: Eligibility
source_page: https://bybe.com/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BYBE\naid: bybe\nurl: https://bybe.com/terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least twenty-one (21) years old to participate in the BYBE rebate program service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Additional verification for Account may be asked upon redemption.\nminimum_age:\n  value: '21'\n  text: You must be at least twenty-one (21) years old to participate in the BYBE rebate program service.\n"
source_yaml_url: https://artifacts.apis.io/bybe/eligibility/bybe-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from BYBE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Alcohol
- Beverages
- Promotions
- Rebates
- Marketing
- Retail
- Consumer Packaged Goods
- Loyalty
- Payments
- Disbursements
- Compliance
---

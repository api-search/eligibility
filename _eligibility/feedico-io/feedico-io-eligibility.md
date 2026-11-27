---
api_specs:
- filename: feedico-io-auth-api-openapi.yml
  format: yaml
  label: feedico-io Auth API
  slug: feedico-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-auth-api-openapi.yml
- filename: feedico-io-catalog-api-openapi.yml
  format: yaml
  label: feedico-io Catalog API
  slug: feedico-io-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-catalog-api-openapi.yml
- filename: feedico-io-coupons-api-openapi.yml
  format: yaml
  label: feedico-io Coupons API
  slug: feedico-io-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-coupons-api-openapi.yml
- filename: feedico-io-firms-api-openapi.yml
  format: yaml
  label: feedico-io Firms API
  slug: feedico-io-firms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-firms-api-openapi.yml
- filename: feedico-io-global-catalogue-api-openapi.yml
  format: yaml
  label: feedico-io Global catalogue API
  slug: feedico-io-global-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-global-catalogue-api-openapi.yml
- filename: feedico-io-health-api-openapi.yml
  format: yaml
  label: feedico-io Health API
  slug: feedico-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-health-api-openapi.yml
- filename: feedico-io-products-api-openapi.yml
  format: yaml
  label: feedico-io Products API
  slug: feedico-io-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-products-api-openapi.yml
- filename: feedico-io-user-api-openapi.yml
  format: yaml
  label: feedico-io User API
  slug: feedico-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for businesses and professionals.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Circumventing human verification
    text: Use automated means to create accounts or submit forms in a way that circumvents human verification (such as CAPTCHA) where required.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate registration information and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: feedico-io
provenance_date: '2026-11-09'
provider_name: feedico-io
provider_slug: feedico-io
slug: feedico-io-eligibility
source_date: '2026-11-09'
source_filename: feedico-io-eligibility.yml
source_heading: Eligibility
source_page: https://feedico.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: feedico-io\naid: feedico-io\nurl: https://feedico.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for businesses and professionals.\nrestricted_uses:\n- summary: Circumventing human verification\n  text: Use automated means to create accounts or submit forms in a way that circumvents human verification (such\n    as CAPTCHA) where required.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate registration information and keep it current.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/feedico-io/eligibility/feedico-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from feedico-io's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Marketing
- E-Commerce
- Coupons
---

---
api_specs:
- filename: noozra-building-permits-api-openapi.yml
  format: yaml
  label: Noozra Building permits API
  slug: noozra-building-permits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-building-permits-api-openapi.yml
- filename: noozra-communities-api-openapi.yml
  format: yaml
  label: Noozra Communities API
  slug: noozra-communities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-communities-api-openapi.yml
- filename: noozra-datasets-api-openapi.yml
  format: yaml
  label: Noozra Datasets API
  slug: noozra-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-datasets-api-openapi.yml
- filename: noozra-federal-register-api-openapi.yml
  format: yaml
  label: Noozra Federal Register API
  slug: noozra-federal-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-federal-register-api-openapi.yml
- filename: noozra-government-contracts-api-openapi.yml
  format: yaml
  label: Noozra Government contracts API
  slug: noozra-government-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-government-contracts-api-openapi.yml
- filename: noozra-jobs-api-openapi.yml
  format: yaml
  label: Noozra Jobs API
  slug: noozra-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-jobs-api-openapi.yml
- filename: noozra-new-businesses-api-openapi.yml
  format: yaml
  label: Noozra New businesses API
  slug: noozra-new-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-new-businesses-api-openapi.yml
- filename: noozra-news-api-openapi.yml
  format: yaml
  label: Noozra News API
  slug: noozra-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-news-api-openapi.yml
- filename: noozra-product-recalls-api-openapi.yml
  format: yaml
  label: Noozra Product recalls API
  slug: noozra-product-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-product-recalls-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person gets one free key.
    type: individual
  - text: Using the API in anything that earns money — a product or service you sell, a paid app, a site that runs ads, or work for a client — needs API Pro.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use requires API Pro
    text: Using the API in anything that earns money — a product or service you sell, a paid app, a site that runs ads, or work for a client — needs API Pro.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A new free key needs a card saved to the account, which its bank has checked.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Noozra
provenance_date: '2026-11-10'
provider_name: Noozra
provider_slug: noozra
slug: noozra-eligibility
source_date: '2026-11-10'
source_filename: noozra-eligibility.yml
source_heading: Eligibility
source_page: https://noozra.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noozra\naid: noozra\nurl: https://noozra.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person gets one free key.\n- type: business\n  text: Using the API in anything that earns money — a product or service you sell, a paid app, a site that runs\n    ads, or work for a client — needs API Pro.\nrestricted_uses:\n- summary: Commercial use requires API Pro\n  text: Using the API in anything that earns money — a product or service you sell, a paid app, a site that runs\n    ads, or work for a client — needs API Pro.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: A new free key needs a card saved to the account, which its bank has checked.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/noozra/eligibility/noozra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Noozra's own page on 2026-11-10.
synthetic: false
tags:
- News
- Free
- Community
- Artificial Intelligence
---

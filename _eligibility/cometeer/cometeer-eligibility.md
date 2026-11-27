---
api_specs:
- filename: cometeer-collections-api-openapi.yml
  format: yaml
  label: Cometeer Collections API
  slug: cometeer-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cometeer/openapi/cometeer-collections-api-openapi.yml
- filename: cometeer-products-api-openapi.yml
  format: yaml
  label: Cometeer Products API
  slug: cometeer-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cometeer/openapi/cometeer-products-api-openapi.yml
- filename: cometeer-search-api-openapi.yml
  format: yaml
  label: Cometeer Search API
  slug: cometeer-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cometeer/openapi/cometeer-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Country refers to: the United States of America'
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: null
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
name: Cometeer
provenance_date: '2026-11-09'
provider_name: Cometeer
provider_slug: cometeer
slug: cometeer-eligibility
source_date: '2026-11-09'
source_filename: cometeer-eligibility.yml
source_heading: Eligibility
source_page: https://cometeer.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cometeer\naid: cometeer\nurl: https://cometeer.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Country refers to: the United States of America'\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cometeer/eligibility/cometeer-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Cometeer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coffee
- Food and Beverage
- E-Commerce
- Direct to Consumer
- Retail
- Subscription
- Agentic Commerce
- Shopify
- MCP
---

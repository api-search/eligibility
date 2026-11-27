---
api_specs:
- filename: bright-mls-auth-api-openapi.yml
  format: yaml
  label: Bright MLS Auth API
  slug: bright-mls-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bright-mls/openapi/bright-mls-auth-api-openapi.yml
- filename: bright-mls-listing-api-openapi.yml
  format: yaml
  label: Bright MLS Listing API
  slug: bright-mls-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bright-mls/openapi/bright-mls-listing-api-openapi.yml
- filename: bright-mls-manifests-api-openapi.yml
  format: yaml
  label: Bright MLS Manifests API
  slug: bright-mls-manifests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bright-mls/openapi/bright-mls-manifests-api-openapi.yml
- filename: bright-mls-user-api-openapi.yml
  format: yaml
  label: Bright MLS User API
  slug: bright-mls-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bright-mls/openapi/bright-mls-user-api-openapi.yml
- filename: bright-mls-data-hub-api-openapi.yml
  format: yaml
  label: Bright MLS Data Hub API
  slug: bright-mls-data-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bright-mls/openapi/bright-mls-data-hub-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Unless otherwise specified, the Sites and the Contents are intended to promote Bright’s products and services available in the United States.
  entity_types:
  - text: Bright only extends products and services to adults.
    type: individual
  minimum_age:
    text: Bright only extends products and services to adults.
    value: '18'
  restricted_uses:
  - summary: Users must not use Sites for unlawful or prohibited conduct
    text: You agree not to use the Sites or any Content you may access to engage in any unauthorized or inappropriate conduct or for any unlawful purpose.
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
name: Bright MLS
provenance_date: '2026-11-09'
provider_name: Bright MLS
provider_slug: bright-mls
slug: bright-mls-eligibility
source_date: '2026-11-09'
source_filename: bright-mls-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightmls.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bright MLS\naid: bright-mls\nurl: https://www.brightmls.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Unless otherwise specified, the Sites and the Contents are intended to promote Bright’s products and services\n    available in the United States.\nentity_types:\n- type: individual\n  text: Bright only extends products and services to adults.\nrestricted_uses:\n- summary: Users must not use Sites for unlawful or prohibited conduct\n  text: You agree not to use the Sites or any Content you may access to engage in any unauthorized or inappropriate\n    conduct or for any\
  \ unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Bright only extends products and services to adults.\n"
source_yaml_url: https://artifacts.apis.io/bright-mls/eligibility/bright-mls-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bright MLS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- MLS
- RESO
- OData
- Listings
- Property Data
---

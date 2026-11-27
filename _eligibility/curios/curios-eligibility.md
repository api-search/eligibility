---
api_specs:
- filename: curios-collections-api-openapi.yml
  format: yaml
  label: Curios Collections API
  slug: curios-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-collections-api-openapi.yml
- filename: curios-contracts-api-openapi.yml
  format: yaml
  label: Curios Contracts API
  slug: curios-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-contracts-api-openapi.yml
- filename: curios-customers-api-openapi.yml
  format: yaml
  label: Curios Customers API
  slug: curios-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-customers-api-openapi.yml
- filename: curios-listings-api-openapi.yml
  format: yaml
  label: Curios Listings API
  slug: curios-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-listings-api-openapi.yml
- filename: curios-orders-api-openapi.yml
  format: yaml
  label: Curios Orders API
  slug: curios-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-orders-api-openapi.yml
- filename: curios-projects-api-openapi.yml
  format: yaml
  label: Curios Projects API
  slug: curios-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-projects-api-openapi.yml
- filename: curios-tokens-api-openapi.yml
  format: yaml
  label: Curios Tokens API
  slug: curios-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-tokens-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Curios is not available in any jurisdiction where its use is prohibited by law.
  entity_types:
  - text: To use Curios, you must be at least 18 years of age or have parental consent if under the legal age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age or have parental consent if under the legal age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Fraudulent, illegal, harassing or disruptive activity
    text: you must not engage in any fraudulent, illegal, harassing, or disruptive activities, or attempt to interfere with the proper functioning of the platform.
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
name: Curios
provenance_date: '2026-11-09'
provider_name: Curios
provider_slug: curios
slug: curios-eligibility
source_date: '2026-11-09'
source_filename: curios-eligibility.yml
source_heading: Eligibility
source_page: https://www.curios.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curios\naid: curios\nurl: https://www.curios.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Curios is not available in any jurisdiction where its use is prohibited by law.\nentity_types:\n- type: individual\n  text: To use Curios, you must be at least 18 years of age or have parental consent if under the legal age of majority\n    in your jurisdiction.\nrestricted_uses:\n- summary: Fraudulent, illegal, harassing or disruptive activity\n  text: you must not engage in any fraudulent, illegal, harassing, or disruptive activities, or attempt to interfere\n    with the\
  \ proper functioning of the platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age or have parental consent if under the legal age of majority in your\n    jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/curios/eligibility/curios-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Curios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Web3
- Creators
---

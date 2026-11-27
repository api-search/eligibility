---
api_specs:
- filename: equibles-equibles-api-api-openapi.yml
  format: yaml
  label: Equibles Equibles API
  slug: equibles-equibles-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-equibles-api-api-openapi.yml
- filename: equibles-etfs-api-openapi.yml
  format: yaml
  label: Equibles Etfs API
  slug: equibles-etfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-etfs-api-openapi.yml
- filename: equibles-fda-api-openapi.yml
  format: yaml
  label: Equibles Fda API
  slug: equibles-fda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-fda-api-openapi.yml
- filename: equibles-funds-api-openapi.yml
  format: yaml
  label: Equibles Funds API
  slug: equibles-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-funds-api-openapi.yml
- filename: equibles-investment-advisers-api-openapi.yml
  format: yaml
  label: Equibles Investment Advisers API
  slug: equibles-investment-advisers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-investment-advisers-api-openapi.yml
- filename: equibles-ipos-api-openapi.yml
  format: yaml
  label: Equibles Ipos API
  slug: equibles-ipos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-ipos-api-openapi.yml
- filename: equibles-short-interest-api-openapi.yml
  format: yaml
  label: Equibles Short Interest API
  slug: equibles-short-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-interest-api-openapi.yml
- filename: equibles-short-volume-api-openapi.yml
  format: yaml
  label: Equibles Short Volume API
  slug: equibles-short-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-volume-api-openapi.yml
- filename: equibles-stocks-api-openapi.yml
  format: yaml
  label: Equibles Stocks API
  slug: equibles-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-stocks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into a contract.
    type: individual
  - text: If you use the Service for a company or other organization, you represent that you may bind that organization, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the Service unlawfully, fraudulently, or to infringe another person's rights;
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
name: Equibles
provenance_date: '2026-11-09'
provider_name: Equibles
provider_slug: equibles
slug: equibles-eligibility
source_date: '2026-11-09'
source_filename: equibles-eligibility.yml
source_heading: Eligibility
source_page: https://equibles.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Equibles\naid: equibles\nurl: https://equibles.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into a contract.\n- type: business\n  text: If you use the Service for a company or other organization, you represent that you may bind that organization,\n    and \"you\" includes that organization.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Service unlawfully, fraudulently, or to infringe another person's rights;\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a contract.\n"
source_yaml_url: https://artifacts.apis.io/equibles/eligibility/equibles-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Equibles's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Stocks
---

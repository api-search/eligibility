---
api_specs:
- filename: bp-cards-api-openapi.yml
  format: yaml
  label: BP Cards API
  slug: bp-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-cards-api-openapi.yml
- filename: bp-fueling-api-openapi.yml
  format: yaml
  label: BP Fueling API
  slug: bp-fueling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-fueling-api-openapi.yml
- filename: bp-openapiinvoices-api-openapi.yml
  format: yaml
  label: BP Open API Invoices API
  slug: bp-openapiinvoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-openapiinvoices-api-openapi.yml
- filename: bp-openapitransactions-api-openapi.yml
  format: yaml
  label: BP Open API Transactions API
  slug: bp-openapitransactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-openapitransactions-api-openapi.yml
- filename: bp-sitediscovery-api-openapi.yml
  format: yaml
  label: BP Site Discovery API
  slug: bp-sitediscovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-sitediscovery-api-openapi.yml
- filename: bp-token-api-openapi.yml
  format: yaml
  label: BP Token API
  slug: bp-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-token-api-openapi.yml
- filename: bp-health-check-api-openapi.yml
  format: yaml
  label: BP Health Check API
  slug: bp-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-health-check-api-openapi.yml
- filename: bp-payment-method-api-openapi.yml
  format: yaml
  label: BP Payment Method API
  slug: bp-payment-method-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-payment-method-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Any persons resident outside the United Kingdom who access this site must first satisfy themselves that they are not subject to any local requirements which prohibit or restrict them from doing so.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Jurisdictions where activity is prohibited
    text: None of the services or investments referred to on this site are available or appropriate for sale or use in any jurisdiction where such activity is prohibited.
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
name: BP
provenance_date: '2026-11-09'
provider_name: BP
provider_slug: bp
slug: bp-eligibility
source_date: '2026-11-09'
source_filename: bp-eligibility.yml
source_heading: Eligibility
source_page: https://www.bp.com/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BP\naid: bp\nurl: https://www.bp.com/legal-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Any persons resident outside the United Kingdom who access this site must first satisfy themselves that\n    they are not subject to any local requirements which prohibit or restrict them from doing so.\nentity_types: []\nrestricted_uses:\n- summary: Jurisdictions where activity is prohibited\n  text: None of the services or investments referred to on this site are available or appropriate for sale or use\n    in any jurisdiction where such activity is prohibited.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bp/eligibility/bp-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BP's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Oil
- Gas
- Renewables
- Developer Platform
- Fleet Management
- Fuel Cards
- Mobility
- Retail Fuel
- EV Charging
- Oil and Gas
---

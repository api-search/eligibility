---
api_specs:
- filename: howtoromania-io-billing-api-openapi.yml
  format: yaml
  label: HowToRomania Billing API
  slug: howtoromania-io-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-billing-api-openapi.yml
- filename: howtoromania-io-bnr-rates-free-api-openapi.yml
  format: yaml
  label: HowToRomania BNR rates (free) API
  slug: howtoromania-io-bnr-rates-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-bnr-rates-free-api-openapi.yml
- filename: howtoromania-io-companies-api-openapi.yml
  format: yaml
  label: HowToRomania Companies API
  slug: howtoromania-io-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-companies-api-openapi.yml
- filename: howtoromania-io-courts-api-openapi.yml
  format: yaml
  label: HowToRomania Courts API
  slug: howtoromania-io-courts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-courts-api-openapi.yml
- filename: howtoromania-io-e-factura-api-openapi.yml
  format: yaml
  label: HowToRomania E Factura API
  slug: howtoromania-io-e-factura-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-e-factura-api-openapi.yml
- filename: howtoromania-io-keys-api-openapi.yml
  format: yaml
  label: HowToRomania Keys API
  slug: howtoromania-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-keys-api-openapi.yml
- filename: howtoromania-io-legislation-api-openapi.yml
  format: yaml
  label: HowToRomania Legislation API
  slug: howtoromania-io-legislation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-legislation-api-openapi.yml
- filename: howtoromania-io-me-api-openapi.yml
  format: yaml
  label: HowToRomania Me API
  slug: howtoromania-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-me-api-openapi.yml
- filename: howtoromania-io-pricing-api-openapi.yml
  format: yaml
  label: HowToRomania Pricing API
  slug: howtoromania-io-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-pricing-api-openapi.yml
- filename: howtoromania-io-validation-api-openapi.yml
  format: yaml
  label: HowToRomania Validation API
  slug: howtoromania-io-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-validation-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a business, you will defend, indemnify and hold us harmless against all reasonable costs
    type: business
  - text: If you are a consumer in the EU, you normally have a 14-day right of withdrawal.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Significant decisions about individuals
    text: Make decisions with legal or similarly significant effects about natural persons (for example credit, employment, housing, insurance) based on the Service without meaningful human review
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: A free API key is created with an email address (POST /v1/keys).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: howtoromania-io
provenance_date: '2026-11-09'
provider_name: HowToRomania
provider_slug: howtoromania-io
slug: howtoromania-io-eligibility
source_date: '2026-11-09'
source_filename: howtoromania-io-eligibility.yml
source_heading: Eligibility
source_page: https://howtoromania.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: howtoromania-io\naid: howtoromania-io\nurl: https://howtoromania.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a business, you will defend, indemnify and hold us harmless against all reasonable costs\n- type: individual\n  text: If you are a consumer in the EU, you normally have a 14-day right of withdrawal.\nrestricted_uses:\n- summary: Significant decisions about individuals\n  text: Make decisions with legal or similarly significant effects about natural persons (for example credit, employment,\n    housing,\
  \ insurance) based on the Service without meaningful human review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: A free API key is created with an email address (POST /v1/keys).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/howtoromania-io/eligibility/howtoromania-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from howtoromania-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Finance
- Legal
- Artificial Intelligence
---

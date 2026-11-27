---
api_specs:
- filename: shoppable-catalog-api-openapi.yml
  format: yaml
  label: Shoppable Catalog API
  slug: shoppable-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-catalog-api-openapi.yml
- filename: shoppable-checkout-api-openapi.yml
  format: yaml
  label: Shoppable Checkout API
  slug: shoppable-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-checkout-api-openapi.yml
- filename: shoppable-merchants-api-openapi.yml
  format: yaml
  label: Shoppable Merchants API
  slug: shoppable-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-merchants-api-openapi.yml
- filename: shoppable-orderdata-api-openapi.yml
  format: yaml
  label: Shoppable OrderData API
  slug: shoppable-orderdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-orderdata-api-openapi.yml
- filename: shoppable-orders-api-openapi.yml
  format: yaml
  label: Shoppable Orders API
  slug: shoppable-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-orders-api-openapi.yml
- filename: shoppable-products-api-openapi.yml
  format: yaml
  label: Shoppable Products API
  slug: shoppable-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shoppable/openapi/shoppable-products-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are based in the United States. We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: The Services are available for individuals aged 13 years or older.
    type: individual
  minimum_age:
    text: The Services are available for individuals aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: You will not use the Services for any unlawful purpose;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We are under no obligation to accept any individual as a Registered User, and may accept or reject any registration in our sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shoppable
provenance_date: '2026-11-10'
provider_name: Shoppable
provider_slug: shoppable
slug: shoppable-eligibility
source_date: '2026-11-10'
source_filename: shoppable-eligibility.yml
source_heading: Eligibility
source_page: https://about.shoppable.com/terms#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shoppable\naid: shoppable\nurl: https://about.shoppable.com/terms#terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are based in the United States. We make no claims concerning whether the Content may be downloaded,\n    viewed, or be appropriate for use outside of the United States.\nentity_types:\n- type: individual\n  text: The Services are available for individuals aged 13 years or older.\nrestricted_uses:\n- summary: Unlawful use\n  text: You will not use the Services for any unlawful purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: We are under no obligation to accept any individual as a Registered User, and may accept or reject any registration\n    in our sole and complete discretion.\nminimum_age:\n  value: '13'\n  text: The Services are available for individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/shoppable/eligibility/shoppable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Shoppable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Checkout
- Catalog
- Payments
- Agentic Commerce
- MCP
- Embeddable Commerce
- Retail
---

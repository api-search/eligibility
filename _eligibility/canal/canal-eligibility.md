---
api_specs:
- filename: canal-csv-api-openapi.yml
  format: yaml
  label: Canal CSV API
  slug: canal-csv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-csv-api-openapi.yml
- filename: canal-fulfillments-api-openapi.yml
  format: yaml
  label: Canal Fulfillments API
  slug: canal-fulfillments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-fulfillments-api-openapi.yml
- filename: canal-markets-api-openapi.yml
  format: yaml
  label: Canal Markets API
  slug: canal-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-markets-api-openapi.yml
- filename: canal-max-shipping-rates-api-openapi.yml
  format: yaml
  label: Canal Max Shipping Rates API
  slug: canal-max-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-max-shipping-rates-api-openapi.yml
- filename: canal-orders-api-openapi.yml
  format: yaml
  label: Canal Orders API
  slug: canal-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-orders-api-openapi.yml
- filename: canal-product-sets-api-openapi.yml
  format: yaml
  label: Canal Product Sets API
  slug: canal-product-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-product-sets-api-openapi.yml
- filename: canal-products-api-openapi.yml
  format: yaml
  label: Canal Products API
  slug: canal-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-products-api-openapi.yml
- filename: canal-refunds-api-openapi.yml
  format: yaml
  label: Canal Refunds API
  slug: canal-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-refunds-api-openapi.yml
- filename: canal-returns-api-openapi.yml
  format: yaml
  label: Canal Returns API
  slug: canal-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-returns-api-openapi.yml
- filename: canal-selection-api-openapi.yml
  format: yaml
  label: Canal Selection API
  slug: canal-selection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-selection-api-openapi.yml
- filename: canal-shipping-api-openapi.yml
  format: yaml
  label: Canal Shipping API
  slug: canal-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-shipping-api-openapi.yml
- filename: canal-shipping-rates-api-openapi.yml
  format: yaml
  label: Canal Shipping Rates API
  slug: canal-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-shipping-rates-api-openapi.yml
- filename: canal-shops-api-openapi.yml
  format: yaml
  label: Canal Shops API
  slug: canal-shops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-shops-api-openapi.yml
- filename: canal-tax-and-shipping-api-openapi.yml
  format: yaml
  label: Canal Tax And Shipping API
  slug: canal-tax-and-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-tax-and-shipping-api-openapi.yml
- filename: canal-tax-api-openapi.yml
  format: yaml
  label: Canal Tax API
  slug: canal-tax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-tax-api-openapi.yml
- filename: canal-variants-api-openapi.yml
  format: yaml
  label: Canal Variants API
  slug: canal-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-variants-api-openapi.yml
- filename: canal-webhooks-api-openapi.yml
  format: yaml
  label: Canal Webhooks API
  slug: canal-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canal/openapi/canal-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this Agreement
    type: business
  - text: You are eighteen (18) years old or older
    type: individual
  minimum_age:
    text: You are eighteen (18) years old or older
    value: '18'
  restricted_uses:
  - summary: No sales of age-restricted products to minors
    text: You agree that you will not sell or distribute any alcohol, tobacco, or other age-restricted products to people who are under the minimum legal age required by the applicable jurisdiction.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Retailers without a recognized and verified payment or billing method will not be activated or granted access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Canal
provenance_date: '2026-11-09'
provider_name: Canal
provider_slug: canal
slug: canal-eligibility
source_date: '2026-11-09'
source_filename: canal-eligibility.yml
source_heading: Eligibility
source_page: https://www.rokt.com/policies/terms-for-rokt-catalog-for-brands
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canal\naid: canal\nurl: https://www.rokt.com/policies/terms-for-rokt-catalog-for-brands\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this Agreement\n- type: individual\n  text: You are eighteen (18) years old or older\nrestricted_uses:\n- summary: No sales of age-restricted products to minors\n  text: You agree that you will not sell\
  \ or distribute any alcohol, tobacco, or other age-restricted products to\n    people who are under the minimum legal age required by the applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Retailers without a recognized and verified payment or billing method will not be activated or granted access.\nminimum_age:\n  value: '18'\n  text: You are eighteen (18) years old or older\n"
source_yaml_url: https://artifacts.apis.io/canal/eligibility/canal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Canal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Dropshipping
- Marketplace
- Commerce
- Retail
- Fulfillment
- Order
- Product
- Webhook
---

---
api_specs:
- filename: goody-brands-api-openapi.yml
  format: yaml
  label: Goody Brands API
  slug: goody-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-brands-api-openapi.yml
- filename: goody-cards-api-openapi.yml
  format: yaml
  label: Goody Cards API
  slug: goody-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-cards-api-openapi.yml
- filename: goody-collections-api-openapi.yml
  format: yaml
  label: Goody Collections API
  slug: goody-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-collections-api-openapi.yml
- filename: goody-commerce-user-payment-methods-api-openapi.yml
  format: yaml
  label: Goody Commerce User Payment Methods API
  slug: goody-commerce-user-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-commerce-user-payment-methods-api-openapi.yml
- filename: goody-me-api-openapi.yml
  format: yaml
  label: Goody Me API
  slug: goody-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-me-api-openapi.yml
- filename: goody-order-activities-api-openapi.yml
  format: yaml
  label: Goody Order Activities API
  slug: goody-order-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-order-activities-api-openapi.yml
- filename: goody-order-batches-api-openapi.yml
  format: yaml
  label: Goody Order Batches API
  slug: goody-order-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-order-batches-api-openapi.yml
- filename: goody-orders-api-openapi.yml
  format: yaml
  label: Goody Orders API
  slug: goody-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-orders-api-openapi.yml
- filename: goody-payment-methods-api-openapi.yml
  format: yaml
  label: Goody Payment Methods API
  slug: goody-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-payment-methods-api-openapi.yml
- filename: goody-products-api-openapi.yml
  format: yaml
  label: Goody Products API
  slug: goody-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-products-api-openapi.yml
- filename: goody-webhooks-api-openapi.yml
  format: yaml
  label: Goody Webhooks API
  slug: goody-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-webhooks-api-openapi.yml
- filename: goody-workspaces-api-openapi.yml
  format: yaml
  label: Goody Workspaces API
  slug: goody-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-workspaces-api-openapi.yml
- filename: goody-categories-api-openapi.yml
  format: yaml
  label: Goody Categories API
  slug: goody-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-categories-api-openapi.yml
- filename: goody-gift-templates-api-openapi.yml
  format: yaml
  label: Goody Gift Templates API
  slug: goody-gift-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-gift-templates-api-openapi.yml
- filename: goody-gifts-of-choice-api-openapi.yml
  format: yaml
  label: Goody Gifts of Choice API
  slug: goody-gifts-of-choice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-gifts-of-choice-api-openapi.yml
- filename: goody-shipping-countries-api-openapi.yml
  format: yaml
  label: Goody Shipping Countries API
  slug: goody-shipping-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goody/openapi/goody-shipping-countries-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Client shall only use the Service, and shall limit Users access to the Service, only within the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or harassing client data
    text: Client will not input or share any Client Data to or through the Service that is unlawful, harassing, libelous, defamatory or threatening.
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
name: Goody
provenance_date: '2026-11-09'
provider_name: Goody
provider_slug: goody
slug: goody-eligibility
source_date: '2026-11-09'
source_filename: goody-eligibility.yml
source_heading: Eligibility
source_page: https://assets.ongoody.com/static/terms/PlusTermsAndConditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goody\naid: goody\nurl: https://assets.ongoody.com/static/terms/PlusTermsAndConditions.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Client shall only use the Service, and shall limit Users access to the Service, only within the United States.\nentity_types: []\nrestricted_uses:\n- summary: No unlawful or harassing client data\n  text: Client will not input or share any Client Data to or through the Service that is unlawful, harassing, libelous,\n    defamatory or threatening.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goody/eligibility/goody-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Goody's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Gifting
- Gift Cards
- E-Commerce
- Commerce
- Payments
- MCP
- Webhook
- Rewards
---

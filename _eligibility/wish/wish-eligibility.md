---
api_specs:
- filename: wish-brands-api-openapi.yml
  format: yaml
  label: Wish Brands API
  slug: wish-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-brands-api-openapi.yml
- filename: wish-bulk-products-api-openapi.yml
  format: yaml
  label: Wish Bulk Products API
  slug: wish-bulk-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-bulk-products-api-openapi.yml
- filename: wish-currencies-api-openapi.yml
  format: yaml
  label: Wish Currencies API
  slug: wish-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-currencies-api-openapi.yml
- filename: wish-eu-product-compliance-api-openapi.yml
  format: yaml
  label: Wish EU Product Compliance API
  slug: wish-eu-product-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-eu-product-compliance-api-openapi.yml
- filename: wish-france-epr-compliance-api-openapi.yml
  format: yaml
  label: Wish France EPR Compliance API
  slug: wish-france-epr-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-france-epr-compliance-api-openapi.yml
- filename: wish-germany-epr-compliance-api-openapi.yml
  format: yaml
  label: Wish Germany EPR Compliance API
  slug: wish-germany-epr-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-germany-epr-compliance-api-openapi.yml
- filename: wish-merchant-api-openapi.yml
  format: yaml
  label: Wish Merchant API
  slug: wish-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-merchant-api-openapi.yml
- filename: wish-orders-api-openapi.yml
  format: yaml
  label: Wish Orders API
  slug: wish-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-orders-api-openapi.yml
- filename: wish-payments-api-openapi.yml
  format: yaml
  label: Wish Payments API
  slug: wish-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-payments-api-openapi.yml
- filename: wish-penalties-api-openapi.yml
  format: yaml
  label: Wish Penalties API
  slug: wish-penalties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-penalties-api-openapi.yml
- filename: wish-productboost-api-openapi.yml
  format: yaml
  label: Wish ProductBoost API
  slug: wish-productboost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-productboost-api-openapi.yml
- filename: wish-products-api-openapi.yml
  format: yaml
  label: Wish Products API
  slug: wish-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-products-api-openapi.yml
- filename: wish-promotions-platform-api-openapi.yml
  format: yaml
  label: Wish Promotions Platform API
  slug: wish-promotions-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-promotions-platform-api-openapi.yml
- filename: wish-ratings-api-openapi.yml
  format: yaml
  label: Wish Ratings API
  slug: wish-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-ratings-api-openapi.yml
- filename: wish-taxonomy-api-openapi.yml
  format: yaml
  label: Wish Taxonomy API
  slug: wish-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-taxonomy-api-openapi.yml
- filename: wish-tickets-api-openapi.yml
  format: yaml
  label: Wish Tickets API
  slug: wish-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-tickets-api-openapi.yml
- filename: wish-unification-initiative-api-openapi.yml
  format: yaml
  label: Wish Unification Initiative API
  slug: wish-unification-initiative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-unification-initiative-api-openapi.yml
- filename: wish-variations-api-openapi.yml
  format: yaml
  label: Wish Variations API
  slug: wish-variations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-variations-api-openapi.yml
- filename: wish-videos-api-openapi.yml
  format: yaml
  label: Wish Videos API
  slug: wish-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-videos-api-openapi.yml
- filename: wish-webhook-api-openapi.yml
  format: yaml
  label: Wish Webhook API
  slug: wish-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-webhook-api-openapi.yml
- filename: wish-oauth-api-openapi.yml
  format: yaml
  label: Wish O Auth API
  slug: wish-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wish/openapi/wish-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are located in a country embargoed by the United States
  entity_types:
  - text: In order to use the Services, you must be 13 years old or older (or the age of consent set by applicable law)
    type: individual
  minimum_age:
    text: you must be 13 years old or older (or the age of consent set by applicable law)
    value: '13'
  restricted_uses:
  - summary: Robots and automated access
    text: Only use (or attempt to use) the Services through interfaces provided by Wish; and Comply with the instructions in any robots.txt file present on the Services.
  - summary: Spam or auto-responders
    text: Run a Maillist, Listserv, or any form of auto-responder or "spam" on the Services
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
name: Wish
provenance_date: '2026-11-10'
provider_name: Wish
provider_slug: wish
slug: wish-eligibility
source_date: '2026-11-10'
source_filename: wish-eligibility.yml
source_heading: Eligibility
source_page: https://www.wish.com/en-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wish\naid: wish\nurl: https://www.wish.com/en-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are located in a country embargoed by the United States\nentity_types:\n- type: individual\n  text: In order to use the Services, you must be 13 years old or older (or the age of consent set by applicable\n    law)\nrestricted_uses:\n- summary: Robots and automated access\n  text: Only use (or attempt to use) the Services through interfaces provided by Wish; and Comply with the instructions\n    in any robots.txt file present on the Services.\n- summary: Spam\
  \ or auto-responders\n  text: Run a Maillist, Listserv, or any form of auto-responder or \"spam\" on the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be 13 years old or older (or the age of consent set by applicable law)\n"
source_yaml_url: https://artifacts.apis.io/wish/eligibility/wish-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wish's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Retail
- Merchants
- Order
- Product
- Fulfillment
- Shopping
- OAuth
- Authentication
---

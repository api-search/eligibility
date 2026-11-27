---
api_specs:
- filename: bourdain-acp-checkout-api-openapi.yml
  format: yaml
  label: Bourdain Acp Checkout API
  slug: bourdain-acp-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-checkout-api-openapi.yml
- filename: bourdain-acp-confirm-api-openapi.yml
  format: yaml
  label: Bourdain Acp Confirm API
  slug: bourdain-acp-confirm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-confirm-api-openapi.yml
- filename: bourdain-acp-payment-api-openapi.yml
  format: yaml
  label: Bourdain Acp Payment API
  slug: bourdain-acp-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-payment-api-openapi.yml
- filename: bourdain-acp-product-api-openapi.yml
  format: yaml
  label: Bourdain Acp Product API
  slug: bourdain-acp-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-product-api-openapi.yml
- filename: bourdain-acp-products-api-openapi.yml
  format: yaml
  label: Bourdain Acp Products API
  slug: bourdain-acp-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-products-api-openapi.yml
- filename: bourdain-mcp-server-api-openapi.yml
  format: yaml
  label: Bourdain Mcp Server API
  slug: bourdain-mcp-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-mcp-server-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use this Platform.
    value: '18'
  restricted_uses:
  - summary: Prohibited item listings
    text: 'Sellers may not list prohibited items including but not limited to: illegal goods, weapons, drugs, stolen items, or items that infringe on intellectual property rights.'
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
name: Bourdain
provenance_date: '2026-11-09'
provider_name: Bourdain
provider_slug: bourdain
slug: bourdain-eligibility
source_date: '2026-11-09'
source_filename: bourdain-eligibility.yml
source_heading: Eligibility
source_page: https://www.bourdain.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bourdain\naid: bourdain\nurl: https://www.bourdain.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited item listings\n  text: 'Sellers may not list prohibited items including but not limited to: illegal goods, weapons, drugs, stolen\n    items, or items that infringe on intellectual property rights.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use this Platform.\n"
source_yaml_url: https://artifacts.apis.io/bourdain/eligibility/bourdain-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bourdain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Trading Cards
- Artificial Intelligence
- E-Commerce
- Collectibles
---

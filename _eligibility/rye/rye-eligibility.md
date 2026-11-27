---
api_specs:
- filename: rye-betas-api-openapi.yml
  format: yaml
  label: Rye Betas API
  slug: rye-betas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-betas-api-openapi.yml
- filename: rye-billing-api-openapi.yml
  format: yaml
  label: Rye Billing API
  slug: rye-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-billing-api-openapi.yml
- filename: rye-brands-api-openapi.yml
  format: yaml
  label: Rye Brands API
  slug: rye-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-brands-api-openapi.yml
- filename: rye-checkout-intents-api-openapi.yml
  format: yaml
  label: Rye Checkout Intents API
  slug: rye-checkout-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-checkout-intents-api-openapi.yml
- filename: rye-commissions-api-openapi.yml
  format: yaml
  label: Rye Commissions API
  slug: rye-commissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-commissions-api-openapi.yml
- filename: rye-events-api-openapi.yml
  format: yaml
  label: Rye Events API
  slug: rye-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-events-api-openapi.yml
- filename: rye-merchant-connectors-api-openapi.yml
  format: yaml
  label: Rye Merchant Connectors API
  slug: rye-merchant-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-merchant-connectors-api-openapi.yml
- filename: rye-orders-api-openapi.yml
  format: yaml
  label: Rye Orders API
  slug: rye-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-orders-api-openapi.yml
- filename: rye-payment-gateways-api-openapi.yml
  format: yaml
  label: Rye Payment Gateways API
  slug: rye-payment-gateways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-payment-gateways-api-openapi.yml
- filename: rye-products-api-openapi.yml
  format: yaml
  label: Rye Products API
  slug: rye-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-products-api-openapi.yml
- filename: rye-returns-api-openapi.yml
  format: yaml
  label: Rye Returns API
  slug: rye-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-returns-api-openapi.yml
- filename: rye-shipments-api-openapi.yml
  format: yaml
  label: Rye Shipments API
  slug: rye-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-shipments-api-openapi.yml
- filename: rye-test-helpers-api-openapi.yml
  format: yaml
  label: Rye Test Helpers API
  slug: rye-test-helpers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rye/openapi/rye-test-helpers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are eighteen (18) years old or older; and You have the authority to enter into this Agreement personally as an authorized user of our Customer (defined below).
    type: individual
  minimum_age:
    text: You are eighteen (18) years old or older
    value: '18'
  restricted_uses:
  - summary: Export controls
    text: Except as authorized by law, you agree and warrant not to export or re-export the software to any county, or to any person, entity, or end-user subject to U.S. export controls or sanctions
  - summary: No deceptive or fraudulent use
    text: use the Services for deceptive or fraudulent purposes
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
name: Rye
provenance_date: '2026-11-10'
provider_name: Rye
provider_slug: rye
slug: rye-eligibility
source_date: '2026-11-10'
source_filename: rye-eligibility.yml
source_heading: Eligibility
source_page: https://rye.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rye\naid: rye\nurl: https://rye.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are eighteen (18) years old or older; and You have the authority to enter into this Agreement personally\n    as an authorized user of our Customer (defined below).\nrestricted_uses:\n- summary: Export controls\n  text: Except as authorized by law, you agree and warrant not to export or re-export the software to any county,\n    or to any person, entity, or end-user subject to U.S. export controls or sanctions\n- summary: No deceptive\
  \ or fraudulent use\n  text: use the Services for deceptive or fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are eighteen (18) years old or older\n"
source_yaml_url: https://artifacts.apis.io/rye/eligibility/rye-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rye's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Checkout
- Payments
- Agentic Commerce
- AI Agents
- Universal Checkout
- Shopping
---

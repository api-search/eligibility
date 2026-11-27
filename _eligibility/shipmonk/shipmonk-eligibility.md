---
api_specs:
- filename: shipmonk-webhooks-asyncapi.yml
  format: yaml
  label: ShipMonk Webhooks
  slug: shipmonk-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/shipmonk/asyncapi/shipmonk-webhooks-asyncapi.yml
- filename: shipmonk-orders-api-openapi.yml
  format: yaml
  label: ShipMonk Orders API
  slug: shipmonk-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-orders-api-openapi.yml
- filename: shipmonk-products-api-openapi.yml
  format: yaml
  label: ShipMonk Products API
  slug: shipmonk-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-products-api-openapi.yml
- filename: shipmonk-receivings-api-openapi.yml
  format: yaml
  label: ShipMonk Receivings API
  slug: shipmonk-receivings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-receivings-api-openapi.yml
- filename: shipmonk-returns-api-openapi.yml
  format: yaml
  label: ShipMonk Returns API
  slug: shipmonk-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-returns-api-openapi.yml
- filename: shipmonk-warehouses-api-openapi.yml
  format: yaml
  label: ShipMonk Warehouses API
  slug: shipmonk-warehouses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-warehouses-api-openapi.yml
- filename: shipmonk-webhooks-api-openapi.yml
  format: yaml
  label: ShipMonk Webhooks API
  slug: shipmonk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipmonk/openapi/shipmonk-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are currently provided from the United States.
  entity_types:
  - text: the Company is in the business of selling and/or manufacturing certain Products
    type: business
  minimum_age:
    text: If you are under 18, you may use ShipMonk.com only with the involvement of a parent or guardian.
    value: null
  restricted_uses:
  - summary: Acceptable use violations
    text: Violating this policy may also result in temporary or permanent limitation of a user’s Account, a held Account, termination of an account with 30 days’ notice, or immediate termination.
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
name: ShipMonk
provenance_date: '2026-11-10'
provider_name: ShipMonk
provider_slug: shipmonk
slug: shipmonk-eligibility
source_date: '2026-11-10'
source_filename: shipmonk-eligibility.yml
source_heading: Eligibility
source_page: https://www.shipmonk.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShipMonk\naid: shipmonk\nurl: https://www.shipmonk.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are currently provided from the United States.\nentity_types:\n- type: business\n  text: the Company is in the business of selling and/or manufacturing certain Products\nrestricted_uses:\n- summary: Acceptable use violations\n  text: Violating this policy may also result in temporary or permanent limitation of a user’s Account, a held Account,\n    termination of an account with 30 days’ notice, or immediate termination.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are under 18, you may use ShipMonk.com only with the involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/shipmonk/eligibility/shipmonk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ShipMonk's own page on 2026-11-10.
synthetic: false
tags:
- Logistics
- Fulfillment
- 3PL
- E-Commerce
- Warehousing
- Inventory
- Shipping
- Returns
- Supply Chain
- Direct to Consumer
- Order Management
---

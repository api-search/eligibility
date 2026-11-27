---
api_specs:
- filename: finditparts-addresses-api-openapi.yml
  format: yaml
  label: FinditParts Addresses API
  slug: finditparts-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-addresses-api-openapi.yml
- filename: finditparts-carts-api-openapi.yml
  format: yaml
  label: FinditParts Carts API
  slug: finditparts-carts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-carts-api-openapi.yml
- filename: finditparts-orders-api-openapi.yml
  format: yaml
  label: FinditParts Orders API
  slug: finditparts-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-orders-api-openapi.yml
- filename: finditparts-partners-api-openapi.yml
  format: yaml
  label: FinditParts Partners API
  slug: finditparts-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-partners-api-openapi.yml
- filename: finditparts-products-api-openapi.yml
  format: yaml
  label: FinditParts Products API
  slug: finditparts-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-products-api-openapi.yml
- filename: finditparts-reseller-customer-sessions-api-openapi.yml
  format: yaml
  label: FinditParts Reseller Customer Sessions API
  slug: finditparts-reseller-customer-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-reseller-customer-sessions-api-openapi.yml
- filename: finditparts-reseller-customers-api-openapi.yml
  format: yaml
  label: FinditParts Reseller Customers API
  slug: finditparts-reseller-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-reseller-customers-api-openapi.yml
- filename: finditparts-sessions-api-openapi.yml
  format: yaml
  label: FinditParts Sessions API
  slug: finditparts-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-sessions-api-openapi.yml
- filename: finditparts-shipping-api-openapi.yml
  format: yaml
  label: FinditParts Shipping API
  slug: finditparts-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-shipping-api-openapi.yml
- filename: finditparts-users-api-openapi.yml
  format: yaml
  label: FinditParts Users API
  slug: finditparts-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-users-api-openapi.yml
- filename: finditparts-variants-api-openapi.yml
  format: yaml
  label: FinditParts Variants API
  slug: finditparts-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finditparts/openapi/finditparts-variants-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The products displayed on the Services can be ordered and delivered only within the U.S. and certain select countries.
  entity_types:
  - text: You may use the Services only if you have reached the age of majority where you live and can form a binding contract with us under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you have reached the age of majority where you live
    value: age of majority
  restricted_uses:
  - summary: Export and sanctions limits
    text: will not access or use the Services from a country or region that is targeted for comprehensive trade sanctions by the United States government
  - summary: Weapons end uses
    text: will not use the Services for military, nuclear, missile, chemical, or biological weaponry end uses in violation of United States export laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of our order processing procedures, we screen all received orders for fraud or other types of unauthorized or illegal activity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FinditParts
provenance_date: '2026-11-09'
provider_name: FinditParts
provider_slug: finditparts
slug: finditparts-eligibility
source_date: '2026-11-09'
source_filename: finditparts-eligibility.yml
source_heading: Eligibility
source_page: https://www.finditparts.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FinditParts\naid: finditparts\nurl: https://www.finditparts.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The products displayed on the Services can be ordered and delivered only within the U.S. and certain select\n    countries.\nentity_types:\n- type: individual\n  text: You may use the Services only if you have reached the age of majority where you live and can form a binding\n    contract with us under applicable law.\nrestricted_uses:\n- summary: Export and sanctions limits\n  text: will not access or use the Services from a country or region that is\
  \ targeted for comprehensive trade sanctions\n    by the United States government\n- summary: Weapons end uses\n  text: will not use the Services for military, nuclear, missile, chemical, or biological weaponry end uses in violation\n    of United States export laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of our order processing procedures, we screen all received orders for fraud or other types of unauthorized\n    or illegal activity.\nminimum_age:\n  value: age of majority\n  text: You may use the Services only if you have reached the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/finditparts/eligibility/finditparts-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from FinditParts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Automotive
- Parts
- Heavy Duty Trucking
- Fleet Management
- Logistics
- Commerce
- Catalog
- Order
- Shipping
---

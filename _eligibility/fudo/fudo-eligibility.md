---
api_specs:
- filename: fudo-customers-api-openapi.yml
  format: yaml
  label: Fudo Customers API
  slug: fudo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-customers-api-openapi.yml
- filename: fudo-discounts-api-openapi.yml
  format: yaml
  label: Fudo Discounts API
  slug: fudo-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-discounts-api-openapi.yml
- filename: fudo-expense-categories-api-openapi.yml
  format: yaml
  label: Fudo Expense Categories API
  slug: fudo-expense-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-expense-categories-api-openapi.yml
- filename: fudo-expenses-api-openapi.yml
  format: yaml
  label: Fudo Expenses API
  slug: fudo-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-expenses-api-openapi.yml
- filename: fudo-ingredients-api-openapi.yml
  format: yaml
  label: Fudo Ingredients API
  slug: fudo-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-ingredients-api-openapi.yml
- filename: fudo-items-api-openapi.yml
  format: yaml
  label: Fudo Items API
  slug: fudo-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-items-api-openapi.yml
- filename: fudo-kitchens-api-openapi.yml
  format: yaml
  label: Fudo Kitchens API
  slug: fudo-kitchens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-kitchens-api-openapi.yml
- filename: fudo-payment-methods-api-openapi.yml
  format: yaml
  label: Fudo Payment Methods API
  slug: fudo-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-payment-methods-api-openapi.yml
- filename: fudo-payments-api-openapi.yml
  format: yaml
  label: Fudo Payments API
  slug: fudo-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-payments-api-openapi.yml
- filename: fudo-product-categories-api-openapi.yml
  format: yaml
  label: Fudo Product Categories API
  slug: fudo-product-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-product-categories-api-openapi.yml
- filename: fudo-product-modifiers-api-openapi.yml
  format: yaml
  label: Fudo Product Modifiers API
  slug: fudo-product-modifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-product-modifiers-api-openapi.yml
- filename: fudo-products-api-openapi.yml
  format: yaml
  label: Fudo Products API
  slug: fudo-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-products-api-openapi.yml
- filename: fudo-providers-api-openapi.yml
  format: yaml
  label: Fudo Providers API
  slug: fudo-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-providers-api-openapi.yml
- filename: fudo-roles-api-openapi.yml
  format: yaml
  label: Fudo Roles API
  slug: fudo-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-roles-api-openapi.yml
- filename: fudo-rooms-api-openapi.yml
  format: yaml
  label: Fudo Rooms API
  slug: fudo-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-rooms-api-openapi.yml
- filename: fudo-sales-api-openapi.yml
  format: yaml
  label: Fudo Sales API
  slug: fudo-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-sales-api-openapi.yml
- filename: fudo-subitems-api-openapi.yml
  format: yaml
  label: Fudo Subitems API
  slug: fudo-subitems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-subitems-api-openapi.yml
- filename: fudo-tables-api-openapi.yml
  format: yaml
  label: Fudo Tables API
  slug: fudo-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-tables-api-openapi.yml
- filename: fudo-users-api-openapi.yml
  format: yaml
  label: Fudo Users API
  slug: fudo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fudo/openapi/fudo-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: El Sitio y/o los Servicios están dirigidos y se encuentran a disposición de cualquier persona que desee utilizarlos.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted products
    text: no podrá utilizar los Servicios, Plataforma ni los servicios independientes de entrega por parte de los terceros aliados o socios de FUDO, para coordinar la venta y/o entrega de los siguientes Productos Restringidos
  - summary: Illegal menu items
    text: debiendo abstenerse de publicar en su menú online productos o servicios ilegales o contrarios a la moral y buenas costumbres
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
name: Fudo
provenance_date: '2026-11-09'
provider_name: Fudo
provider_slug: fudo
slug: fudo-eligibility
source_date: '2026-11-09'
source_filename: fudo-eligibility.yml
source_heading: Eligibility
source_page: https://fu.do/es/condiciones-de-servicio/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fudo\naid: fudo\nurl: https://fu.do/es/condiciones-de-servicio/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: El Sitio y/o los Servicios están dirigidos y se encuentran a disposición de cualquier persona que desee\n    utilizarlos.\nrestricted_uses:\n- summary: Restricted products\n  text: no podrá utilizar los Servicios, Plataforma ni los servicios independientes de entrega por parte de los\n    terceros aliados o socios de FUDO, para coordinar la venta y/o entrega de los siguientes Productos Restringidos\n- summary: Illegal menu\
  \ items\n  text: debiendo abstenerse de publicar en su menú online productos o servicios ilegales o contrarios a la moral\n    y buenas costumbres\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fudo/eligibility/fudo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Fudo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Point-of-Sale
- Hospitality
- Food and Beverage
- Payments
- Inventory
- Latin America
- Software-as-a-Service
---

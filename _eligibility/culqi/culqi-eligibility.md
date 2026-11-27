---
api_specs:
- filename: culqi-cards-api-openapi.yml
  format: yaml
  label: Culqi Cards API
  slug: culqi-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-cards-api-openapi.yml
- filename: culqi-charges-api-openapi.yml
  format: yaml
  label: Culqi Charges API
  slug: culqi-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-charges-api-openapi.yml
- filename: culqi-customers-api-openapi.yml
  format: yaml
  label: Culqi Customers API
  slug: culqi-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-customers-api-openapi.yml
- filename: culqi-events-api-openapi.yml
  format: yaml
  label: Culqi Events API
  slug: culqi-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-events-api-openapi.yml
- filename: culqi-iins-api-openapi.yml
  format: yaml
  label: Culqi Iins API
  slug: culqi-iins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-iins-api-openapi.yml
- filename: culqi-orders-api-openapi.yml
  format: yaml
  label: Culqi Orders API
  slug: culqi-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-orders-api-openapi.yml
- filename: culqi-plans-api-openapi.yml
  format: yaml
  label: Culqi Plans API
  slug: culqi-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-plans-api-openapi.yml
- filename: culqi-refunds-api-openapi.yml
  format: yaml
  label: Culqi Refunds API
  slug: culqi-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-refunds-api-openapi.yml
- filename: culqi-subscriptions-api-openapi.yml
  format: yaml
  label: Culqi Subscriptions API
  slug: culqi-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-subscriptions-api-openapi.yml
- filename: culqi-tokens-api-openapi.yml
  format: yaml
  label: Culqi Tokens API
  slug: culqi-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-tokens-api-openapi.yml
- filename: culqi-transfers-api-openapi.yml
  format: yaml
  label: Culqi Transfers API
  slug: culqi-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-transfers-api-openapi.yml
- filename: culqi-3-ds-api-openapi.yml
  format: yaml
  label: Culqi 3 DS API
  slug: culqi-3-ds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-3-ds-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Válido a nivel nacional.
  entity_types:
  - text: Participan los clientes RUC20 y RUC10 con negocio
    type: business
  - text: participan las personas naturales, mayores de edad
    type: individual
  minimum_age:
    text: personas naturales, mayores de edad
    value: adult
  restricted_uses:
  - summary: No combination with Costo 0 benefit
    text: no puede ser aplicado junto al beneficio de Costo 0, POS Refurbished, uso de bolsa.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: El cliente deberá ser registrado por su vendedor (formulario online) a la campaña actual de Bono.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Culqi
provenance_date: '2026-11-09'
provider_name: Culqi
provider_slug: culqi
slug: culqi-eligibility
source_date: '2026-11-09'
source_filename: culqi-eligibility.yml
source_heading: Eligibility
source_page: https://culqi.com/terminos_y_condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Culqi\naid: culqi\nurl: https://culqi.com/terminos_y_condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Válido a nivel nacional.\nentity_types:\n- type: business\n  text: Participan los clientes RUC20 y RUC10 con negocio\n- type: individual\n  text: participan las personas naturales, mayores de edad\nrestricted_uses:\n- summary: No combination with Costo 0 benefit\n  text: no puede ser aplicado junto al beneficio de Costo 0, POS Refurbished, uso de bolsa.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: El cliente deberá ser\
  \ registrado por su vendedor (formulario online) a la campaña actual de Bono.\nminimum_age:\n  value: adult\n  text: personas naturales, mayores de edad\n"
source_yaml_url: https://artifacts.apis.io/culqi/eligibility/culqi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Culqi's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- Peru
- Latin America
- Cards
- Yape
---

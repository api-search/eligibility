---
api_specs:
- filename: 99-minutos-coverage-api-openapi.yml
  format: yaml
  label: 99 Minutos Coverage API
  slug: 99-minutos-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-coverage-api-openapi.yml
- filename: 99-minutos-documents-api-openapi.yml
  format: yaml
  label: 99 Minutos Documents API
  slug: 99-minutos-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-documents-api-openapi.yml
- filename: 99-minutos-locations-api-openapi.yml
  format: yaml
  label: 99 Minutos Locations API
  slug: 99-minutos-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-locations-api-openapi.yml
- filename: 99-minutos-orders-api-openapi.yml
  format: yaml
  label: 99 Minutos Orders API
  slug: 99-minutos-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-orders-api-openapi.yml
- filename: 99-minutos-shipments-api-openapi.yml
  format: yaml
  label: 99 Minutos Shipments API
  slug: 99-minutos-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-shipments-api-openapi.yml
- filename: 99-minutos-shipping-rates-api-openapi.yml
  format: yaml
  label: 99 Minutos Shipping Rates API
  slug: 99-minutos-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-shipping-rates-api-openapi.yml
- filename: 99-minutos-super-geocoding-api-openapi.yml
  format: yaml
  label: 99 Minutos Super Geocoding API
  slug: 99-minutos-super-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-super-geocoding-api-openapi.yml
- filename: 99-minutos-webhooks-api-openapi.yml
  format: yaml
  label: 99 Minutos Webhooks API
  slug: 99-minutos-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-webhooks-api-openapi.yml
- filename: 99-minutos-oauth-api-openapi.yml
  format: yaml
  label: 99 Minutos OAUTH API
  slug: 99-minutos-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-minutos/openapi/99-minutos-oauth-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: nacional en los Estados Unidos Mexicanos
  entity_types:
  - text: Persona física o moral titular de una Cuenta de Usuario en la Plataforma
    type: individual
  - text: Persona física o moral que contrata a través de la Plataforma los servicios
    type: business
  minimum_age:
    text: Para utilizar la Plataforma, debe ser mayor de 18 años de edad, lo que usted declara personalmente en este acto.
    value: '18'
  restricted_uses:
  - summary: Package size and weight limits
    text: excedan los 20 kilogramos
  - summary: Prohibited goods
    text: No se transportará ninguna Mercancía prohibida por cualquier regulación o ley aplicable local, estatal o federal
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
name: 99 Minutos
provenance_date: '2026-11-09'
provider_name: 99 Minutos
provider_slug: 99-minutos
slug: 99-minutos-eligibility
source_date: '2026-11-09'
source_filename: 99-minutos-eligibility.yml
source_heading: Eligibility
source_page: https://www.99minutos.com/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 99 Minutos\naid: 99-minutos\nurl: https://www.99minutos.com/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: nacional en los Estados Unidos Mexicanos\nentity_types:\n- type: individual\n  text: Persona física o moral titular de una Cuenta de Usuario en la Plataforma\n- type: business\n  text: Persona física o moral que contrata a través de la Plataforma los servicios\nrestricted_uses:\n- summary: Package size and weight limits\n  text: excedan los 20 kilogramos\n- summary: Prohibited goods\n  text: No se transportará ninguna Mercancía prohibida por cualquier\
  \ regulación o ley aplicable local, estatal o\n    federal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Para utilizar la Plataforma, debe ser mayor de 18 años de edad, lo que usted declara personalmente en este\n    acto.\n"
source_yaml_url: https://artifacts.apis.io/99-minutos/eligibility/99-minutos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from 99 Minutos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Last Mile Delivery
- Shipping
- E-Commerce
- Fulfillment
- Freight
- Tracking
- Webhook
- Latin America
- Mexico
---

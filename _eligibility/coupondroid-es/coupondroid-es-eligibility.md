---
api_specs:
- filename: coupondroid-es-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid España A2a API
  slug: coupondroid-es-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-es/openapi/coupondroid-es-a2a-api-openapi.yml
- filename: coupondroid-es-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid España Auth.md API
  slug: coupondroid-es-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-es/openapi/coupondroid-es-auth-md-api-openapi.yml
- filename: coupondroid-es-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid España Llms.txt API
  slug: coupondroid-es-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-es/openapi/coupondroid-es-llms-txt-api-openapi.yml
- filename: coupondroid-es-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid España MCP API
  slug: coupondroid-es-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-es/openapi/coupondroid-es-mcp-api-openapi.yml
- filename: coupondroid-es-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid España .well Known API
  slug: coupondroid-es-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-es/openapi/coupondroid-es-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - ES
    text: En compras a distancia dentro de España, el texto refundido de la Ley General para la Defensa de los Consumidores y Usuarios
  entity_types:
  - text: Si eres consumidor, cualquier conflicto podrá plantearse ante los juzgados y tribunales que correspondan
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Bulk or automated extraction
    text: Extraer de forma masiva o automatizada nuestro contenido o nuestras bases de datos, ni reproducirlas en otro servicio.
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
name: Coupondroid España
provenance_date: '2026-11-09'
provider_name: Coupondroid España
provider_slug: coupondroid-es
slug: coupondroid-es-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-es-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.es/corp/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid España\naid: coupondroid-es\nurl: https://coupondroid.es/corp/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ES\n  excluded: []\n  text: En compras a distancia dentro de España, el texto refundido de la Ley General para la Defensa de los Consumidores\n    y Usuarios\nentity_types:\n- type: individual\n  text: Si eres consumidor, cualquier conflicto podrá plantearse ante los juzgados y tribunales que correspondan\nrestricted_uses:\n- summary: Bulk or automated extraction\n  text: Extraer de forma masiva o automatizada nuestro contenido o nuestras bases de datos, ni reproducirlas\
  \ en\n    otro servicio.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-es/eligibility/coupondroid-es-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Coupondroid España's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Deals
- Discounts
- E-Commerce
- Shopping
- Spain
- MCP
---

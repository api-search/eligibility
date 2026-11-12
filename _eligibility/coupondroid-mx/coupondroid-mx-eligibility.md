---
api_specs:
- filename: coupondroid-mx-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid México A2a API
  slug: coupondroid-mx-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-mx/openapi/coupondroid-mx-a2a-api-openapi.yml
- filename: coupondroid-mx-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid México Auth.md API
  slug: coupondroid-mx-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-mx/openapi/coupondroid-mx-auth-md-api-openapi.yml
- filename: coupondroid-mx-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid México Llms.txt API
  slug: coupondroid-mx-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-mx/openapi/coupondroid-mx-llms-txt-api-openapi.yml
- filename: coupondroid-mx-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid México MCP API
  slug: coupondroid-mx-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-mx/openapi/coupondroid-mx-mcp-api-openapi.yml
- filename: coupondroid-mx-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid México .well Known API
  slug: coupondroid-mx-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-mx/openapi/coupondroid-mx-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: reunimos, verificamos y publicamos cupones, códigos de descuento y ofertas de tiendas que venden en línea en México y en el extranjero.
  entity_types:
  - text: Si eres consumidor, conservas el derecho a acudir a Profeco y a los tribunales que te correspondan; estos Términos no lo limitan.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Coupondroid México
provenance_date: '2026-11-09'
provider_name: Coupondroid México
provider_slug: coupondroid-mx
slug: coupondroid-mx-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-mx-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.mx/corp/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid México\naid: coupondroid-mx\nurl: https://coupondroid.mx/corp/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: reunimos, verificamos y publicamos cupones, códigos de descuento y ofertas de tiendas que venden en línea\n    en México y en el extranjero.\nentity_types:\n- type: individual\n  text: Si eres consumidor, conservas el derecho a acudir a Profeco y a los tribunales que te correspondan; estos\n    Términos no lo limitan.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-mx/eligibility/coupondroid-mx-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Coupondroid México's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Discounts
- Deals
- E-Commerce
- Mexico
- Affiliate Marketing
- MCP
---

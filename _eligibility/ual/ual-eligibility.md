---
api_specs:
- filename: ual-authentication-api-openapi.yml
  format: yaml
  label: Ualá Authentication API
  slug: ual-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ual/openapi/ual-authentication-api-openapi.yml
- filename: ual-orders-api-openapi.yml
  format: yaml
  label: Ualá Orders API
  slug: ual-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ual/openapi/ual-orders-api-openapi.yml
- filename: ual-refunds-api-openapi.yml
  format: yaml
  label: Ualá Refunds API
  slug: ual-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ual/openapi/ual-refunds-api-openapi.yml
- filename: ual-ual-bis-api-cobros-online-v2-api-openapi.yml
  format: yaml
  label: Ualá Bis API Cobros Online V2 API
  slug: ual-ual-bis-api-cobros-online-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ual/openapi/ual-ual-bis-api-cobros-online-v2-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Personas
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: One basic account per holder
    text: Los titulares de las cuentas CGU no pueden disponer de ningún otro tipo de cuenta vista en la misma entidad ni en otra del sistema financiero.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: El único requisito para la apertura es la presentación del DNI.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ualá
provenance_date: '2026-11-10'
provider_name: Ualá
provider_slug: ual
slug: ual-eligibility
source_date: '2026-11-10'
source_filename: ual-eligibility.yml
source_heading: Eligibility
source_page: https://www.uala.com.ar/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ualá\naid: ual\nurl: https://www.uala.com.ar/cgu\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Personas\nrestricted_uses:\n- summary: One basic account per holder\n  text: Los titulares de las cuentas CGU no pueden disponer de ningún otro tipo de cuenta vista en la misma entidad\n    ni en otra del sistema financiero.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: El único requisito para la apertura es la presentación del DNI.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ual/eligibility/ual-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Ualá's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Banking
- Neobank
- Checkout
- E-Commerce
- Argentina
- Mexico
---

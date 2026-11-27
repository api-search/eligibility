---
api_specs:
- filename: platzi-auth-api-openapi.yml
  format: yaml
  label: Platzi Auth API
  slug: platzi-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-auth-api-openapi.yml
- filename: platzi-categories-api-openapi.yml
  format: yaml
  label: Platzi Categories API
  slug: platzi-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-categories-api-openapi.yml
- filename: platzi-files-api-openapi.yml
  format: yaml
  label: Platzi Files API
  slug: platzi-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-files-api-openapi.yml
- filename: platzi-locations-api-openapi.yml
  format: yaml
  label: Platzi Locations API
  slug: platzi-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-locations-api-openapi.yml
- filename: platzi-products-api-openapi.yml
  format: yaml
  label: Platzi Products API
  slug: platzi-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-products-api-openapi.yml
- filename: platzi-users-api-openapi.yml
  format: yaml
  label: Platzi Users API
  slug: platzi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platzi/openapi/platzi-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Debe tener al menos 18 años de edad para aceptar estos Términos de Servicio, quedando entendido, sin embargo, que si fuera menor de 18 años, su padre o tutor legal puede aceptarlos en su nombre.
    type: individual
  - text: Si utiliza o abre una cuenta en el Servicio en nombre de una empresa, entidad u organización (colectivamente "Organización Suscriptora"), entonces usted declara y garantiza que es un representante autorizado de dicha Organización Suscriptora
    type: business
  minimum_age:
    text: Debe tener al menos 18 años de edad para aceptar estos Términos de Servicio
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: Usted acepta que este permiso es para su uso personal, no comercial y que nadie más que usted va a utilizar el Servicio.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Para utilizar el Servicio, deberá registrarse y abrir una Cuenta de Platzi.com.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Platzi
provenance_date: '2026-11-10'
provider_name: Platzi
provider_slug: platzi
slug: platzi-eligibility
source_date: '2026-11-10'
source_filename: platzi-eligibility.yml
source_heading: Eligibility
source_page: https://platzi.com/terminos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Platzi\naid: platzi\nurl: https://platzi.com/terminos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Debe tener al menos 18 años de edad para aceptar estos Términos de Servicio, quedando entendido, sin embargo,\n    que si fuera menor de 18 años, su padre o tutor legal puede aceptarlos en su nombre.\n- type: business\n  text: Si utiliza o abre una cuenta en el Servicio en nombre de una empresa, entidad u organización (colectivamente\n    \"Organización Suscriptora\"), entonces usted declara y garantiza que es un representante autorizado\
  \ de dicha\n    Organización Suscriptora\nrestricted_uses:\n- summary: No commercial use\n  text: Usted acepta que este permiso es para su uso personal, no comercial y que nadie más que usted va a utilizar\n    el Servicio.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Para utilizar el Servicio, deberá registrarse y abrir una Cuenta de Platzi.com.\nminimum_age:\n  value: '18'\n  text: Debe tener al menos 18 años de edad para aceptar estos Términos de Servicio\n"
source_yaml_url: https://artifacts.apis.io/platzi/eligibility/platzi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Platzi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- E-Commerce
- Product
- Mock API
- Prototyping
- REST
- GraphQL
- Fake Store
- Developer Tools
---

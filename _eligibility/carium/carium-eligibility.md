---
api_specs:
- filename: carium-caredb-api-openapi.yml
  format: yaml
  label: Carium Caredb API
  slug: carium-caredb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-caredb-api-openapi.yml
- filename: carium-carium-api-api-openapi.yml
  format: yaml
  label: Carium Carium API
  slug: carium-carium-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-carium-api-api-openapi.yml
- filename: carium-carium-inc-api-openapi.yml
  format: yaml
  label: Carium Carium Inc API
  slug: carium-carium-inc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-carium-inc-api-openapi.yml
- filename: carium-identity-api-openapi.yml
  format: yaml
  label: Carium Identity API
  slug: carium-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-identity-api-openapi.yml
- filename: carium-lachesis-api-openapi.yml
  format: yaml
  label: Carium Lachesis API
  slug: carium-lachesis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-lachesis-api-openapi.yml
- filename: carium-overlord-api-openapi.yml
  format: yaml
  label: Carium Overlord API
  slug: carium-overlord-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-overlord-api-openapi.yml
- filename: carium-showboat-api-openapi.yml
  format: yaml
  label: Carium Showboat API
  slug: carium-showboat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carium/openapi/carium-showboat-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'NO PUEDE UTILIZAR EL SERVICIO SI: (A) NO PUEDE CELEBRAR UN CONTRATO VINCULANTE CON LA EMPRESA; (B) NO TIENE PERMITIDO RECIBIR PRODUCTOS, LO QUE INCLUYE SERVICIOS O SOFTWARE DE LOS ESTADOS UNIDOS'
  entity_types:
  - text: 'Usted declara que: 1. Tiene al menos 18 años; 2. es un menor emancipado; 3. posee el consentimiento de su padre, madre o tutor legal'
    type: individual
  minimum_age:
    text: EL SERVICIO ESTÁ DISEÑADO PARA SU USO POR PARTE DE PERSONAS MAYORES DE 18 AÑOS.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Hacer cualquier uso comercial del Servicio
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Para crear una Cuenta, debe proporcionar la información que se solicite durante el proceso de registro
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carium
provenance_date: '2026-11-09'
provider_name: Carium
provider_slug: carium
slug: carium-eligibility
source_date: '2026-11-09'
source_filename: carium-eligibility.yml
source_heading: Eligibility
source_page: https://www.go.carium.com/terms-of-use-spanish
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carium\naid: carium\nurl: https://www.go.carium.com/terms-of-use-spanish\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'NO PUEDE UTILIZAR EL SERVICIO SI: (A) NO PUEDE CELEBRAR UN CONTRATO VINCULANTE CON LA EMPRESA; (B) NO TIENE\n    PERMITIDO RECIBIR PRODUCTOS, LO QUE INCLUYE SERVICIOS O SOFTWARE DE LOS ESTADOS UNIDOS'\nentity_types:\n- type: individual\n  text: 'Usted declara que: 1. Tiene al menos 18 años; 2. es un menor emancipado; 3. posee el consentimiento de\n    su padre, madre o tutor legal'\nrestricted_uses:\n- summary: Commercial use\n  text: Hacer cualquier uso comercial\
  \ del Servicio\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Para crear una Cuenta, debe proporcionar la información que se solicite durante el proceso de registro\nminimum_age:\n  value: '18'\n  text: EL SERVICIO ESTÁ DISEÑADO PARA SU USO POR PARTE DE PERSONAS MAYORES DE 18 AÑOS.\n"
source_yaml_url: https://artifacts.apis.io/carium/eligibility/carium-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Carium's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Virtual Care
- Remote Monitoring
- Patient Engagement
- Health Tech
- Company
---

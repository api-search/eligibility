---
api_specs:
- filename: cincel-openapi-generated.yml
  format: yaml
  label: CINCEL API
  slug: cincel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cincel/openapi/_ae-authored/cincel-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Cliente: la persona física o moral, que por su cuenta contrata con el Proveedor algún Plan que se ofrece en Cincel'
    type: business
  minimum_age:
    text: declara bajo protesta de decir verdad, ser mayor de edad
    value: null
  restricted_uses:
  - summary: Background-check data requires written consent
    text: DEBERÁ OBTENER, PREVIAMENTE Y EN TODOS LOS CASOS, EL CONSENTIMIENTO EXPRESO Y POR ESCRITO DE LOS TITULARES DE LOS DATOS
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
name: CINCEL
provenance_date: '2026-11-09'
provider_name: CINCEL
provider_slug: cincel
slug: cincel-eligibility
source_date: '2026-11-09'
source_filename: cincel-eligibility.yml
source_heading: Eligibility
source_page: https://www.cincel.digital/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CINCEL\naid: cincel\nurl: https://www.cincel.digital/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Cliente: la persona física o moral, que por su cuenta contrata con el Proveedor algún Plan que se ofrece\n    en Cincel'\nrestricted_uses:\n- summary: Background-check data requires written consent\n  text: DEBERÁ OBTENER, PREVIAMENTE Y EN TODOS LOS CASOS, EL CONSENTIMIENTO EXPRESO Y POR ESCRITO DE LOS TITULARES\n    DE LOS DATOS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: declara bajo protesta de decir verdad, ser mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/cincel/eligibility/cincel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CINCEL's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Signature
- Software-as-a-Service
- Latin America
- Compliance
---

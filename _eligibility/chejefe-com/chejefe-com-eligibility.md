---
api_specs:
- filename: chejefe-com-guides-api-openapi.yml
  format: yaml
  label: Jefe Guides API
  slug: chejefe-com-guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chejefe-com/openapi/chejefe-com-guides-api-openapi.yml
- filename: chejefe-com-nlweb-api-openapi.yml
  format: yaml
  label: Jefe NL Web API
  slug: chejefe-com-nlweb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chejefe-com/openapi/chejefe-com-nlweb-api-openapi.yml
- filename: chejefe-com-product-api-openapi.yml
  format: yaml
  label: Jefe Product API
  slug: chejefe-com-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chejefe-com/openapi/chejefe-com-product-api-openapi.yml
- filename: chejefe-com-resources-api-openapi.yml
  format: yaml
  label: Jefe Resources API
  slug: chejefe-com-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chejefe-com/openapi/chejefe-com-resources-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Para operar con Jefe el restaurante debe entregar información veraz y actualizada sobre su identidad y su negocio
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted product sales
    text: No usar la plataforma para contenido ilegal, engañoso, discriminatorio, ni para productos cuya venta esté restringida sin la habilitación correspondiente.
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
name: Jefe
provenance_date: '2026-11-09'
provider_name: Jefe
provider_slug: chejefe-com
slug: chejefe-com-eligibility
source_date: '2026-11-09'
source_filename: chejefe-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.chejefe.com/terminos-de-uso
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jefe\naid: chejefe-com\nurl: https://www.chejefe.com/terminos-de-uso\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Para operar con Jefe el restaurante debe entregar información veraz y actualizada sobre su identidad y su\n    negocio\nrestricted_uses:\n- summary: Restricted product sales\n  text: No usar la plataforma para contenido ilegal, engañoso, discriminatorio, ni para productos cuya venta esté\n    restringida sin la habilitación correspondiente.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chejefe-com/eligibility/chejefe-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Jefe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- WhatsApp
- Food Ordering
- Artificial Intelligence
- Online Store
- Latin America
- MCP
---

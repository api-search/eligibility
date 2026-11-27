---
api_specs:
- filename: novicap-confirming-standard-api-openapi.yml
  format: yaml
  label: Novicap Confirming Standard API
  slug: novicap-confirming-standard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novicap/openapi/novicap-confirming-standard-api-openapi.yml
- filename: novicap-dynamic-discounting-api-openapi.yml
  format: yaml
  label: Novicap Dynamic Discounting API
  slug: novicap-dynamic-discounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novicap/openapi/novicap-dynamic-discounting-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Los servicios de financiación y gestión ofrecidos a través de las plataformas Novicap y Novicap Go están dirigidos exclusivamente a personas jurídicas y profesionales que actúen en el marco de su actividad empresarial.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No consumer use of financing services
    text: En ningún caso estos servicios están destinados a consumidores finales.
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
name: Novicap
provenance_date: '2026-11-10'
provider_name: Novicap
provider_slug: novicap
slug: novicap-eligibility
source_date: '2026-11-10'
source_filename: novicap-eligibility.yml
source_heading: Eligibility
source_page: https://novicap.com/aviso-legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Novicap\naid: novicap\nurl: https://novicap.com/aviso-legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Los servicios de financiación y gestión ofrecidos a través de las plataformas Novicap y Novicap Go están\n    dirigidos exclusivamente a personas jurídicas y profesionales que actúen en el marco de su actividad empresarial.\nrestricted_uses:\n- summary: No consumer use of financing services\n  text: En ningún caso estos servicios están destinados a consumidores finales.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/novicap/eligibility/novicap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Novicap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Working Capital
- Invoice Finance
- Supply Chain Finance
- Dynamic Discounting
- Confirming
- Reverse Factoring
- Spain
---

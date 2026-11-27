---
api_specs:
- filename: waspytech-com-openapi-generated.yml
  format: yaml
  label: waspytech-com API
  slug: waspytech-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waspytech-com/openapi/_ae-authored/waspytech-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Si utilizás el Servicio en nombre de una empresa u otra entidad legal, declarás que tenés la autoridad para vincular a dicha entidad a estos Términos.
    type: business
  minimum_age:
    text: Sos mayor de edad según la legislación del país donde residís, o contás con el consentimiento expreso de tu tutor legal para utilizar el Servicio.
    value: age of majority or parental consent
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
name: waspytech-com
provenance_date: '2026-11-10'
provider_name: waspytech-com
provider_slug: waspytech-com
slug: waspytech-com-eligibility
source_date: '2026-11-10'
source_filename: waspytech-com-eligibility.yml
source_heading: Eligibility
source_page: https://waspytech.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: waspytech-com\naid: waspytech-com\nurl: https://waspytech.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Si utilizás el Servicio en nombre de una empresa u otra entidad legal, declarás que tenés la autoridad para\n    vincular a dicha entidad a estos Términos.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority or parental consent\n  text: Sos mayor de edad según la legislación del país donde residís, o contás con el consentimiento expreso\
  \ de\n    tu tutor legal para utilizar el Servicio.\n"
source_yaml_url: https://artifacts.apis.io/waspytech-com/eligibility/waspytech-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from waspytech-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- WhatsApp
- Messaging
- Software-as-a-Service
---

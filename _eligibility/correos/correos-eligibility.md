---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale of services or APIs
    text: El uso del portal para reventa de servicios o APIs, sin el consentimiento previo y por escrito de Correos, está estrictamente prohibido.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Esto puede incluir la confirmación de la dirección de correo electrónico y/o un proceso de verificación de identidad.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Correos
provenance_date: '2026-11-09'
provider_name: Correos
provider_slug: correos
slug: correos-eligibility
source_date: '2026-11-09'
source_filename: correos-eligibility.yml
source_heading: Eligibility
source_page: https://developers.correos.es/s/terminos-y-condiciones?language=es
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Correos\naid: correos\nurl: https://developers.correos.es/s/terminos-y-condiciones?language=es\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Resale of services or APIs\n  text: El uso del portal para reventa de servicios o APIs, sin el consentimiento previo y por escrito de Correos,\n    está estrictamente prohibido.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Esto puede incluir la confirmación de la dirección de correo electrónico y/o un proceso de verificación\n    de identidad.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/correos/eligibility/correos-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Correos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Postal
- Logistics
- Spain
---

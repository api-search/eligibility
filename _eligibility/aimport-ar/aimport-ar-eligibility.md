---
claim_count: 3
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
  - summary: Personal, non-transferable credentials
    text: Son personales e intransferibles.
  - summary: No presenting inferences as official facts
    text: Presentar nuestras inferencias como si fueran hechos oficiales, o atribuirle a ARCA un número que calculamos nosotros.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: 'Mientras el servicio está en beta , el alta es inmediata : completás tus datos, aceptás estos términos y entrás.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AImport
provenance_date: '2026-11-09'
provider_name: AImport
provider_slug: aimport-ar
slug: aimport-ar-eligibility
source_date: '2026-11-09'
source_filename: aimport-ar-eligibility.yml
source_heading: Eligibility
source_page: https://aimport.ar/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AImport\naid: aimport-ar\nurl: https://aimport.ar/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal, non-transferable credentials\n  text: Son personales e intransferibles.\n- summary: No presenting inferences as official facts\n  text: Presentar nuestras inferencias como si fueran hechos oficiales, o atribuirle a ARCA un número que calculamos\n    nosotros.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: 'Mientras el servicio está en beta , el alta es inmediata : completás tus datos,\
  \ aceptás estos términos\n    y entrás.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aimport-ar/eligibility/aimport-ar-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from AImport's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Import
- Argentina
- Artificial Intelligence
- Analytics
---

---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Las credenciales son personales.
    type: individual
  - text: Las instituciones administran sus usuarios y estaciones autorizadas.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional review of results
    text: El usuario es responsable de revisar los resultados antes de emplearlos en fabricación, construcción, publicaciones, decisiones de ingeniería, seguridad, cumplimiento regulatorio o decisiones de negocio.
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
name: axenomia-cl
provenance_date: '2026-11-09'
provider_name: axenomia-cl
provider_slug: axenomia-cl
slug: axenomia-cl-eligibility
source_date: '2026-11-09'
source_filename: axenomia-cl-eligibility.yml
source_heading: Eligibility
source_page: https://axenomia.cl/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: axenomia-cl\naid: axenomia-cl\nurl: https://axenomia.cl/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Las credenciales son personales.\n- type: business\n  text: Las instituciones administran sus usuarios y estaciones autorizadas.\nrestricted_uses:\n- summary: Professional review of results\n  text: El usuario es responsable de revisar los resultados antes de emplearlos en fabricación, construcción, publicaciones,\n    decisiones de ingeniería, seguridad, cumplimiento regulatorio o decisiones de negocio.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axenomia-cl/eligibility/axenomia-cl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from axenomia-cl's own page on 2026-11-09.
synthetic: false
tags:
- Company
---

---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bee Holding SAS es una empresa establecida en Uruguay con número de empresa (RUT) 21.833.415.001
  entity_types:
  - text: Debe ser una persona natural de al menos 18 años de edad para usar el Sitio y registrarse para los Servicios.
    type: individual
  - text: La plataforma Wortise beneficia al Editor (editores/propietarios/desarrolladores/proveedores de aplicaciones)
    type: business
  minimum_age:
    text: Debe ser una persona natural de al menos 18 años de edad para usar el Sitio y registrarse para los Servicios.
    value: '18'
  restricted_uses:
  - summary: Illegal or objectionable content
    text: El Editor acepta no crear contenido ilegal, difamatorio, amenazante u objetable en relación con Wortise.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: La participación en el Servicio de Wortise está sujeta a la aprobación previa de Wortise y al cumplimiento continuo del Editor con los TyC.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdsGPT
provenance_date: '2026-11-09'
provider_name: AdsGPT
provider_slug: adsgpt-dev
slug: adsgpt-dev-eligibility
source_date: '2026-11-09'
source_filename: adsgpt-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.adsgpt.dev/es/terminos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdsGPT\naid: adsgpt-dev\nurl: https://www.adsgpt.dev/es/terminos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Bee Holding SAS es una empresa establecida en Uruguay con número de empresa (RUT) 21.833.415.001\nentity_types:\n- type: individual\n  text: Debe ser una persona natural de al menos 18 años de edad para usar el Sitio y registrarse para los Servicios.\n- type: business\n  text: La plataforma Wortise beneficia al Editor (editores/propietarios/desarrolladores/proveedores de aplicaciones)\nrestricted_uses:\n- summary: Illegal or objectionable content\n  text: El Editor acepta\
  \ no crear contenido ilegal, difamatorio, amenazante u objetable en relación con Wortise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: La participación en el Servicio de Wortise está sujeta a la aprobación previa de Wortise y al cumplimiento\n    continuo del Editor con los TyC.\nminimum_age:\n  value: '18'\n  text: Debe ser una persona natural de al menos 18 años de edad para usar el Sitio y registrarse para los Servicios.\n"
source_yaml_url: https://artifacts.apis.io/adsgpt-dev/eligibility/adsgpt-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AdsGPT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Artificial Intelligence
- Marketing
- Automation
- Platform
---

---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Plataforma puede no estar disponible en el país donde el Usuario se encuentre; software sujeto a normas de exportación; no se permite a ciudadanos o residentes de países restringidos por el gobierno mexicano.
  entity_types:
  - text: Para hacer uso de esta Plataforma y de los Servicios, el Usuario debe ser mayor de edad
    type: individual
  minimum_age:
    text: bajo ninguna circunstancia se permite el acceso a menores de 14 años.
    value: '14'
  restricted_uses:
  - summary: No fraudulent or unlawful use
    text: cualquier uso de la Plataforma para fines distintos a los establecidos expresamente entre las partes, así como para realizar conductas contrarias a las leyes, la moral y las buenas costumbres está estrictamente prohibido.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: SPORTWEY puede verificar, por si o por terceros, en cualquier momento los datos de los Usuarios.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sportwey
provenance_date: '2026-11-10'
provider_name: Sportwey
provider_slug: sportwey
slug: sportwey-eligibility
source_date: '2026-11-10'
source_filename: sportwey-eligibility.yml
source_heading: Eligibility
source_page: https://sportwey.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sportwey\naid: sportwey\nurl: https://sportwey.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Plataforma puede no estar disponible en el país donde el Usuario se encuentre; software sujeto a normas\n    de exportación; no se permite a ciudadanos o residentes de países restringidos por el gobierno mexicano.\nentity_types:\n- type: individual\n  text: Para hacer uso de esta Plataforma y de los Servicios, el Usuario debe ser mayor de edad\nrestricted_uses:\n- summary: No fraudulent or unlawful use\n  text: cualquier uso de la Plataforma para fines distintos a los establecidos\
  \ expresamente entre las partes, así\n    como para realizar conductas contrarias a las leyes, la moral y las buenas costumbres está estrictamente prohibido.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: SPORTWEY puede verificar, por si o por terceros, en cualquier momento los datos de los Usuarios.\nminimum_age:\n  value: '14'\n  text: bajo ninguna circunstancia se permite el acceso a menores de 14 años.\n"
source_yaml_url: https://artifacts.apis.io/sportwey/eligibility/sportwey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sportwey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Tournaments
- League
- Sports Management
- Software-as-a-Service
- Facilities
- Academies
- Payments
- Mexico
---

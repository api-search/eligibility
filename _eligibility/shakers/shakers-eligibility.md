---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: por parte de cualquier persona física o jurídica
    type: individual
  - text: por parte de cualquier persona física o jurídica
    type: business
  minimum_age:
    text: el Usuario declara que es mayor de (18) años, o, en su defecto, que cuenta con la debida autorización de sus tutores legales.
    value: '18'
  restricted_uses:
  - summary: No intermediaries or recruiters on behalf of end clients
    text: Dichos servicios están reservados para Clientes y Talentos y no pueden ser utilizados por intermediarios o profesionales de reclutamiento que actúen en nombre de un cliente final.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: la solicitud de registro como Talento del Sitio Web será evaluada y validada por Shakers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shakers
provenance_date: '2026-11-10'
provider_name: Shakers
provider_slug: shakers
slug: shakers-eligibility
source_date: '2026-11-10'
source_filename: shakers-eligibility.yml
source_heading: Eligibility
source_page: https://www.shakersworks.com/condiciones-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shakers\naid: shakers\nurl: https://www.shakersworks.com/condiciones-generales\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: por parte de cualquier persona física o jurídica\n- type: business\n  text: por parte de cualquier persona física o jurídica\nrestricted_uses:\n- summary: No intermediaries or recruiters on behalf of end clients\n  text: Dichos servicios están reservados para Clientes y Talentos y no pueden ser utilizados por intermediarios\n    o profesionales de reclutamiento que actúen en nombre de un cliente final.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: la solicitud de registro como Talento del Sitio Web será evaluada y validada por Shakers.\nminimum_age:\n  value: '18'\n  text: el Usuario declara que es mayor de (18) años, o, en su defecto, que cuenta con la debida autorización de\n    sus tutores legales.\n"
source_yaml_url: https://artifacts.apis.io/shakers/eligibility/shakers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Shakers's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Freelance
- Talent
- Recruiting
- Future Of Work
- Artificial Intelligence
- Staffing
---

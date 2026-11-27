---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CL
    text: Estos Términos y Condiciones estarán regidos en todas sus partes por las leyes vigentes en la República de Chile.
  entity_types:
  - text: cualquier persona natural o jurídica que desee acceder y/o usar los productos y/o servicios
    type: individual
  - text: Los servicios y productos solo están disponibles para personas que tengan capacidad legal para contratar
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: Si el Usuario o alguno de sus accionistas, representantes, empleados, colaboradores, asesores, proveedores, personas relacionadas, o beneﬁciarios de alguna operación aparece en listas de sanciones o delitos
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
name: Xepelin
provenance_date: '2026-11-10'
provider_name: Xepelin
provider_slug: xepelin
slug: xepelin-eligibility
source_date: '2026-11-10'
source_filename: xepelin-eligibility.yml
source_heading: Eligibility
source_page: https://xepelin.cl/legal/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xepelin\naid: xepelin\nurl: https://xepelin.cl/legal/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CL\n  excluded: []\n  text: Estos Términos y Condiciones estarán regidos en todas sus partes por las leyes vigentes en la República\n    de Chile.\nentity_types:\n- type: individual\n  text: cualquier persona natural o jurídica que desee acceder y/o usar los productos y/o servicios\n- type: business\n  text: Los servicios y productos solo están disponibles para personas que tengan capacidad legal para contratar\nrestricted_uses:\n- summary: Sanctioned persons\n  text: Si el Usuario\
  \ o alguno de sus accionistas, representantes, empleados, colaboradores, asesores, proveedores,\n    personas relacionadas, o beneﬁciarios de alguna operación aparece en listas de sanciones o delitos\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xepelin/eligibility/xepelin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Xepelin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Factoring
- Invoice Financing
- Working Capital
- Payments
- Lending
- Small Business
- Latin America
- Financial Intelligence
---

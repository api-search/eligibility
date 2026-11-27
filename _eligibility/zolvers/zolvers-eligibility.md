---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AR
    - CL
    - CO
    - MX
    text: Capital Federal - Argentina ... Santiago de Chile - Chile Distrito Federal - México Monterrey - México Bogotá - Colombia
  entity_types:
  - text: Zolvers contacta a personas que desean ofrecer servicios
    type: individual
  minimum_age:
    text: el Usuario garantiza poseer la edad mínima necesaria (dieciocho – 18 – años) para utilizar los Servicios del Sitio.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: Sea falso o engañoso.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Zolvers tendrá el derecho de realizar la validación de documentación del postulante y rechazar su solicitud.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zolvers
provenance_date: '2026-11-10'
provider_name: Zolvers
provider_slug: zolvers
slug: zolvers-eligibility
source_date: '2026-11-10'
source_filename: zolvers-eligibility.yml
source_heading: Eligibility
source_page: https://zolvers.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zolvers\naid: zolvers\nurl: https://zolvers.com/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AR\n  - CL\n  - CO\n  - MX\n  excluded: []\n  text: Capital Federal - Argentina ... Santiago de Chile - Chile Distrito Federal - México Monterrey - México Bogotá\n    - Colombia\nentity_types:\n- type: individual\n  text: Zolvers contacta a personas que desean ofrecer servicios\nrestricted_uses:\n- summary: Prohibited content\n  text: Sea falso o engañoso.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Zolvers tendrá el derecho de realizar la validación de\
  \ documentación del postulante y rechazar su solicitud.\nminimum_age:\n  value: '18'\n  text: el Usuario garantiza poseer la edad mínima necesaria (dieciocho – 18 – años) para utilizar los Servicios\n    del Sitio.\n"
source_yaml_url: https://artifacts.apis.io/zolvers/eligibility/zolvers-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zolvers's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- Domestic Work
- Cleaning
- Latin America
- Gig Economy
- On-Demand
---

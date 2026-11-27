---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: exclusivamente a los usuarios que se encuentren en el territorio de los Estados Unidos Mexicanos ("México")
  entity_types:
  - text: Serán referidos como "Usuarios" todas las personas físicas que se registren
    type: individual
  minimum_age:
    text: Únicamente podrán solicitar la habilitación de una Cuenta de Usuario las personas que tengan mayoría de edad, es decir, dieciocho (18) años cumplidos
    value: '18'
  restricted_uses:
  - summary: Crypto transactions prohibited
    text: queda expresamente prohibido realizar, intentar realizar o facilitar transacciones relacionadas, directa o indirectamente, con criptomonedas, activos virtuales o instrumentos análogos
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
name: Nelo
provenance_date: '2026-11-10'
provider_name: Nelo
provider_slug: nelo
slug: nelo-eligibility
source_date: '2026-11-10'
source_filename: nelo-eligibility.yml
source_heading: Eligibility
source_page: https://www.nelo.mx/es/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nelo\naid: nelo\nurl: https://www.nelo.mx/es/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: exclusivamente a los usuarios que se encuentren en el territorio de los Estados Unidos Mexicanos (\"México\")\nentity_types:\n- type: individual\n  text: Serán referidos como \"Usuarios\" todas las personas físicas que se registren\nrestricted_uses:\n- summary: Crypto transactions prohibited\n  text: queda expresamente prohibido realizar, intentar realizar o facilitar transacciones relacionadas, directa\n    o indirectamente, con criptomonedas, activos virtuales o instrumentos\
  \ análogos\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Únicamente podrán solicitar la habilitación de una Cuenta de Usuario las personas que tengan mayoría de\n    edad, es decir, dieciocho (18) años cumplidos\n"
source_yaml_url: https://artifacts.apis.io/nelo/eligibility/nelo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nelo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Buy Now Pay Later
- Consumer Credit
- Payments
- Mexico
- Mobile App
---

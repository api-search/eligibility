---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Los menores de edad no pueden acceder a los Créditos aquí regulados.
    value: '18'
  restricted_uses:
  - summary: Lending to minors prohibited
    text: Los menores de edad no pueden acceder a los Créditos aquí regulados.
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
name: Morado
provenance_date: '2026-11-10'
provider_name: Morado
provider_slug: morado
slug: morado-eligibility
source_date: '2026-11-10'
source_filename: morado-eligibility.yml
source_heading: Eligibility
source_page: https://www.moradocolombia.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Morado\naid: morado\nurl: https://www.moradocolombia.com/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lending to minors prohibited\n  text: Los menores de edad no pueden acceder a los Créditos aquí regulados.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Los menores de edad no pueden acceder a los Créditos aquí regulados.\n"
source_yaml_url: https://artifacts.apis.io/morado/eligibility/morado-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Morado's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Fintech
- Beauty
- Wellness
- Lending
- Credit
- Colombia
- Latin America
- B2B
---

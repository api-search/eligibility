---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: LaHaus controla y opera la Plataforma y todas sus actividades desde Colombia
  entity_types:
  - text: Cualquier persona natural o jurídica que desee acceder a la Plataforma o a los Servicios
    type: individual
  minimum_age:
    text: Al acceder a la Plataforma el Usuario declara que es mayor de edad
    value: null
  restricted_uses:
  - summary: Minors and persons without legal capacity
    text: No podrán utilizar los Servicios las personas que no tengan esa capacidad y los menores de edad.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: El Usuario autoriza expresamente a LaHaus para que consulte, verifique y solicite información relevante
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: La Haus
provenance_date: '2026-11-09'
provider_name: La Haus
provider_slug: la-haus
slug: la-haus-eligibility
source_date: '2026-11-09'
source_filename: la-haus-eligibility.yml
source_heading: Eligibility
source_page: https://www.lahaus.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: La Haus\naid: la-haus\nurl: https://www.lahaus.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: LaHaus controla y opera la Plataforma y todas sus actividades desde Colombia\nentity_types:\n- type: individual\n  text: Cualquier persona natural o jurídica que desee acceder a la Plataforma o a los Servicios\nrestricted_uses:\n- summary: Minors and persons without legal capacity\n  text: No podrán utilizar los Servicios las personas que no tengan esa capacidad y los menores de edad.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ El Usuario autoriza expresamente a LaHaus para que consulte, verifique y solicite información relevante\nminimum_age:\n  value: null\n  text: Al acceder a la Plataforma el Usuario declara que es mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/la-haus/eligibility/la-haus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from La Haus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Marketplace
- Housing
- Mortgage
- Brokerage
- Latin America
- Colombia
- Mexico
---

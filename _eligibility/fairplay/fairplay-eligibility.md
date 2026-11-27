---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Esta Plataforma está controlada y operada por FAIRPLAY desde México
  entity_types:
  - text: las empresas de comercio electrónico pueden calificar para la contratación de nuestros servicios de analítica y/o servicios de inversión
    type: business
  - text: Ser una persona física con actividad empresarial
    type: individual
  minimum_age:
    text: debes de ser mayor de edad, en ninguna circunstancia, permitimos el acceso y/o utilización de la Plataforma a menores de 18 años.
    value: '18'
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
name: Fairplay
provenance_date: '2026-11-09'
provider_name: Fairplay
provider_slug: fairplay
slug: fairplay-eligibility
source_date: '2026-11-09'
source_filename: fairplay-eligibility.yml
source_heading: Eligibility
source_page: https://www.getfairplay.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fairplay\naid: fairplay\nurl: https://www.getfairplay.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Esta Plataforma está controlada y operada por FAIRPLAY desde México\nentity_types:\n- type: business\n  text: las empresas de comercio electrónico pueden calificar para la contratación de nuestros servicios de analítica\n    y/o servicios de inversión\n- type: individual\n  text: Ser una persona física con actividad empresarial\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: debes de ser mayor de edad, en ninguna circunstancia, permitimos el acceso y/o utilización de la Plataforma\n    a menores de 18 años.\n"
source_yaml_url: https://artifacts.apis.io/fairplay/eligibility/fairplay-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Fairplay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Embedded Finance
- Working Capital
- Revenue-Based Financing
- E-Commerce
- Fintech
- Mexico
---

---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AR
    text: En la República Argentina, y dentro de las zonas de cobertura habilitadas por COOPER, la Aplicación intermedia los servicios de paseo, guardería y entrenamiento canino
  entity_types:
  - text: Solo podrán registrarse como Usuarios personas físicas mayores de edad con capacidad legal para contratar
    type: individual
  - text: COOPER podrá celebrar acuerdos con empresas, entidades, obras sociales, asociaciones u organizaciones
    type: business
  minimum_age:
    text: El Usuario declara tener al menos 18 años, ser menor emancipado o contar con el consentimiento legal de sus padres o tutor
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent purposes
    text: No solicitará la Aplicación con fines ilícitos, ilegales, contrarios a lo establecido en los presentes Términos y Condiciones Generales
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
name: Cooper Pet Care
provenance_date: '2026-11-09'
provider_name: Cooper Pet Care
provider_slug: cooperpetcare-app
slug: cooperpetcare-app-eligibility
source_date: '2026-11-09'
source_filename: cooperpetcare-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.cooperpetcare.app/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cooper Pet Care\naid: cooperpetcare-app\nurl: https://www.cooperpetcare.app/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AR\n  excluded: []\n  text: En la República Argentina, y dentro de las zonas de cobertura habilitadas por COOPER, la Aplicación intermedia\n    los servicios de paseo, guardería y entrenamiento canino\nentity_types:\n- type: individual\n  text: Solo podrán registrarse como Usuarios personas físicas mayores de edad con capacidad legal para contratar\n- type: business\n  text: COOPER podrá celebrar acuerdos con empresas, entidades, obras sociales,\
  \ asociaciones u organizaciones\nrestricted_uses:\n- summary: Unlawful or fraudulent purposes\n  text: No solicitará la Aplicación con fines ilícitos, ilegales, contrarios a lo establecido en los presentes Términos\n    y Condiciones Generales\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: El Usuario declara tener al menos 18 años, ser menor emancipado o contar con el consentimiento legal de\n    sus padres o tutor\n"
source_yaml_url: https://artifacts.apis.io/cooperpetcare-app/eligibility/cooperpetcare-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cooper Pet Care's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pet Care
- Dog Walking
- Dog Boarding
- Dog Training
- Marketplace
- Mobile Apps
- Argentina
- Latin America
- MCP
---

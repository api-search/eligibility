---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AR
    text: Capacidad legal para contratar bajo las leyes de la República Argentina
  entity_types:
  - text: Todo Usuario del Sitio deberá ser mayor de edad, contar con la capacidad legal para contratar
    type: individual
  - text: Para el caso en que se registre una persona jurídica, la persona humana que realice la registración deberá tener facultades para contratar y obligar a dicha persona jurídica
    type: business
  minimum_age:
    text: Todo Usuario del Sitio deberá ser mayor de edad
    value: '18'
  restricted_uses:
  - summary: Prohibited or illegal content and conduct
    text: No ingresar o difundir contenidos contrarios al honor, a la intimidad o a la imagen o propaganda de carácter racista, xenófobo, pornográfico, o de apología del delito.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Agrofy se reserva el derecho de admisión y tendrá, en consecuencia, la facultad de decidir si una solicitud de registro en el Sitio se admite o rechaza sin tener que explicar los fundamentos
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agrofy
provenance_date: '2026-11-09'
provider_name: Agrofy
provider_slug: agrofy
slug: agrofy-eligibility
source_date: '2026-11-09'
source_filename: agrofy-eligibility.yml
source_heading: Eligibility
source_page: https://www.agrofy.com.ar/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agrofy\naid: agrofy\nurl: https://www.agrofy.com.ar/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AR\n  excluded: []\n  text: Capacidad legal para contratar bajo las leyes de la República Argentina\nentity_types:\n- type: individual\n  text: Todo Usuario del Sitio deberá ser mayor de edad, contar con la capacidad legal para contratar\n- type: business\n  text: Para el caso en que se registre una persona jurídica, la persona humana que realice la registración deberá\n    tener facultades para contratar y obligar a dicha persona jurídica\nrestricted_uses:\n- summary: Prohibited or\
  \ illegal content and conduct\n  text: No ingresar o difundir contenidos contrarios al honor, a la intimidad o a la imagen o propaganda de carácter\n    racista, xenófobo, pornográfico, o de apología del delito.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Agrofy se reserva el derecho de admisión y tendrá, en consecuencia, la facultad de decidir si una solicitud\n    de registro en el Sitio se admite o rechaza sin tener que explicar los fundamentos\nminimum_age:\n  value: '18'\n  text: Todo Usuario del Sitio deberá ser mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/agrofy/eligibility/agrofy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Agrofy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Agribusiness
- AgTech
- Marketplace
- E-Commerce
- Payments
- Latin America
- Argentina
- Brazil
---

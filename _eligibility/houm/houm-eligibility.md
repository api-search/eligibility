---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CL
    text: leyes que regulan el consumo de bienes y servicios en Chile
  entity_types:
  - text: El acceso al Sitio Web está limitado a mayores de 18 años.
    type: individual
  minimum_age:
    text: El acceso al Sitio Web está limitado a mayores de 18 años.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Houm podría negar el Registro de un Usuario si, a su juicio, no cumple con los Términos y Condiciones, Política de Privacidad de Houm y demás disposiciones pertinentes.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Houm
provenance_date: '2026-11-09'
provider_name: Houm
provider_slug: houm
slug: houm-eligibility
source_date: '2026-11-09'
source_filename: houm-eligibility.yml
source_heading: Eligibility
source_page: https://help.houm.com/cl/articles/397/t-1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Houm\naid: houm\nurl: https://help.houm.com/cl/articles/397/t-1\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CL\n  excluded: []\n  text: leyes que regulan el consumo de bienes y servicios en Chile\nentity_types:\n- type: individual\n  text: El acceso al Sitio Web está limitado a mayores de 18 años.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Houm podría negar el Registro de un Usuario si, a su juicio, no cumple con los Términos y Condiciones, Política\n    de Privacidad de Houm y demás disposiciones pertinentes.\nminimum_age:\n  value: '18'\n  text:\
  \ El acceso al Sitio Web está limitado a mayores de 18 años.\n"
source_yaml_url: https://artifacts.apis.io/houm/eligibility/houm-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Houm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Property Management
- Rentals
- Marketplace
- Latin America
- Chile
- Mexico
- Colombia
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: cruce de mercancías desde nuestras bodegas operativas en Estados Unidos (EE.UU.) y China hacia México
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited imports
    text: 'Esta prohibido importar: *Armas o productos relacionados'
  - summary: Goods requiring sanitary or government permits
    text: En caso de que las mercancías requieran autorizaciones sanitarias o cualquier otro tipo de procedimiento o autorización gubernamental para su importación, no podrán ser importadas por medio de nuestro servicio
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: La creación de envíos está sometida a revisión por los agentes de importaciones en Shopeando SAPI de CV
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shopeando
provenance_date: '2026-11-10'
provider_name: Shopeando
provider_slug: shopeando
slug: shopeando-eligibility
source_date: '2026-11-10'
source_filename: shopeando-eligibility.yml
source_heading: Eligibility
source_page: https://www.shopeando.mx/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shopeando\naid: shopeando\nurl: https://www.shopeando.mx/terminos-y-condiciones/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: cruce de mercancías desde nuestras bodegas operativas en Estados Unidos (EE.UU.) y China hacia México\nentity_types: []\nrestricted_uses:\n- summary: Prohibited imports\n  text: 'Esta prohibido importar: *Armas o productos relacionados'\n- summary: Goods requiring sanitary or government permits\n  text: En caso de que las mercancías requieran autorizaciones sanitarias o cualquier otro tipo de procedimiento\n    o autorización gubernamental para su\
  \ importación, no podrán ser importadas por medio de nuestro servicio\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: La creación de envíos está sometida a revisión por los agentes de importaciones en Shopeando SAPI de CV\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shopeando/eligibility/shopeando-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Shopeando's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Import Export
- Cross-Border Commerce
- E-Commerce
- Fulfillment
- Mexico
---

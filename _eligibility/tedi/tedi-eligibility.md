---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: El Usuario debe ser mayor de edad o contar con autorización legal para contratar.
    value: mayor de edad
  restricted_uses:
  - summary: Harassment and discrimination
    text: No acosar, discriminar ni atacar a otros usuarios bajo ninguna circunstancia.
  - summary: Spam and unauthorized commercial activity
    text: No realizar spam, promociones no autorizadas ni actividades comerciales dentro de los espacios comunitarios.
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
name: TEDI
provenance_date: '2026-11-10'
provider_name: TEDI
provider_slug: tedi
slug: tedi-eligibility
source_date: '2026-11-10'
source_filename: tedi-eligibility.yml
source_heading: Eligibility
source_page: https://tedivirtual.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TEDI\naid: tedi\nurl: https://tedivirtual.com/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment and discrimination\n  text: No acosar, discriminar ni atacar a otros usuarios bajo ninguna circunstancia.\n- summary: Spam and unauthorized commercial activity\n  text: No realizar spam, promociones no autorizadas ni actividades comerciales dentro de los espacios comunitarios.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: mayor de edad\n  text:\
  \ El Usuario debe ser mayor de edad o contar con autorización legal para contratar.\n"
source_yaml_url: https://artifacts.apis.io/tedi/eligibility/tedi-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TEDI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Construction
- Engineering
- Professional Training
- Certification
- Latin America
---

---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: No utilizar el servicio desde jurisdicciones donde el contenido pueda ser ilegal o estar restringido.
  entity_types:
  - text: Tener cumplidos 18 años o la mayoría de edad legal vigente en tu jurisdicción. Disponer de capacidad legal para contratar.
    type: individual
  minimum_age:
    text: Tener cumplidos 18 años o la mayoría de edad legal vigente en tu jurisdicción.
    value: '18'
  restricted_uses:
  - summary: Illicit or fraudulent use
    text: Usar el servicio para fines ilícitos, fraudulentos o contrarios al orden público.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Basta con crear una cuenta y verificar el correo electrónico.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bettrails
provenance_date: '2026-11-09'
provider_name: Bettrails
provider_slug: bettrails-com
slug: bettrails-com-eligibility
source_date: '2026-11-09'
source_filename: bettrails-com-eligibility.yml
source_heading: Eligibility
source_page: https://bettrails.com/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bettrails\naid: bettrails-com\nurl: https://bettrails.com/terms.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: No utilizar el servicio desde jurisdicciones donde el contenido pueda ser ilegal o estar restringido.\nentity_types:\n- type: individual\n  text: Tener cumplidos 18 años o la mayoría de edad legal vigente en tu jurisdicción. Disponer de capacidad legal\n    para contratar.\nrestricted_uses:\n- summary: Illicit or fraudulent use\n  text: Usar el servicio para fines ilícitos, fraudulentos o contrarios al orden público.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Basta con crear una cuenta y verificar el correo electrónico.\nminimum_age:\n  value: '18'\n  text: Tener cumplidos 18 años o la mayoría de edad legal vigente en tu jurisdicción.\n"
source_yaml_url: https://artifacts.apis.io/bettrails-com/eligibility/bettrails-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bettrails's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Esports
- Analytics
- Real-Time Data
- Gaming
---

---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: regulan el acceso, uso y/o utilización que usted haga desde cualquier lugar del mundo, excluidos aquellos en donde Memorick haya puesto a disposición y/o haya dado a conocer términos y condiciones distintos
  minimum_age:
    text: el Usuario sea mayor de 18 años y ser mayor de edad conforme a la legislación de su jurisdicción, cuando esta sea mayor a 18 años
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: son de uso personal exclusivamente, no pudiendo ser utilizados con fines comerciales sin la previa aprobación de Memorick.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: En cualquier momento Memorick y/o los terceros proveedores independientes contratados por el Usuario a través de los Servicios, podrán requerir una identificación oficial al Usuario
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Memorick
provenance_date: '2026-11-10'
provider_name: Memorick
provider_slug: memorick
slug: memorick-eligibility
source_date: '2026-11-10'
source_filename: memorick-eligibility.yml
source_heading: Eligibility
source_page: https://memorick.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Memorick\naid: memorick\nurl: https://memorick.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: regulan el acceso, uso y/o utilización que usted haga desde cualquier lugar del mundo, excluidos aquellos\n    en donde Memorick haya puesto a disposición y/o haya dado a conocer términos y condiciones distintos\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: son de uso personal exclusivamente, no pudiendo ser utilizados con fines comerciales sin la previa aprobación\n    de Memorick.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n\
  \  text: En cualquier momento Memorick y/o los terceros proveedores independientes contratados por el Usuario a través\n    de los Servicios, podrán requerir una identificación oficial al Usuario\nminimum_age:\n  value: '18'\n  text: el Usuario sea mayor de 18 años y ser mayor de edad conforme a la legislación de su jurisdicción, cuando\n    esta sea mayor a 18 años\n"
source_yaml_url: https://artifacts.apis.io/memorick/eligibility/memorick-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Memorick's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photography
- Booking
- Marketplace
- Travel
- Photographers
- OAuth
- Laravel
- Authentication
---

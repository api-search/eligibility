---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Para contratar y acceder al Servicio es necesario que el Usuario sea una persona física, mayor de edad
    type: individual
  minimum_age:
    text: mayor de edad
    value: null
  restricted_uses:
  - summary: Politically exposed persons not served
    text: Si determinamos que un usuario es PEP, lamentablemente no podremos ofrecerle servicio por nuestras políticas internas, y su cuenta será dada de baja.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: necesitamos validar tu documento de identidad, que respondas un cuestionario de idoneidad y que hayas validado una tarjeta de crédito o débito previamente validada por Prakma.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Goin
provenance_date: '2026-11-09'
provider_name: Goin
provider_slug: goin
slug: goin-eligibility
source_date: '2026-11-09'
source_filename: goin-eligibility.yml
source_heading: Eligibility
source_page: https://www.goin.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goin\naid: goin\nurl: https://www.goin.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Para contratar y acceder al Servicio es necesario que el Usuario sea una persona física, mayor de edad\nrestricted_uses:\n- summary: Politically exposed persons not served\n  text: Si determinamos que un usuario es PEP, lamentablemente no podremos ofrecerle servicio por nuestras políticas\n    internas, y su cuenta será dada de baja.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: necesitamos validar tu documento\
  \ de identidad, que respondas un cuestionario de idoneidad y que hayas validado\n    una tarjeta de crédito o débito previamente validada por Prakma.\nminimum_age:\n  value: null\n  text: mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/goin/eligibility/goin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Goin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Personal Finance
- Savings
- Investing
- Cryptocurrency
- Cashback
- Rewards
- Open Banking
- PSD2
- Consumer App
- Europe
- Spain
---

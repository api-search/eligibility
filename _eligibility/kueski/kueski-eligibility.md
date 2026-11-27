---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Kueski únicamente realiza operaciones en México.
  entity_types:
  - text: 'Recuerda cumplir los siguientes requisitos: ser mayor de edad, ser de nacionalidad mexicana, domicilio en territorio nacional y credencial para votar original vigente o pasaporte mexicano vigente.'
    type: individual
  minimum_age:
    text: ser mayor de edad
    value: mayor de edad
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: '*Todos nuestros créditos son sujetos a aprobación'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kueski
provenance_date: '2026-11-09'
provider_name: Kueski
provider_slug: kueski
slug: kueski-eligibility
source_date: '2026-11-09'
source_filename: kueski-eligibility.yml
source_heading: Eligibility
source_page: https://www.kueskipay.com/tyc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kueski\naid: kueski\nurl: https://www.kueskipay.com/tyc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Kueski únicamente realiza operaciones en México.\nentity_types:\n- type: individual\n  text: 'Recuerda cumplir los siguientes requisitos: ser mayor de edad, ser de nacionalidad mexicana, domicilio\n    en territorio nacional y credencial para votar original vigente o pasaporte mexicano vigente.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: '*Todos nuestros créditos son sujetos a aprobación'\nminimum_age:\n  value: mayor\
  \ de edad\n  text: ser mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/kueski/eligibility/kueski-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kueski's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Buy Now Pay Later
- Lending
- Fintech
- Financial Services
- Consumer Credit
- E-Commerce
- Checkout
- Mexico
- Latin America
---

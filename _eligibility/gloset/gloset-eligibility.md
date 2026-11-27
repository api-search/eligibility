---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: No se permite a las personas dedicadas al comercio la utilización de los Servicios.
    type: business
  - text: Los Servicios prestados en el Sitio deberán ser utilizados por personas que tengan capacidad legal suficiente para obligarse en términos del presente contrato.
    type: individual
  minimum_age:
    text: Los Servicios no están destinados a su uso por parte de niños menores de 18 años.
    value: '18'
  restricted_uses:
  - summary: Users must be legally capable
    text: No podrán utilizar los servicios las personas que no tengan esa capacidad ni los menores de edad.
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
name: Gloset
provenance_date: '2026-11-09'
provider_name: Gloset
provider_slug: gloset
slug: gloset-eligibility
source_date: '2026-11-09'
source_filename: gloset-eligibility.yml
source_heading: Eligibility
source_page: https://gloset.mx/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gloset\naid: gloset\nurl: https://gloset.mx/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: No se permite a las personas dedicadas al comercio la utilización de los Servicios.\n- type: individual\n  text: Los Servicios prestados en el Sitio deberán ser utilizados por personas que tengan capacidad legal suficiente\n    para obligarse en términos del presente contrato.\nrestricted_uses:\n- summary: Users must be legally capable\n  text: No podrán utilizar los servicios las personas que no tengan esa capacidad ni los menores\
  \ de edad.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Los Servicios no están destinados a su uso por parte de niños menores de 18 años.\n"
source_yaml_url: https://artifacts.apis.io/gloset/eligibility/gloset-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gloset's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Fashion
- E-Commerce
- Resale
- Peer-to-Peer
- Mexico
- Retail
---

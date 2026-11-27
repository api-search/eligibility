---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - GB
    text: Products and Services offered for sale on the Sites are available for shipment only to the United States, Canada and the United Kingdom (UK)
  entity_types:
  - text: you must be of legal age (18 years of age or older)
    type: individual
  - text: If you use the Sites or Services on behalf of any third party, you agree that you are an authorized representative of that third party
    type: business
  minimum_age:
    text: you must be of legal age (18 years of age or older)
    value: '18'
  restricted_uses:
  - summary: Personal use only; no resale
    text: Products and Services are for your personal use only. You agree not to sell or resell any Products you purchase or otherwise receive from us.
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
name: FabFitFun
provenance_date: '2026-11-09'
provider_name: FabFitFun
provider_slug: fabfitfun
slug: fabfitfun-eligibility
source_date: '2026-11-09'
source_filename: fabfitfun-eligibility.yml
source_heading: Eligibility
source_page: https://legal.fabfitfun.com/#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FabFitFun\naid: fabfitfun\nurl: https://legal.fabfitfun.com/#terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  - GB\n  excluded: []\n  text: Products and Services offered for sale on the Sites are available for shipment only to the United States,\n    Canada and the United Kingdom (UK)\nentity_types:\n- type: individual\n  text: you must be of legal age (18 years of age or older)\n- type: business\n  text: If you use the Sites or Services on behalf of any third party, you agree that you are an authorized representative\n    of that third party\nrestricted_uses:\n\
  - summary: Personal use only; no resale\n  text: Products and Services are for your personal use only. You agree not to sell or resell any Products you purchase\n    or otherwise receive from us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be of legal age (18 years of age or older)\n"
source_yaml_url: https://artifacts.apis.io/fabfitfun/eligibility/fabfitfun-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from FabFitFun's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Subscription
- E-Commerce
- Retail
- Consumer
- Beauty
- Lifestyle
- Direct to Consumer
---

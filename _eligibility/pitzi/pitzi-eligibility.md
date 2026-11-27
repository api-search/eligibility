---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: Apenas celulares comercializados e comprados no Brasil.
  entity_types:
  - text: Você é autorizado a usar a Proteção do Clube Pitzi apenas para seu uso pessoal, não comercial.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use not permitted
    text: Você é autorizado a usar a Proteção do Clube Pitzi apenas para seu uso pessoal, não comercial.
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
name: Pitzi
provenance_date: '2026-11-10'
provider_name: Pitzi
provider_slug: pitzi
slug: pitzi-eligibility
source_date: '2026-11-10'
source_filename: pitzi-eligibility.yml
source_heading: Eligibility
source_page: https://pitzi.com.br/termos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pitzi\naid: pitzi\nurl: https://pitzi.com.br/termos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: Apenas celulares comercializados e comprados no Brasil.\nentity_types:\n- type: individual\n  text: Você é autorizado a usar a Proteção do Clube Pitzi apenas para seu uso pessoal, não comercial.\nrestricted_uses:\n- summary: Commercial use not permitted\n  text: Você é autorizado a usar a Proteção do Clube Pitzi apenas para seu uso pessoal, não comercial.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pitzi/eligibility/pitzi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pitzi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Insurtech
- Insurance
- Mobile
- Device Protection
- Brazil
- Consumer
---

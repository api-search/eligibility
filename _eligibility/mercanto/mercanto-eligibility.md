---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Entregas en CDMX según horarios acordados.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Términos de crédito según aprobación crediticia individual.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mercanto
provenance_date: '2026-11-10'
provider_name: Mercanto
provider_slug: mercanto
slug: mercanto-eligibility
source_date: '2026-11-10'
source_filename: mercanto-eligibility.yml
source_heading: Eligibility
source_page: https://mercanto.mx/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mercanto\naid: mercanto\nurl: https://mercanto.mx/terminos-y-condiciones\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Entregas en CDMX según horarios acordados.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Términos de crédito según aprobación crediticia individual.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mercanto/eligibility/mercanto-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Mercanto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Marketplace
- Wholesale
- Food and Beverage
- Restaurant
- B2B
- Supply Chain
- Grocery
- Mexico
---

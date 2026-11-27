---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - EC
    text: Términos y condiciones de uso de los servicios de Taxo en Ecuador.
  entity_types:
  - text: Diseñado para despachos contables y empresas
    type: business
  minimum_age:
    text: null
    value: null
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
name: TAXO
provenance_date: '2026-11-10'
provider_name: TAXO
provider_slug: taxo
slug: taxo-eligibility
source_date: '2026-11-10'
source_filename: taxo-eligibility.yml
source_heading: Eligibility
source_page: https://taxo.co/ec/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TAXO\naid: taxo\nurl: https://taxo.co/ec/terminos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EC\n  excluded: []\n  text: Términos y condiciones de uso de los servicios de Taxo en Ecuador.\nentity_types:\n- type: business\n  text: Diseñado para despachos contables y empresas\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/taxo/eligibility/taxo-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from TAXO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accounting
- Tax
- Fintech
- E-Invoicing
- Facturación Electrónica
- CFDI
- SRI
- SAT
- Artificial Intelligence
- Ecuador
- Mexico
---

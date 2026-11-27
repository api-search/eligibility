---
api_specs:
- filename: adexto-xyz-x402-api-openapi.yml
  format: yaml
  label: ADEXTO X402 API
  slug: adexto-xyz-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adexto-xyz/openapi/adexto-xyz-x402-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not use ADEXTO from, or for the benefit of anyone in, a country or region under comprehensive sanctions by any of them.
  entity_types:
  - text: You must be at least 18, or the age of majority where you live if that is higher, and able to enter into a binding agreement.
    type: individual
  - text: If you use ADEXTO for an organisation, you accept these terms for it and confirm you may do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: You must not be a person or entity named on a sanctions list of the United Nations, the United States (OFAC), the European Union or the United Kingdom, owned or controlled by one, or acting for one.
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
name: ADEXTO
provenance_date: '2026-11-09'
provider_name: ADEXTO
provider_slug: adexto-xyz
slug: adexto-xyz-eligibility
source_date: '2026-11-09'
source_filename: adexto-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://adexto.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ADEXTO\naid: adexto-xyz\nurl: https://adexto.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not use ADEXTO from, or for the benefit of anyone in, a country or region under comprehensive sanctions\n    by any of them.\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live if that is higher, and able to enter into\n    a binding agreement.\n- type: business\n  text: If you use ADEXTO for an organisation, you accept these terms for it and confirm you may do so.\nrestricted_uses:\n- summary: Sanctioned persons\n\
  \  text: You must not be a person or entity named on a sanctions list of the United Nations, the United States (OFAC),\n    the European Union or the United Kingdom, owned or controlled by one, or acting for one.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adexto-xyz/eligibility/adexto-xyz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ADEXTO's own page on 2026-11-09.
synthetic: false
tags:
- DeFi
- Token Launch
- Bonding Curve
- AI Agents
- Blockchain
---

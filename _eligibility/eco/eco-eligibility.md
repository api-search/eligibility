---
api_specs:
- filename: eco-quotes-v1-api-openapi.yml
  format: yaml
  label: Eco Quotes V1 API
  slug: eco-quotes-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eco/openapi/eco-quotes-v1-api-openapi.yml
- filename: eco-quotes-v2-api-openapi.yml
  format: yaml
  label: Eco Quotes V2 API
  slug: eco-quotes-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eco/openapi/eco-quotes-v2-api-openapi.yml
- filename: eco-quotes-v3-api-openapi.yml
  format: yaml
  label: Eco Quotes V3 API
  slug: eco-quotes-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eco/openapi/eco-quotes-v3-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located, organized, or ordinarily resident in any country, territory, or region subject to comprehensive sanctions
  entity_types:
  - text: you are at least 18 years old (or the age of majority in your jurisdiction, if higher) and have the legal capacity to enter into these Terms
    type: individual
  - text: if you access the Site on behalf of an entity, you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least 18 years old (or the age of majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful activity
    text: use the Site to facilitate fraud, scams, phishing, market manipulation, or any unlawful activity
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
name: Eco
provenance_date: '2026-11-09'
provider_name: Eco
provider_slug: eco
slug: eco-eligibility
source_date: '2026-11-09'
source_filename: eco-eligibility.yml
source_heading: Eligibility
source_page: https://eco.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eco\naid: eco\nurl: https://eco.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located, organized, or ordinarily resident in any country, territory, or region subject to comprehensive\n    sanctions\nentity_types:\n- type: individual\n  text: you are at least 18 years old (or the age of majority in your jurisdiction, if higher) and have the legal\n    capacity to enter into these Terms\n- type: business\n  text: if you access the Site on behalf of an entity, you have authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful, fraudulent\
  \ or harmful activity\n  text: use the Site to facilitate fraud, scams, phishing, market manipulation, or any unlawful activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old (or the age of majority in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/eco/eligibility/eco-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Eco's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Stablecoins
- Cryptocurrency
- Payments
- Blockchain
- Cross-Chain
- DeFi
- Web3
- Infrastructure
- Financial Services
---

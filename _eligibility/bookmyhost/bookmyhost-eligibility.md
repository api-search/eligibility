---
api_specs:
- filename: bookmyhost-public-openapi.json
  format: json
  label: BookMyHost API
  slug: bookmyhost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookmyhost/openapi/_original/bookmyhost-public-openapi.json
- filename: openapi.json
  format: json
  label: BookMyHost AI API (LiteLLM proxy)
  slug: bookmyhost-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookmyhost/openapi/_original/openapi.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering a contract.
    type: individual
  - text: Indian customers verify via email plus Aadhaar/DigiLocker (individuals) or GSTIN (businesses)
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering a contract.
    value: '18'
  restricted_uses:
  - summary: Cryptomining or reselling raw capacity
    text: mine cryptocurrency, or resell raw capacity, except with our prior written consent;
  - summary: Child sexual abuse material
    text: host or transmit child sexual abuse material
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Identity verification (KYC) is mandatory before services are provisioned.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blazing Bullet Private Limited
provenance_date: '2026-11-09'
provider_name: Blazing Bullet Private Limited
provider_slug: bookmyhost
slug: bookmyhost-eligibility
source_date: '2026-11-09'
source_filename: bookmyhost-eligibility.yml
source_heading: Eligibility
source_page: https://bookmyhost.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blazing Bullet Private Limited\naid: bookmyhost\nurl: https://bookmyhost.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering a contract.\n- type: business\n  text: Indian customers verify via email plus Aadhaar/DigiLocker (individuals) or GSTIN (businesses)\nrestricted_uses:\n- summary: Cryptomining or reselling raw capacity\n  text: mine cryptocurrency, or resell raw capacity, except with our prior written consent;\n- summary: Child sexual abuse material\n  text:\
  \ host or transmit child sexual abuse material\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Identity verification (KYC) is mandatory before services are provisioned.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering a contract.\n"
source_yaml_url: https://artifacts.apis.io/bookmyhost/eligibility/bookmyhost-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Blazing Bullet Private Limited's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Hosting
- VPS
- India
---

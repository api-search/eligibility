---
api_specs:
- filename: birdeye-so-data-openapi-generated.yml
  format: yaml
  label: Birdeye (Solana data) data API
  slug: data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/birdeye-so/openapi/_ae-authored/birdeye-so-data-openapi-generated.yml
- filename: birdeye-so-resources-openapi-generated.yml
  format: yaml
  label: Birdeye (Solana data) resources API
  slug: resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/birdeye-so/openapi/_ae-authored/birdeye-so-resources-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years to register and maintain an Account with Wings Lab.
    type: individual
  - text: Where you are creating an Account on behalf of a corporate entity, you warrant and represent that you have the requisite authority to do so
    type: business
  minimum_age:
    text: You must be at least 18 years to register and maintain an Account with Wings Lab.
    value: '18'
  restricted_uses:
  - summary: personal use only
    text: You will only use the Services for your personal own use and will not resell it to a third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will provide Wings Lab with proof of identity as it may reasonably request or require
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Birdeye (Solana data)
provenance_date: '2026-11-09'
provider_name: Birdeye (Solana data)
provider_slug: birdeye-so
slug: birdeye-so-eligibility
source_date: '2026-11-09'
source_filename: birdeye-so-eligibility.yml
source_heading: Eligibility
source_page: https://data.birdeye.so/docs/resources/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Birdeye (Solana data)\naid: birdeye-so\nurl: https://data.birdeye.so/docs/resources/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years to register and maintain an Account with Wings Lab.\n- type: business\n  text: Where you are creating an Account on behalf of a corporate entity, you warrant and represent that you have\n    the requisite authority to do so\nrestricted_uses:\n- summary: personal use only\n  text: You will only use the Services for your personal own use and will not resell it to a third\
  \ party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will provide Wings Lab with proof of identity as it may reasonably request or require\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years to register and maintain an Account with Wings Lab.\n"
source_yaml_url: https://artifacts.apis.io/birdeye-so/eligibility/birdeye-so-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Birdeye (Solana data)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Data
- Analytics
- Tokens
---

---
api_specs:
- filename: palmetto-bem-api-openapi.yml
  format: yaml
  label: Palmetto Bem API
  slug: palmetto-bem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palmetto/openapi/palmetto-bem-api-openapi.yml
- filename: palmetto-health-api-openapi.yml
  format: yaml
  label: Palmetto Health API
  slug: palmetto-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palmetto/openapi/palmetto-health-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To access and use the Platform, you must be 18 years of age or older and located in the United States.
  entity_types:
  - text: “User” means an individual Platform user who accesses and uses the Platform on behalf of themselves as an individual.
    type: individual
  - text: you accept and agree to be bound by this Agreement on behalf of yourself and, if applicable, the entity for which you are acting
    type: business
  minimum_age:
    text: To access and use the Platform, you must be 18 years of age or older and located in the United States.
    value: '18'
  restricted_uses:
  - summary: Ambassador program eligibility
    text: Eligibility to participate in the Palmetto Ambassador Referral Program is limited to individuals only.
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
name: Palmetto
provenance_date: '2026-11-10'
provider_name: Palmetto
provider_slug: palmetto
slug: palmetto-eligibility
source_date: '2026-11-10'
source_filename: palmetto-eligibility.yml
source_heading: Eligibility
source_page: https://palmetto.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Palmetto\naid: palmetto\nurl: https://palmetto.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To access and use the Platform, you must be 18 years of age or older and located in the United States.\nentity_types:\n- type: individual\n  text: “User” means an individual Platform user who accesses and uses the Platform on behalf of themselves as an\n    individual.\n- type: business\n  text: you accept and agree to be bound by this Agreement on behalf of yourself and, if applicable, the entity\n    for which you are acting\nrestricted_uses:\n- summary:\
  \ Ambassador program eligibility\n  text: Eligibility to participate in the Palmetto Ambassador Referral Program is limited to individuals only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To access and use the Platform, you must be 18 years of age or older and located in the United States.\n"
source_yaml_url: https://artifacts.apis.io/palmetto/eligibility/palmetto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Palmetto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clean Energy
- Solar
- Energy
- Building Energy Modeling
- Home Energy
- Financing
- Sustainability
---

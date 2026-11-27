---
api_specs:
- filename: fxsocket-com-openapi-generated.yml
  format: yaml
  label: FxSocket API
  slug: fxsocket-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxsocket-com/openapi/_ae-authored/fxsocket-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You further represent that you are not located in a country or region subject to comprehensive U.S. or EU sanctions, or designated as a terrorist organization by any relevant government authority.
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into binding contracts to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: High-frequency trading violating broker terms
    text: Use the Service to facilitate high-frequency trading that violates your broker's terms or applicable regulations.
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
name: FxSocket
provenance_date: '2026-11-09'
provider_name: FxSocket
provider_slug: fxsocket-com
slug: fxsocket-com-eligibility
source_date: '2026-11-09'
source_filename: fxsocket-com-eligibility.yml
source_heading: Eligibility
source_page: https://fxsocket.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FxSocket\naid: fxsocket-com\nurl: https://fxsocket.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You further represent that you are not located in a country or region subject to comprehensive U.S. or EU\n    sanctions, or designated as a terrorist organization by any relevant government authority.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into binding contracts to use our services.\nrestricted_uses:\n- summary: High-frequency trading violating broker terms\n  text: Use the Service to facilitate high-frequency\
  \ trading that violates your broker's terms or applicable regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/fxsocket-com/eligibility/fxsocket-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FxSocket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Trading
- Cloud
---

---
api_specs:
- filename: reposit-power-auth-api-openapi.yml
  format: yaml
  label: Reposit Power Auth API
  slug: reposit-power-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-auth-api-openapi.yml
- filename: reposit-power-battery-api-openapi.yml
  format: yaml
  label: Reposit Power Battery API
  slug: reposit-power-battery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-battery-api-openapi.yml
- filename: reposit-power-curtailment-api-openapi.yml
  format: yaml
  label: Reposit Power Curtailment API
  slug: reposit-power-curtailment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-curtailment-api-openapi.yml
- filename: reposit-power-deployment-api-openapi.yml
  format: yaml
  label: Reposit Power Deployment API
  slug: reposit-power-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-deployment-api-openapi.yml
- filename: reposit-power-dispatch-api-openapi.yml
  format: yaml
  label: Reposit Power Dispatch API
  slug: reposit-power-dispatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-dispatch-api-openapi.yml
- filename: reposit-power-inverter-api-openapi.yml
  format: yaml
  label: Reposit Power Inverter API
  slug: reposit-power-inverter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-inverter-api-openapi.yml
- filename: reposit-power-network-api-openapi.yml
  format: yaml
  label: Reposit Power Network API
  slug: reposit-power-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-network-api-openapi.yml
- filename: reposit-power-node-api-openapi.yml
  format: yaml
  label: Reposit Power Node API
  slug: reposit-power-node-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-node-api-openapi.yml
- filename: reposit-power-power-station-api-openapi.yml
  format: yaml
  label: Reposit Power Station API
  slug: reposit-power-power-station-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-power-station-api-openapi.yml
- filename: reposit-power-solar-api-openapi.yml
  format: yaml
  label: Reposit Power Solar API
  slug: reposit-power-solar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-solar-api-openapi.yml
- filename: reposit-power-users-api-openapi.yml
  format: yaml
  label: Reposit Power Users API
  slug: reposit-power-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reposit-power/openapi/reposit-power-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: No Bill is available to homeowners in our service areas.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fair use cap on energy consumption
    text: your No Bill guarantee includes a fair use policy to ensure that all No Bill customers consume their energy in a fair and equitable way.
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
name: Reposit Power
provenance_date: '2026-11-10'
provider_name: Reposit Power
provider_slug: reposit-power
slug: reposit-power-eligibility
source_date: '2026-11-10'
source_filename: reposit-power-eligibility.yml
source_heading: Eligibility
source_page: https://repositpower.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reposit Power\naid: reposit-power\nurl: https://repositpower.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: No Bill is available to homeowners in our service areas.\nrestricted_uses:\n- summary: Fair use cap on energy consumption\n  text: your No Bill guarantee includes a fair use policy to ensure that all No Bill customers consume their energy\n    in a fair and equitable way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reposit-power/eligibility/reposit-power-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Reposit Power's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Australia
- Utilities
- Electricity
- Batteries
- DER
- Virtual Power Plant
- Demand Response
- Solar
- Grid
- Energy Markets
- Smart Metering
- Storage
- Flexibility
---

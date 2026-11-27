---
api_specs:
- filename: voltus-dispatches-api-openapi.yml
  format: yaml
  label: Voltus Dispatches API
  slug: voltus-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-dispatches-api-openapi.yml
- filename: voltus-sites-api-openapi.yml
  format: yaml
  label: Voltus Sites API
  slug: voltus-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-sites-api-openapi.yml
- filename: voltus-telemetry-api-openapi.yml
  format: yaml
  label: Voltus Telemetry API
  slug: voltus-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-telemetry-api-openapi.yml
- filename: voltus-webhooks-api-openapi.yml
  format: yaml
  label: Voltus Webhooks API
  slug: voltus-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information about yourself.
    type: individual
  minimum_age:
    text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information about yourself.
    value: '18'
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
name: Voltus
provenance_date: '2026-11-10'
provider_name: Voltus
provider_slug: voltus
slug: voltus-eligibility
source_date: '2026-11-10'
source_filename: voltus-eligibility.yml
source_heading: Eligibility
source_page: https://www.voltus.co/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voltus\naid: voltus\nurl: https://www.voltus.co/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information\n    about yourself.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information\n    about yourself.\n"
source_yaml_url: https://artifacts.apis.io/voltus/eligibility/voltus-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Voltus's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Electricity
- Demand Response
- Virtual Power Plant
- DER
- Grid
- Energy Markets
- Flexibility
- Energy Storage
- OpenADR
- Telemetry
---

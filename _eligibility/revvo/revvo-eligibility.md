---
api_specs:
- filename: revvo-api-keys-api-openapi.yml
  format: yaml
  label: Revvo Api-keys API
  slug: revvo-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-api-keys-api-openapi.yml
- filename: revvo-auth-api-openapi.yml
  format: yaml
  label: Revvo Auth API
  slug: revvo-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-auth-api-openapi.yml
- filename: revvo-device-api-openapi.yml
  format: yaml
  label: Revvo Device API
  slug: revvo-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-device-api-openapi.yml
- filename: revvo-event-api-openapi.yml
  format: yaml
  label: Revvo Event API
  slug: revvo-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-event-api-openapi.yml
- filename: revvo-fleet-api-openapi.yml
  format: yaml
  label: Revvo Fleet API
  slug: revvo-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-fleet-api-openapi.yml
- filename: revvo-tire-operation-api-openapi.yml
  format: yaml
  label: Revvo Tire Operation API
  slug: revvo-tire-operation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-tire-operation-api-openapi.yml
- filename: revvo-vehicle-api-openapi.yml
  format: yaml
  label: Revvo Vehicle API
  slug: revvo-vehicle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revvo/openapi/revvo-vehicle-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority in state or province of residence
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Revvo
provenance_date: '2026-11-10'
provider_name: Revvo
provider_slug: revvo
slug: revvo-eligibility
source_date: '2026-11-10'
source_filename: revvo-eligibility.yml
source_heading: Eligibility
source_page: https://www.revvo.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revvo\naid: revvo\nurl: https://www.revvo.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state or province of residence\n  text: you represent that you are at\
  \ least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/revvo/eligibility/revvo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Revvo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fleet Management
- Transportation
- Tire Management
- TPMS
- Telematics
- IoT
- Logistics
---

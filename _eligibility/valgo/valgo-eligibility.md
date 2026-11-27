---
api_specs:
- filename: valgo-compute-api-openapi.yml
  format: yaml
  label: Valgo Compute API
  slug: valgo-compute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-compute-api-openapi.yml
- filename: valgo-compute-batch-api-openapi.yml
  format: yaml
  label: Valgo Compute Batch API
  slug: valgo-compute-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-compute-batch-api-openapi.yml
- filename: valgo-compute-depot-route-api-openapi.yml
  format: yaml
  label: Valgo Compute Depot Route API
  slug: valgo-compute-depot-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-compute-depot-route-api-openapi.yml
- filename: valgo-compute-route-api-openapi.yml
  format: yaml
  label: Valgo Compute Route API
  slug: valgo-compute-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-compute-route-api-openapi.yml
- filename: valgo-health-api-openapi.yml
  format: yaml
  label: Valgo Health API
  slug: valgo-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-health-api-openapi.yml
- filename: valgo-manifest-api-openapi.yml
  format: yaml
  label: Valgo Manifest API
  slug: valgo-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-manifest-api-openapi.yml
- filename: valgo-request-api-key-api-openapi.yml
  format: yaml
  label: Valgo Request Api Key API
  slug: valgo-request-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-request-api-key-api-openapi.yml
- filename: valgo-filters-api-openapi.yml
  format: yaml
  label: Valgo Filters API
  slug: valgo-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-filters-api-openapi.yml
- filename: valgo-regions-api-openapi.yml
  format: yaml
  label: Valgo Regions API
  slug: valgo-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valgo/openapi/valgo-regions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No identifying or soliciting crash participants
    text: use the Services to identify, contact, or solicit any person involved in a crash
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to the Human Crash Baselines tool is currently invite-only and limited to email addresses we have approved.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Valgo
provenance_date: '2026-11-10'
provider_name: Valgo
provider_slug: valgo
slug: valgo-eligibility
source_date: '2026-11-10'
source_filename: valgo-eligibility.yml
source_heading: Eligibility
source_page: https://valgo.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valgo\naid: valgo\nurl: https://valgo.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No identifying or soliciting crash participants\n  text: use the Services to identify, contact, or solicit any person involved in a crash\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access to the Human Crash Baselines tool is currently invite-only and limited to email addresses we have\n    approved.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/valgo/eligibility/valgo-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Valgo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Risk Management
- Autonomous Vehicles
- Robotics
- Artificial Intelligence
- Safety Validation
- Actuarial
---

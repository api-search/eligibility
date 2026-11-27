---
api_specs:
- filename: answerline-dev-async-api-openapi.yml
  format: yaml
  label: answerline-dev Async API
  slug: answerline-dev-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-async-api-openapi.yml
- filename: answerline-dev-countries-api-openapi.yml
  format: yaml
  label: answerline-dev Countries API
  slug: answerline-dev-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-countries-api-openapi.yml
- filename: answerline-dev-credits-api-openapi.yml
  format: yaml
  label: answerline-dev Credits API
  slug: answerline-dev-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-credits-api-openapi.yml
- filename: answerline-dev-monitor-api-openapi.yml
  format: yaml
  label: answerline-dev Monitor API
  slug: answerline-dev-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-monitor-api-openapi.yml
- filename: answerline-dev-states-api-openapi.yml
  format: yaml
  label: answerline-dev States API
  slug: answerline-dev-states-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-states-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and provide a valid email address.
    type: individual
  - text: If you use the service for an organization, you confirm you can bind it.
    type: business
  minimum_age:
    text: You must be at least 18
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
name: answerline-dev
provenance_date: '2026-11-09'
provider_name: answerline-dev
provider_slug: answerline-dev
slug: answerline-dev-eligibility
source_date: '2026-11-09'
source_filename: answerline-dev-eligibility.yml
source_heading: Eligibility
source_page: https://answerline.dev/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: answerline-dev\naid: answerline-dev\nurl: https://answerline.dev/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and provide a valid email address.\n- type: business\n  text: If you use the service for an organization, you confirm you can bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/answerline-dev/eligibility/answerline-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from answerline-dev's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Visibility
- Marketing
- Analytics
---

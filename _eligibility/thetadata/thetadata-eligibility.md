---
api_specs:
- filename: thetadata-streaming-asyncapi.yml
  format: yaml
  label: ThetaData Streaming WebSocket API
  slug: thetadata-streaming-websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/thetadata/asyncapi/thetadata-streaming-asyncapi.yml
- filename: thetadata-calendar-api-openapi.yml
  format: yaml
  label: ThetaData Calendar API
  slug: thetadata-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-calendar-api-openapi.yml
- filename: thetadata-index-api-openapi.yml
  format: yaml
  label: ThetaData Index API
  slug: thetadata-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-index-api-openapi.yml
- filename: thetadata-interest-rate-api-openapi.yml
  format: yaml
  label: ThetaData Interest Rate API
  slug: thetadata-interest-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-interest-rate-api-openapi.yml
- filename: thetadata-option-api-openapi.yml
  format: yaml
  label: ThetaData Option API
  slug: thetadata-option-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-option-api-openapi.yml
- filename: thetadata-stock-api-openapi.yml
  format: yaml
  label: ThetaData Stock API
  slug: thetadata-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thetadata/openapi/thetadata-stock-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each Authorized User must be at least eighteen (18) years old or the age of legal majority in his or her jurisdiction of residence to access and use the Service.
    type: individual
  minimum_age:
    text: Each Authorized User must be at least eighteen (18) years old or the age of legal majority in his or her jurisdiction of residence to access and use the Service.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: The Services are for use solely in connection with your personal investment activities and the personal investment activities of your immediate family members and qualifying trusts of which you are the trustee or custodian.
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
name: ThetaData
provenance_date: '2026-11-10'
provider_name: ThetaData
provider_slug: thetadata
slug: thetadata-eligibility
source_date: '2026-11-10'
source_filename: thetadata-eligibility.yml
source_heading: Eligibility
source_page: https://thetadata.net/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThetaData\naid: thetadata\nurl: https://thetadata.net/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each Authorized User must be at least eighteen (18) years old or the age of legal majority in his or her\n    jurisdiction of residence to access and use the Service.\nrestricted_uses:\n- summary: Personal use only\n  text: The Services are for use solely in connection with your personal investment activities and the personal\n    investment activities of your immediate family members and qualifying trusts of which\
  \ you are the trustee or\n    custodian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Each Authorized User must be at least eighteen (18) years old or the age of legal majority in his or her\n    jurisdiction of residence to access and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/thetadata/eligibility/thetadata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ThetaData's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Market Data
- Options
- Stocks
- Indices
- Real-Time
- Historical Data
- Trading
---

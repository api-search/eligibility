---
api_specs:
- filename: con-edison-applicationinformation-api-openapi.yml
  format: yaml
  label: Con Edison Application Information API
  slug: con-edison-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-applicationinformation-api-openapi.yml
- filename: con-edison-authorization-api-openapi.yml
  format: yaml
  label: Con Edison Authorization API
  slug: con-edison-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-authorization-api-openapi.yml
- filename: con-edison-batch-api-openapi.yml
  format: yaml
  label: Con Edison Batch API
  slug: con-edison-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-batch-api-openapi.yml
- filename: con-edison-electricpowerusagesummary-api-openapi.yml
  format: yaml
  label: Con Edison Electric Power Usage Summary API
  slug: con-edison-electricpowerusagesummary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-electricpowerusagesummary-api-openapi.yml
- filename: con-edison-intervalblock-api-openapi.yml
  format: yaml
  label: Con Edison Interval Block API
  slug: con-edison-intervalblock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-intervalblock-api-openapi.yml
- filename: con-edison-localtimeparameters-api-openapi.yml
  format: yaml
  label: Con Edison Local Time Parameters API
  slug: con-edison-localtimeparameters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-localtimeparameters-api-openapi.yml
- filename: con-edison-meterreading-api-openapi.yml
  format: yaml
  label: Con Edison Meter Reading API
  slug: con-edison-meterreading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-meterreading-api-openapi.yml
- filename: con-edison-readingtype-api-openapi.yml
  format: yaml
  label: Con Edison Reading Type API
  slug: con-edison-readingtype-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-readingtype-api-openapi.yml
- filename: con-edison-realtimebatch-api-openapi.yml
  format: yaml
  label: Con Edison Real Time Batch API
  slug: con-edison-realtimebatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-realtimebatch-api-openapi.yml
- filename: con-edison-realtimeintervalblock-api-openapi.yml
  format: yaml
  label: Con Edison Real Time Interval Block API
  slug: con-edison-realtimeintervalblock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-realtimeintervalblock-api-openapi.yml
- filename: con-edison-realtimereadingtype-api-openapi.yml
  format: yaml
  label: Con Edison Real Time Reading Type API
  slug: con-edison-realtimereadingtype-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-realtimereadingtype-api-openapi.yml
- filename: con-edison-retailcustomer-api-openapi.yml
  format: yaml
  label: Con Edison Retail Customer API
  slug: con-edison-retailcustomer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-retailcustomer-api-openapi.yml
- filename: con-edison-usagepoint-api-openapi.yml
  format: yaml
  label: Con Edison Usage Point API
  slug: con-edison-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-usagepoint-api-openapi.yml
- filename: con-edison-service-status-api-openapi.yml
  format: yaml
  label: Con Edison Service Status API
  slug: con-edison-service-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/con-edison/openapi/con-edison-service-status-api-openapi.yml
claim_count: 1
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
  - summary: Account services limited to account holder or authorized agent
    text: Con Edison's account services and customer-specific information are solely intended for use by the customer who is the account holder or the customer's authorized agent.
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
name: Con Edison
provenance_date: '2026-11-09'
provider_name: Con Edison
provider_slug: con-edison
slug: con-edison-eligibility
source_date: '2026-11-09'
source_filename: con-edison-eligibility.yml
source_heading: Eligibility
source_page: https://www.coned.com/en/login?url=%2fen%2faccounts-billing%2fdashboard%2fbilling-and-usage%2fterms-of-use&returnUrl=%2Fen%2Faccounts-billing%2Fdashboard%2Fbilling-and-usage%2Fterms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Con Edison\naid: con-edison\nurl: https://www.coned.com/en/login?url=%2fen%2faccounts-billing%2fdashboard%2fbilling-and-usage%2fterms-of-use&returnUrl=%2Fen%2Faccounts-billing%2Fdashboard%2Fbilling-and-usage%2Fterms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Account services limited to account holder or authorized agent\n  text: Con Edison's account services and customer-specific information are solely intended for use by the customer\n    who is the account holder or the customer's authorized agent.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/con-edison/eligibility/con-edison-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Con Edison's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United States
- New York
- Utilities
- Electricity
- Gas
- Steam
- Smart Metering
- Green Button
- Energy Data
- Grid
- Distribution
- Hosting Capacity
- Distributed Energy Resources
- Solar
- EV Charging
- Demand Response
---

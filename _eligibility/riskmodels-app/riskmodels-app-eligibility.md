---
api_specs:
- filename: riskmodels-app-13f-filers-api-openapi.yml
  format: yaml
  label: riskmodels-app 13F Filers API
  slug: riskmodels-app-13f-filers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-13f-filers-api-openapi.yml
- filename: riskmodels-app-account-api-openapi.yml
  format: yaml
  label: riskmodels-app Account API
  slug: riskmodels-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-account-api-openapi.yml
- filename: riskmodels-app-authentication-api-openapi.yml
  format: yaml
  label: riskmodels-app Authentication API
  slug: riskmodels-app-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-authentication-api-openapi.yml
- filename: riskmodels-app-billing-api-openapi.yml
  format: yaml
  label: riskmodels-app Billing API
  slug: riskmodels-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-billing-api-openapi.yml
- filename: riskmodels-app-compliance-api-openapi.yml
  format: yaml
  label: riskmodels-app Compliance API
  slug: riskmodels-app-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-compliance-api-openapi.yml
- filename: riskmodels-app-deprecated-api-openapi.yml
  format: yaml
  label: riskmodels-app Deprecated API
  slug: riskmodels-app-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-deprecated-api-openapi.yml
- filename: riskmodels-app-discovery-api-openapi.yml
  format: yaml
  label: riskmodels-app Discovery API
  slug: riskmodels-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-discovery-api-openapi.yml
- filename: riskmodels-app-fundamentals-api-openapi.yml
  format: yaml
  label: riskmodels-app Fundamentals API
  slug: riskmodels-app-fundamentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-fundamentals-api-openapi.yml
- filename: riskmodels-app-funds-api-openapi.yml
  format: yaml
  label: riskmodels-app Funds API
  slug: riskmodels-app-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-funds-api-openapi.yml
- filename: riskmodels-app-funds-data-plane-api-openapi.yml
  format: yaml
  label: riskmodels-app Funds Data Plane API
  slug: riskmodels-app-funds-data-plane-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-funds-data-plane-api-openapi.yml
- filename: riskmodels-app-mcp-api-openapi.yml
  format: yaml
  label: riskmodels-app MCP API
  slug: riskmodels-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-mcp-api-openapi.yml
- filename: riskmodels-app-plaid-integration-api-openapi.yml
  format: yaml
  label: riskmodels-app Plaid Integration API
  slug: riskmodels-app-plaid-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-plaid-integration-api-openapi.yml
- filename: riskmodels-app-privacy-api-openapi.yml
  format: yaml
  label: riskmodels-app Privacy API
  slug: riskmodels-app-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-privacy-api-openapi.yml
- filename: riskmodels-app-risk-metrics-api-openapi.yml
  format: yaml
  label: riskmodels-app Risk Metrics API
  slug: riskmodels-app-risk-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-risk-metrics-api-openapi.yml
- filename: riskmodels-app-utility-api-openapi.yml
  format: yaml
  label: riskmodels-app Utility API
  slug: riskmodels-app-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-utility-api-openapi.yml
- filename: riskmodels-app-webhooks-api-openapi.yml
  format: yaml
  label: riskmodels-app Webhooks API
  slug: riskmodels-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskmodels-app/openapi/riskmodels-app-webhooks-api-openapi.yml
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
  - summary: Not investment advice
    text: Nothing on RiskModels should be treated as a recommendation to trade.
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
name: riskmodels-app
provenance_date: '2026-11-10'
provider_name: riskmodels-app
provider_slug: riskmodels-app
slug: riskmodels-app-eligibility
source_date: '2026-11-10'
source_filename: riskmodels-app-eligibility.yml
source_heading: Eligibility
source_page: https://riskmodels.app/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: riskmodels-app\naid: riskmodels-app\nurl: https://riskmodels.app/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not investment advice\n  text: Nothing on RiskModels should be treated as a recommendation to trade.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/riskmodels-app/eligibility/riskmodels-app-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from riskmodels-app's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Risk Management
- Analytics
- Equity
---

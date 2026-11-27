---
api_specs:
- filename: whoisgeni-us-account-api-openapi.yml
  format: yaml
  label: whoisgeni-us Account API
  slug: whoisgeni-us-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-account-api-openapi.yml
- filename: whoisgeni-us-analysis-api-openapi.yml
  format: yaml
  label: whoisgeni-us Analysis API
  slug: whoisgeni-us-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-analysis-api-openapi.yml
- filename: whoisgeni-us-authentication-api-openapi.yml
  format: yaml
  label: whoisgeni-us Authentication API
  slug: whoisgeni-us-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-authentication-api-openapi.yml
- filename: whoisgeni-us-billing-api-openapi.yml
  format: yaml
  label: whoisgeni-us Billing API
  slug: whoisgeni-us-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-billing-api-openapi.yml
- filename: whoisgeni-us-byok-api-openapi.yml
  format: yaml
  label: whoisgeni-us Byok API
  slug: whoisgeni-us-byok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-byok-api-openapi.yml
- filename: whoisgeni-us-correlation-api-openapi.yml
  format: yaml
  label: whoisgeni-us Correlation API
  slug: whoisgeni-us-correlation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-correlation-api-openapi.yml
- filename: whoisgeni-us-domains-api-openapi.yml
  format: yaml
  label: whoisgeni-us Domains API
  slug: whoisgeni-us-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-domains-api-openapi.yml
- filename: whoisgeni-us-entities-api-openapi.yml
  format: yaml
  label: whoisgeni-us Entities API
  slug: whoisgeni-us-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-entities-api-openapi.yml
- filename: whoisgeni-us-health-api-openapi.yml
  format: yaml
  label: whoisgeni-us Health API
  slug: whoisgeni-us-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-health-api-openapi.yml
- filename: whoisgeni-us-jobs-api-openapi.yml
  format: yaml
  label: whoisgeni-us Jobs API
  slug: whoisgeni-us-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-jobs-api-openapi.yml
- filename: whoisgeni-us-mcp-api-openapi.yml
  format: yaml
  label: whoisgeni-us MCP API
  slug: whoisgeni-us-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-mcp-api-openapi.yml
- filename: whoisgeni-us-schema-templates-api-openapi.yml
  format: yaml
  label: whoisgeni-us Schema Templates API
  slug: whoisgeni-us-schema-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-schema-templates-api-openapi.yml
- filename: whoisgeni-us-webhooks-api-openapi.yml
  format: yaml
  label: whoisgeni-us Webhooks API
  slug: whoisgeni-us-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-webhooks-api-openapi.yml
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
  - summary: Harassment or unauthorized surveillance
    text: You may not use the service to harass, stalk, or conduct unauthorized surveillance of individuals.
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
name: whoisgeni-us
provenance_date: '2026-11-10'
provider_name: whoisgeni-us
provider_slug: whoisgeni-us
slug: whoisgeni-us-eligibility
source_date: '2026-11-10'
source_filename: whoisgeni-us-eligibility.yml
source_heading: Eligibility
source_page: https://whoisgeni.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: whoisgeni-us\naid: whoisgeni-us\nurl: https://whoisgeni.us/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment or unauthorized surveillance\n  text: You may not use the service to harass, stalk, or conduct unauthorized surveillance of individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/whoisgeni-us/eligibility/whoisgeni-us-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from whoisgeni-us's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Domain Intelligence
- Security
- Compliance
- Data Enrichment
---

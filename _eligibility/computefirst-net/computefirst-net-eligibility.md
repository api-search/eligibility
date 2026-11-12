---
api_specs:
- filename: computefirst-net-account-api-openapi.yml
  format: yaml
  label: ComputeFirst Account API
  slug: computefirst-net-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-account-api-openapi.yml
- filename: computefirst-net-discovery-api-openapi.yml
  format: yaml
  label: ComputeFirst Discovery API
  slug: computefirst-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-discovery-api-openapi.yml
- filename: computefirst-net-execution-api-openapi.yml
  format: yaml
  label: ComputeFirst Execution API
  slug: computefirst-net-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-execution-api-openapi.yml
- filename: computefirst-net-feedback-api-openapi.yml
  format: yaml
  label: ComputeFirst Feedback API
  slug: computefirst-net-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-feedback-api-openapi.yml
- filename: computefirst-net-mcp-api-openapi.yml
  format: yaml
  label: ComputeFirst MCP API
  slug: computefirst-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-mcp-api-openapi.yml
- filename: computefirst-net-newsletter-api-openapi.yml
  format: yaml
  label: ComputeFirst Newsletter API
  slug: computefirst-net-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-newsletter-api-openapi.yml
- filename: computefirst-net-savings-api-openapi.yml
  format: yaml
  label: ComputeFirst Savings API
  slug: computefirst-net-savings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-savings-api-openapi.yml
- filename: computefirst-net-service-api-openapi.yml
  format: yaml
  label: ComputeFirst Service API
  slug: computefirst-net-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-service-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old. If you are under 18, you confirm that a parent or guardian agrees to your use of ComputeFirst.
    type: individual
  - text: If you use ComputeFirst for an organisation, you confirm that you may accept these terms for it, and "you" includes that organisation.
    type: business
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Illegal use
    text: submit anything illegal, or use the service for an illegal purpose or to infringe anyone's rights
  - summary: Sensitive data in inputs
    text: put sensitive data in inputs, such as health, genetic or biometric data, data about sex life, religion, political views or criminal records, government ID numbers, or payment card and bank account details
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
name: ComputeFirst
provenance_date: '2026-11-09'
provider_name: ComputeFirst
provider_slug: computefirst-net
slug: computefirst-net-eligibility
source_date: '2026-11-09'
source_filename: computefirst-net-eligibility.yml
source_heading: Eligibility
source_page: https://computefirst.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ComputeFirst\naid: computefirst-net\nurl: https://computefirst.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old. If you are under 18, you confirm that a parent or guardian agrees to\n    your use of ComputeFirst.\n- type: business\n  text: If you use ComputeFirst for an organisation, you confirm that you may accept these terms for it, and \"you\"\n    includes that organisation.\nrestricted_uses:\n- summary: Illegal use\n  text: submit anything illegal, or use the service for an illegal purpose\
  \ or to infringe anyone's rights\n- summary: Sensitive data in inputs\n  text: put sensitive data in inputs, such as health, genetic or biometric data, data about sex life, religion,\n    political views or criminal records, government ID numbers, or payment card and bank account details\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/computefirst-net/eligibility/computefirst-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ComputeFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- Developer Tools
- Data Transformation
- CSV
- JSON
- Deterministic Tools
---

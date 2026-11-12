---
api_specs:
- filename: corroborateme-com-agents-api-openapi.yml
  format: yaml
  label: CorroborateMe Agents API
  slug: corroborateme-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-agents-api-openapi.yml
- filename: corroborateme-com-billing-api-openapi.yml
  format: yaml
  label: CorroborateMe Billing API
  slug: corroborateme-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-billing-api-openapi.yml
- filename: corroborateme-com-companies-api-openapi.yml
  format: yaml
  label: CorroborateMe Companies API
  slug: corroborateme-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-companies-api-openapi.yml
- filename: corroborateme-com-console-auth-api-openapi.yml
  format: yaml
  label: CorroborateMe Console auth API
  slug: corroborateme-com-console-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-console-auth-api-openapi.yml
- filename: corroborateme-com-discovery-api-openapi.yml
  format: yaml
  label: CorroborateMe Discovery API
  slug: corroborateme-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-discovery-api-openapi.yml
- filename: corroborateme-com-integrations-api-openapi.yml
  format: yaml
  label: CorroborateMe Integrations API
  slug: corroborateme-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-integrations-api-openapi.yml
- filename: corroborateme-com-login-link-idp-api-openapi.yml
  format: yaml
  label: CorroborateMe Login-link IdP API
  slug: corroborateme-com-login-link-idp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-login-link-idp-api-openapi.yml
- filename: corroborateme-com-login-links-api-openapi.yml
  format: yaml
  label: CorroborateMe Login links API
  slug: corroborateme-com-login-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-login-links-api-openapi.yml
- filename: corroborateme-com-mcp-api-openapi.yml
  format: yaml
  label: CorroborateMe MCP API
  slug: corroborateme-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-mcp-api-openapi.yml
- filename: corroborateme-com-oidc-api-openapi.yml
  format: yaml
  label: CorroborateMe OIDC API
  slug: corroborateme-com-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-oidc-api-openapi.yml
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
  - summary: Unlawful or abusive use
    text: Use the Service only for lawful purposes.
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
name: CorroborateMe
provenance_date: '2026-11-09'
provider_name: CorroborateMe
provider_slug: corroborateme-com
slug: corroborateme-com-eligibility
source_date: '2026-11-09'
source_filename: corroborateme-com-eligibility.yml
source_heading: Eligibility
source_page: https://corroborateme.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CorroborateMe\naid: corroborateme-com\nurl: https://corroborateme.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corroborateme-com/eligibility/corroborateme-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CorroborateMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Authentication
- Identity
- Sign-In
- Passkeys
- OIDC
- Single Sign-On
- AI Agents
- MCP
---

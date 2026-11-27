---
api_specs:
- filename: tesser-accounts-api-openapi.yml
  format: yaml
  label: Tesser Accounts API
  slug: tesser-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-accounts-api-openapi.yml
- filename: tesser-admin-api-openapi.yml
  format: yaml
  label: Tesser Admin API
  slug: tesser-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-admin-api-openapi.yml
- filename: tesser-api-keys-api-openapi.yml
  format: yaml
  label: Tesser API Keys API
  slug: tesser-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-api-keys-api-openapi.yml
- filename: tesser-counterparties-api-openapi.yml
  format: yaml
  label: Tesser Counterparties API
  slug: tesser-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-counterparties-api-openapi.yml
- filename: tesser-currencies-api-openapi.yml
  format: yaml
  label: Tesser Currencies API
  slug: tesser-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-currencies-api-openapi.yml
- filename: tesser-health-api-openapi.yml
  format: yaml
  label: Tesser Health API
  slug: tesser-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-health-api-openapi.yml
- filename: tesser-mcp-api-openapi.yml
  format: yaml
  label: Tesser MCP API
  slug: tesser-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-mcp-api-openapi.yml
- filename: tesser-networks-api-openapi.yml
  format: yaml
  label: Tesser Networks API
  slug: tesser-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-networks-api-openapi.yml
- filename: tesser-organizations-api-openapi.yml
  format: yaml
  label: Tesser Organizations API
  slug: tesser-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-organizations-api-openapi.yml
- filename: tesser-payments-api-openapi.yml
  format: yaml
  label: Tesser Payments API
  slug: tesser-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-payments-api-openapi.yml
- filename: tesser-tenants-api-openapi.yml
  format: yaml
  label: Tesser Tenants API
  slug: tesser-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-tenants-api-openapi.yml
- filename: tesser-treasury-api-openapi.yml
  format: yaml
  label: Tesser Treasury API
  slug: tesser-treasury-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-treasury-api-openapi.yml
- filename: tesser-users-api-openapi.yml
  format: yaml
  label: Tesser Users API
  slug: tesser-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-users-api-openapi.yml
- filename: tesser-webhooks-api-openapi.yml
  format: yaml
  label: Tesser Webhooks API
  slug: tesser-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tesser/openapi/tesser-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" means the entity identified on an Order Form that incorporates this Agreement by reference.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and AML restrictions
    text: 'Customer shall not permit any End User to use the Services: (a) in violation of any applicable AML and International Trade Laws'
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
name: Tesser
provenance_date: '2026-11-10'
provider_name: Tesser
provider_slug: tesser
slug: tesser-eligibility
source_date: '2026-11-10'
source_filename: tesser-eligibility.yml
source_heading: Eligibility
source_page: https://tesser.xyz/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tesser\naid: tesser\nurl: https://tesser.xyz/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Customer\" means the entity identified on an Order Form that incorporates this Agreement by reference.'\nrestricted_uses:\n- summary: Sanctions and AML restrictions\n  text: 'Customer shall not permit any End User to use the Services: (a) in violation of any applicable AML and\n    International Trade Laws'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/tesser/eligibility/tesser-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tesser's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Stablecoins
- Cross-Border Payments
- Fintech
- Treasury
- Banking
- Blockchain
- Compliance
- MCP
- Developer Platform
---

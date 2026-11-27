---
api_specs:
- filename: apisign-io-api-keys-api-openapi.yml
  format: yaml
  label: APISign API Keys API
  slug: apisign-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-api-keys-api-openapi.yml
- filename: apisign-io-contracts-api-openapi.yml
  format: yaml
  label: APISign Contracts API
  slug: apisign-io-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-contracts-api-openapi.yml
- filename: apisign-io-health-api-openapi.yml
  format: yaml
  label: APISign Health API
  slug: apisign-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-health-api-openapi.yml
- filename: apisign-io-organization-api-openapi.yml
  format: yaml
  label: APISign Organization API
  slug: apisign-io-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-organization-api-openapi.yml
- filename: apisign-io-templates-api-openapi.yml
  format: yaml
  label: APISign Templates API
  slug: apisign-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-templates-api-openapi.yml
- filename: apisign-io-webhooks-api-openapi.yml
  format: yaml
  label: APISign Webhooks API
  slug: apisign-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use certain features of the Service, you must register for an account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: 'You agree not to use the Service to: Violate any applicable laws or regulations'
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
name: APISign
provenance_date: '2026-11-09'
provider_name: APISign
provider_slug: apisign-io
slug: apisign-io-eligibility
source_date: '2026-11-09'
source_filename: apisign-io-eligibility.yml
source_heading: Eligibility
source_page: https://apisign.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APISign\naid: apisign-io\nurl: https://apisign.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use certain features of the Service, you must register for an account.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: 'You agree not to use the Service to: Violate any applicable laws or regulations'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apisign-io/eligibility/apisign-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from APISign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Artificial Intelligence
- MCP
- Contracts
- Developer Platform
---

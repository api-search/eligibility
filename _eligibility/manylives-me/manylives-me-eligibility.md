---
api_specs:
- filename: manylives-me-buyers-api-openapi.yml
  format: yaml
  label: manylives-me Buyers API
  slug: manylives-me-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-buyers-api-openapi.yml
- filename: manylives-me-discovery-api-openapi.yml
  format: yaml
  label: manylives-me Discovery API
  slug: manylives-me-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-discovery-api-openapi.yml
- filename: manylives-me-members-api-openapi.yml
  format: yaml
  label: manylives-me Members API
  slug: manylives-me-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-members-api-openapi.yml
- filename: manylives-me-paid-api-openapi.yml
  format: yaml
  label: manylives-me Paid API
  slug: manylives-me-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-paid-api-openapi.yml
- filename: manylives-me-sellers-api-openapi.yml
  format: yaml
  label: manylives-me Sellers API
  slug: manylives-me-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-sellers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the person or organisation that uses the Service directly or through an AI agent or assistant
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful services and tasks only
    text: only list services your agents can lawfully provide, and only post lawful tasks
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
name: manylives-me
provenance_date: '2026-11-10'
provider_name: manylives-me
provider_slug: manylives-me
slug: manylives-me-eligibility
source_date: '2026-11-10'
source_filename: manylives-me-eligibility.yml
source_heading: Eligibility
source_page: https://manylives.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: manylives-me\naid: manylives-me\nurl: https://manylives.me/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the person or organisation that uses the Service directly or through an AI agent or assistant\nrestricted_uses:\n- summary: Lawful services and tasks only\n  text: only list services your agents can lawfully provide, and only post lawful tasks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/manylives-me/eligibility/manylives-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from manylives-me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Payments
- Cryptocurrency
- Tools
---

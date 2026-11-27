---
api_specs:
- filename: targetwise-ai-account-api-openapi.yml
  format: yaml
  label: targetwise-ai Account API
  slug: targetwise-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-account-api-openapi.yml
- filename: targetwise-ai-autocomplete-api-openapi.yml
  format: yaml
  label: targetwise-ai Autocomplete API
  slug: targetwise-ai-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-autocomplete-api-openapi.yml
- filename: targetwise-ai-companies-api-openapi.yml
  format: yaml
  label: targetwise-ai Companies API
  slug: targetwise-ai-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-companies-api-openapi.yml
- filename: targetwise-ai-employees-api-openapi.yml
  format: yaml
  label: targetwise-ai Employees API
  slug: targetwise-ai-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-employees-api-openapi.yml
- filename: targetwise-ai-enrichment-api-openapi.yml
  format: yaml
  label: targetwise-ai Enrichment API
  slug: targetwise-ai-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-enrichment-api-openapi.yml
- filename: targetwise-ai-prospecting-api-openapi.yml
  format: yaml
  label: targetwise-ai Prospecting API
  slug: targetwise-ai-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-prospecting-api-openapi.yml
- filename: targetwise-ai-resolution-api-openapi.yml
  format: yaml
  label: targetwise-ai Resolution API
  slug: targetwise-ai-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-resolution-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is offered for business purposes, not personal or household use.
    type: business
  minimum_age:
    text: You must be at least 18 and have authority to bind that business.
    value: '18'
  restricted_uses:
  - summary: consumer reports and credit/insurance/housing/employment decisions
    text: Do not use the data as a consumer report or for decisions about consumer credit, insurance, housing or employment eligibility.
  - summary: children and sensitive data
    text: Do not submit special-category data, criminal-offence records, passwords, financial-account credentials or unnecessary identity documents.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require reasonable verification to protect accounts and prevent misuse.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: targetwise-ai
provenance_date: '2026-11-10'
provider_name: targetwise-ai
provider_slug: targetwise-ai
slug: targetwise-ai-eligibility
source_date: '2026-11-10'
source_filename: targetwise-ai-eligibility.yml
source_heading: Eligibility
source_page: https://targetwise.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: targetwise-ai\naid: targetwise-ai\nurl: https://targetwise.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is offered for business purposes, not personal or household use.\nrestricted_uses:\n- summary: consumer reports and credit/insurance/housing/employment decisions\n  text: Do not use the data as a consumer report or for decisions about consumer credit, insurance, housing or employment\n    eligibility.\n- summary: children and sensitive data\n  text: Do not submit special-category data, criminal-offence\
  \ records, passwords, financial-account credentials\n    or unnecessary identity documents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require reasonable verification to protect accounts and prevent misuse.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and have authority to bind that business.\n"
source_yaml_url: https://artifacts.apis.io/targetwise-ai/eligibility/targetwise-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from targetwise-ai's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Data Enrichment
- MCP
- Software-as-a-Service
---

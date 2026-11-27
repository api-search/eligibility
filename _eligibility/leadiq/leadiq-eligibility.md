---
api_specs:
- filename: leadiq-account-api-openapi.yml
  format: yaml
  label: LeadIQ Account API
  slug: leadiq-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-account-api-openapi.yml
- filename: leadiq-lists-api-openapi.yml
  format: yaml
  label: LeadIQ Lists API
  slug: leadiq-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-lists-api-openapi.yml
- filename: leadiq-prospects-api-openapi.yml
  format: yaml
  label: LeadIQ Prospects API
  slug: leadiq-prospects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-prospects-api-openapi.yml
- filename: leadiq-company-lists-api-openapi.yml
  format: yaml
  label: LeadIQ Company Lists API
  slug: leadiq-company-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-company-lists-api-openapi.yml
- filename: leadiq-salesforce-api-openapi.yml
  format: yaml
  label: LeadIQ Salesforce API
  slug: leadiq-salesforce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-salesforce-api-openapi.yml
- filename: leadiq-graph-ql-api-openapi.yml
  format: yaml
  label: LeadIQ Graph QL API
  slug: leadiq-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-graph-ql-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual accepting the Terms on behalf of a company
    type: individual
  - text: solely for your internal business purpose
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Business-to-business sales and CRM use only
    text: use the Services for any purposes other than your own internal business to business sales, marketing, or customer relationship management
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
name: LeadIQ
provenance_date: '2026-11-09'
provider_name: LeadIQ
provider_slug: leadiq
slug: leadiq-eligibility
source_date: '2026-11-09'
source_filename: leadiq-eligibility.yml
source_heading: Eligibility
source_page: https://leadiq.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeadIQ\naid: leadiq\nurl: https://leadiq.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual accepting the Terms on behalf of a company\n- type: business\n  text: solely for your internal business purpose\nrestricted_uses:\n- summary: Business-to-business sales and CRM use only\n  text: use the Services for any purposes other than your own internal business to business sales, marketing, or\n    customer relationship management\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/leadiq/eligibility/leadiq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LeadIQ's own page on 2026-11-09.
synthetic: false
tags:
- Sales Intelligence
- B2B Data
- Contact Data
- Lead Generation
- Prospecting
- CRM Enrichment
- Sales Engagement
- GraphQL
- MCP
- Revenue Operations
- Go-To-Market
- Data Enrichment
---

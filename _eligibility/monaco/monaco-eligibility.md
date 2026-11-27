---
api_specs:
- filename: monaco-accounts-api-openapi.yml
  format: yaml
  label: Monaco Accounts API
  slug: monaco-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-accounts-api-openapi.yml
- filename: monaco-audiences-api-openapi.yml
  format: yaml
  label: Monaco Audiences API
  slug: monaco-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-audiences-api-openapi.yml
- filename: monaco-auth-api-openapi.yml
  format: yaml
  label: Monaco Auth API
  slug: monaco-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-auth-api-openapi.yml
- filename: monaco-campaigns-api-openapi.yml
  format: yaml
  label: Monaco Campaigns API
  slug: monaco-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-campaigns-api-openapi.yml
- filename: monaco-contacts-api-openapi.yml
  format: yaml
  label: Monaco Contacts API
  slug: monaco-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-contacts-api-openapi.yml
- filename: monaco-meetings-api-openapi.yml
  format: yaml
  label: Monaco Meetings API
  slug: monaco-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-meetings-api-openapi.yml
- filename: monaco-opportunities-api-openapi.yml
  format: yaml
  label: Monaco Opportunities API
  slug: monaco-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-opportunities-api-openapi.yml
- filename: monaco-schemas-api-openapi.yml
  format: yaml
  label: Monaco Schemas API
  slug: monaco-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-schemas-api-openapi.yml
- filename: monaco-sequence-templates-api-openapi.yml
  format: yaml
  label: Monaco Sequence Templates API
  slug: monaco-sequence-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-sequence-templates-api-openapi.yml
- filename: monaco-sequences-api-openapi.yml
  format: yaml
  label: Monaco Sequences API
  slug: monaco-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-sequences-api-openapi.yml
- filename: monaco-tags-api-openapi.yml
  format: yaml
  label: Monaco Tags API
  slug: monaco-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-tags-api-openapi.yml
- filename: monaco-tasks-api-openapi.yml
  format: yaml
  label: Monaco Tasks API
  slug: monaco-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-tasks-api-openapi.yml
- filename: monaco-users-api-openapi.yml
  format: yaml
  label: Monaco Users API
  slug: monaco-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monaco/openapi/monaco-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer identified in the applicable Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-prohibited uses
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications
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
name: Monaco
provenance_date: '2026-11-10'
provider_name: Monaco
provider_slug: monaco
slug: monaco-eligibility
source_date: '2026-11-10'
source_filename: monaco-eligibility.yml
source_heading: Eligibility
source_page: https://www.monaco.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monaco\naid: monaco\nurl: https://www.monaco.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer identified in the applicable Order Form\nrestricted_uses:\n- summary: Export-prohibited uses\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/monaco/eligibility/monaco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Monaco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- Sales
- Revenue Operations
- Artificial Intelligence
- Contacts
- Account
- Opportunities
- Pipelines
- Go-To-Market
- MCP
- Campaigns
- Audiences
- Sales Engagement
- Agents
- A2A
---

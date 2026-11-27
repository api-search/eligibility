---
api_specs:
- filename: govly-awards-api-openapi.yml
  format: yaml
  label: Govly Awards API
  slug: govly-awards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-awards-api-openapi.yml
- filename: govly-documents-api-openapi.yml
  format: yaml
  label: Govly Documents API
  slug: govly-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-documents-api-openapi.yml
- filename: govly-follows-api-openapi.yml
  format: yaml
  label: Govly Follows API
  slug: govly-follows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-follows-api-openapi.yml
- filename: govly-inbox-api-openapi.yml
  format: yaml
  label: Govly Inbox API
  slug: govly-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-inbox-api-openapi.yml
- filename: govly-opportunities-api-openapi.yml
  format: yaml
  label: Govly Opportunities API
  slug: govly-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-opportunities-api-openapi.yml
- filename: govly-quote-submissions-api-openapi.yml
  format: yaml
  label: Govly Quote Submissions API
  slug: govly-quote-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-quote-submissions-api-openapi.yml
- filename: govly-saved-searches-api-openapi.yml
  format: yaml
  label: Govly Saved Searches API
  slug: govly-saved-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-saved-searches-api-openapi.yml
- filename: govly-workspace-attachments-api-openapi.yml
  format: yaml
  label: Govly Workspace Attachments API
  slug: govly-workspace-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-workspace-attachments-api-openapi.yml
- filename: govly-workspace-comments-api-openapi.yml
  format: yaml
  label: Govly Workspace Comments API
  slug: govly-workspace-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-workspace-comments-api-openapi.yml
- filename: govly-workspace-members-api-openapi.yml
  format: yaml
  label: Govly Workspace Members API
  slug: govly-workspace-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-workspace-members-api-openapi.yml
- filename: govly-workspaces-api-openapi.yml
  format: yaml
  label: Govly Workspaces API
  slug: govly-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-workspaces-api-openapi.yml
- filename: govly-contacts-api-openapi.yml
  format: yaml
  label: Govly Contacts API
  slug: govly-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-contacts-api-openapi.yml
- filename: govly-organization-labels-api-openapi.yml
  format: yaml
  label: Govly Organization Labels API
  slug: govly-organization-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-organization-labels-api-openapi.yml
- filename: govly-organization-users-api-openapi.yml
  format: yaml
  label: Govly Organization Users API
  slug: govly-organization-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-organization-users-api-openapi.yml
- filename: govly-places-api-openapi.yml
  format: yaml
  label: Govly Places API
  slug: govly-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-places-api-openapi.yml
- filename: govly-product-catalogs-api-openapi.yml
  format: yaml
  label: Govly Product Catalogs API
  slug: govly-product-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-product-catalogs-api-openapi.yml
- filename: govly-shares-api-openapi.yml
  format: yaml
  label: Govly Shares API
  slug: govly-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-shares-api-openapi.yml
- filename: govly-signals-api-openapi.yml
  format: yaml
  label: Govly Signals API
  slug: govly-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govly/openapi/govly-signals-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You represent and warrant that you are a US entity or US citizen
  entity_types:
  - text: companies, resellers, distributors, prime contractors, and subcontractors
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Competitor benefit
    text: use the Govly Service for the benefit of a Govly competitor or to compete with Govly
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
name: Govly
provenance_date: '2026-11-09'
provider_name: Govly
provider_slug: govly
slug: govly-eligibility
source_date: '2026-11-09'
source_filename: govly-eligibility.yml
source_heading: Eligibility
source_page: https://www.govly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Govly\naid: govly\nurl: https://www.govly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You represent and warrant that you are a US entity or US citizen\nentity_types:\n- type: business\n  text: companies, resellers, distributors, prime contractors, and subcontractors\nrestricted_uses:\n- summary: Competitor benefit\n  text: use the Govly Service for the benefit of a Govly competitor or to compete with Govly\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/govly/eligibility/govly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Govly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- Public Sector
- Procurement
- Government Contracting
- GovTech
- Market Intelligence
- Awards
- Opportunities
- Agents
---

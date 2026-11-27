---
api_specs:
- filename: corridor-dashboard-api-openapi.yml
  format: yaml
  label: Corridor Dashboard API
  slug: corridor-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-dashboard-api-openapi.yml
- filename: corridor-findings-api-openapi.yml
  format: yaml
  label: Corridor Findings API
  slug: corridor-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-findings-api-openapi.yml
- filename: corridor-guardrails-api-openapi.yml
  format: yaml
  label: Corridor Guardrails API
  slug: corridor-guardrails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-guardrails-api-openapi.yml
- filename: corridor-pr-reviews-api-openapi.yml
  format: yaml
  label: Corridor PR Reviews API
  slug: corridor-pr-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-pr-reviews-api-openapi.yml
- filename: corridor-projects-api-openapi.yml
  format: yaml
  label: Corridor Projects API
  slug: corridor-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-projects-api-openapi.yml
- filename: corridor-teams-api-openapi.yml
  format: yaml
  label: Corridor Teams API
  slug: corridor-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-teams-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be the Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive data submission
    text: Customer will not provide (or cause or permit to be provided) any Sensitive Data to Corridor for processing under the Agreement
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
name: Corridor
provenance_date: '2026-11-09'
provider_name: Corridor
provider_slug: corridor
slug: corridor-eligibility
source_date: '2026-11-09'
source_filename: corridor-eligibility.yml
source_heading: Eligibility
source_page: https://www.corridor.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corridor\naid: corridor\nurl: https://www.corridor.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be\n    the Customer.\nrestricted_uses:\n- summary: No sensitive data submission\n  text: Customer will not provide (or cause or permit to be provided) any Sensitive Data to Corridor for processing\n    under the Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corridor/eligibility/corridor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Corridor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Application Security
- AI Coding
- Code Security
- Developer Tools
- Guardrails
- MCP
- Static Analysis
- DevSecOps
---

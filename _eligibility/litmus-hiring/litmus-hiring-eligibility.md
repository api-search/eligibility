---
api_specs:
- filename: litmus-hiring-invites-api-openapi.yml
  format: yaml
  label: Litmus Hiring Invites API
  slug: litmus-hiring-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-invites-api-openapi.yml
- filename: litmus-hiring-roles-api-openapi.yml
  format: yaml
  label: Litmus Hiring Roles API
  slug: litmus-hiring-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-roles-api-openapi.yml
- filename: litmus-hiring-submissions-api-openapi.yml
  format: yaml
  label: Litmus Hiring Submissions API
  slug: litmus-hiring-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-submissions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Company customers are also subject to the full Litmus Terms of Service accepted through the platform or in an applicable order form.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or impersonated assessment responses
    text: Submit fraudulent, impersonated, or unauthorized assessment responses, including responses completed by another person
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
name: Litmus Hiring
provenance_date: '2026-11-09'
provider_name: Litmus Hiring
provider_slug: litmus-hiring
slug: litmus-hiring-eligibility
source_date: '2026-11-09'
source_filename: litmus-hiring-eligibility.yml
source_heading: Eligibility
source_page: https://litmushiring.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Litmus Hiring\naid: litmus-hiring\nurl: https://litmushiring.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Company customers are also subject to the full Litmus Terms of Service accepted through the platform or\n    in an applicable order form.\nrestricted_uses:\n- summary: Fraudulent or impersonated assessment responses\n  text: Submit fraudulent, impersonated, or unauthorized assessment responses, including responses completed by\n    another person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/litmus-hiring/eligibility/litmus-hiring-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Litmus Hiring's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hiring
- Recruiting
- Technical Assessment
- Developer Hiring
- MCP
- Interviewing
- Y Combinator
---

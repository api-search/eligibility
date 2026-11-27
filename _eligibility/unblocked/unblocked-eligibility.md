---
api_specs:
- filename: unblocked-answers-api-openapi.yml
  format: yaml
  label: Unblocked Answers API
  slug: unblocked-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unblocked/openapi/unblocked-answers-api-openapi.yml
- filename: unblocked-collections-api-openapi.yml
  format: yaml
  label: Unblocked Collections API
  slug: unblocked-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unblocked/openapi/unblocked-collections-api-openapi.yml
- filename: unblocked-documents-api-openapi.yml
  format: yaml
  label: Unblocked Documents API
  slug: unblocked-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unblocked/openapi/unblocked-documents-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to this agreement
    type: business
  minimum_age:
    text: you must have reached the legal age of majority in your jurisdiction of residence
    value: age of majority
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
name: Unblocked
provenance_date: '2026-11-10'
provider_name: Unblocked
provider_slug: unblocked
slug: unblocked-eligibility
source_date: '2026-11-10'
source_filename: unblocked-eligibility.yml
source_heading: Eligibility
source_page: https://getunblocked.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unblocked\naid: unblocked\nurl: https://getunblocked.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering this agreement on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to this agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you must have reached the legal age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/unblocked/eligibility/unblocked-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Unblocked's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Artificial Intelligence
- Developer Experience
- Knowledge Management
- Code Review
- MCP
- AI Agents
- Context Engineering
- Search
---

---
api_specs:
- filename: savee-boards-api-openapi.yml
  format: yaml
  label: Savee Boards API
  slug: savee-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-boards-api-openapi.yml
- filename: savee-saves-api-openapi.yml
  format: yaml
  label: Savee Saves API
  slug: savee-saves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-saves-api-openapi.yml
- filename: savee-search-api-openapi.yml
  format: yaml
  label: Savee Search API
  slug: savee-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-search-api-openapi.yml
- filename: savee-system-api-openapi.yml
  format: yaml
  label: Savee System API
  slug: savee-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-system-api-openapi.yml
- filename: savee-user-api-openapi.yml
  format: yaml
  label: Savee User API
  slug: savee-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts are personal and cannot be shared.
    type: individual
  minimum_age:
    text: You must be at least 13. If you are under 18, you need a parent or guardian's permission.
    value: '13'
  restricted_uses:
  - summary: Sanctions or export rule violations
    text: Use Savee in violation of applicable sanctions or export rules
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
name: Savee
provenance_date: '2026-11-10'
provider_name: Savee
provider_slug: savee
slug: savee-eligibility
source_date: '2026-11-10'
source_filename: savee-eligibility.yml
source_heading: Eligibility
source_page: https://savee.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Savee\naid: savee\nurl: https://savee.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Accounts are personal and cannot be shared.\nrestricted_uses:\n- summary: Sanctions or export rule violations\n  text: Use Savee in violation of applicable sanctions or export rules\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13. If you are under 18, you need a parent or guardian's permission.\n"
source_yaml_url: https://artifacts.apis.io/savee/eligibility/savee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Savee's own page on 2026-11-10.
synthetic: false
tags:
- Design
- visual inspiration
- Image
- Creative
- Moodboards
- Artificial Intelligence
---

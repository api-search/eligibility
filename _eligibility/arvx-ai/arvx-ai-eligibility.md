---
api_specs:
- filename: arvx-ai-readings-api-openapi.yml
  format: yaml
  label: ARVX Readings API
  slug: arvx-ai-readings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-readings-api-openapi.yml
- filename: arvx-ai-records-api-openapi.yml
  format: yaml
  label: ARVX Records API
  slug: arvx-ai-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-records-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be at least 18, located in the United States, and pay with a card issued in the United States.
  entity_types:
  - text: If you accept for a company, you confirm you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18, located in the United States
    value: '18'
  restricted_uses:
  - summary: Covered Decisions
    text: Make, support or inform any Covered Decision, whether a person or software makes it, in any industry.
  - summary: Employment decisions
    text: Make, support or inform any employment decision, including hiring, screening or ranking candidates
  - summary: Minors and non-US subjects
    text: Process Material about anyone under 18, or about anyone located outside the United States.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Before your first paid Reading you must pass an automated identity check.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ARVX
provenance_date: '2026-11-09'
provider_name: ARVX
provider_slug: arvx-ai
slug: arvx-ai-eligibility
source_date: '2026-11-09'
source_filename: arvx-ai-eligibility.yml
source_heading: Eligibility
source_page: https://developer.arvx.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ARVX\naid: arvx-ai\nurl: https://developer.arvx.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be at least 18, located in the United States, and pay with a card issued in the United States.\nentity_types:\n- type: business\n  text: If you accept for a company, you confirm you have authority to bind it.\nrestricted_uses:\n- summary: Covered Decisions\n  text: Make, support or inform any Covered Decision, whether a person or software makes it, in any industry.\n- summary: Employment decisions\n  text: Make, support or inform any employment decision, including\
  \ hiring, screening or ranking candidates\n- summary: Minors and non-US subjects\n  text: Process Material about anyone under 18, or about anyone located outside the United States.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Before your first paid Reading you must pass an automated identity check.\nminimum_age:\n  value: '18'\n  text: You must be at least 18, located in the United States\n"
source_yaml_url: https://artifacts.apis.io/arvx-ai/eligibility/arvx-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from ARVX's own page on 2026-11-09.
synthetic: false
tags:
- Company
---

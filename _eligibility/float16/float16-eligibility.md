---
api_specs:
- filename: float16-chat-api-openapi.yml
  format: yaml
  label: Float16 Chat API
  slug: float16-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/float16/openapi/float16-chat-api-openapi.yml
- filename: float16-fact-api-openapi.yml
  format: yaml
  label: Float16 Fact API
  slug: float16-fact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/float16/openapi/float16-fact-api-openapi.yml
- filename: float16-float16-api-api-openapi.yml
  format: yaml
  label: Float16 Float16 API
  slug: float16-float16-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/float16/openapi/float16-float16-api-api-openapi.yml
- filename: float16-ocr-api-openapi.yml
  format: yaml
  label: Float16 Ocr API
  slug: float16-ocr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/float16/openapi/float16-ocr-api-openapi.yml
- filename: float16-task-api-openapi.yml
  format: yaml
  label: Float16 Task API
  slug: float16-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/float16/openapi/float16-task-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated access must be pre-approved
    text: Automated access must be pre-approved
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
name: Float16
provenance_date: '2026-11-09'
provider_name: Float16
provider_slug: float16
slug: float16-eligibility
source_date: '2026-11-09'
source_filename: float16-eligibility.yml
source_heading: Eligibility
source_page: https://docs.float16.cloud/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Float16\naid: float16\nurl: https://docs.float16.cloud/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Automated access must be pre-approved\n  text: Automated access must be pre-approved\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/float16/eligibility/float16-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Float16's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- High Performance Computing
- Artificial Intelligence
---

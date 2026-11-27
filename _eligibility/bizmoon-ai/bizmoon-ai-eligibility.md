---
api_specs:
- filename: bizmoon-ai-read-api-openapi.yml
  format: yaml
  label: Bizmoon Read API
  slug: bizmoon-ai-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizmoon-ai/openapi/bizmoon-ai-read-api-openapi.yml
- filename: bizmoon-ai-write-api-openapi.yml
  format: yaml
  label: Bizmoon Write API
  slug: bizmoon-ai-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizmoon-ai/openapi/bizmoon-ai-write-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Use the service for any unlawful purpose or to violate any applicable law
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
name: Bizmoon
provenance_date: '2026-11-09'
provider_name: Bizmoon
provider_slug: bizmoon-ai
slug: bizmoon-ai-eligibility
source_date: '2026-11-09'
source_filename: bizmoon-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bizmoon.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bizmoon\naid: bizmoon-ai\nurl: https://bizmoon.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the service for any unlawful purpose or to violate any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizmoon-ai/eligibility/bizmoon-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Bizmoon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compliance
- Grants
- Small Business
---

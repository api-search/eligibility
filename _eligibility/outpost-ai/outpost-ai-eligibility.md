---
api_specs:
- filename: outpost-ai-oauth-api-openapi.yml
  format: yaml
  label: Outpost OAuth API
  slug: outpost-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-oauth-api-openapi.yml
- filename: outpost-ai-payments-api-openapi.yml
  format: yaml
  label: Outpost Payments API
  slug: outpost-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-payments-api-openapi.yml
- filename: outpost-ai-webhooks-api-openapi.yml
  format: yaml
  label: Outpost Webhooks API
  slug: outpost-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: These Terms govern the eFX payment and international transfer services provided by Outpost in Brazil.
  minimum_age:
    text: null
    value: null
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
name: Outpost
provenance_date: '2026-11-10'
provider_name: Outpost
provider_slug: outpost-ai
slug: outpost-ai-eligibility
source_date: '2026-11-10'
source_filename: outpost-ai-eligibility.yml
source_heading: Eligibility
source_page: https://outpost.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outpost\naid: outpost-ai\nurl: https://outpost.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: These Terms govern the eFX payment and international transfer services provided by Outpost in Brazil.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/outpost-ai/eligibility/outpost-ai-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Outpost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Tax
- Commerce
- Software-as-a-Service
---

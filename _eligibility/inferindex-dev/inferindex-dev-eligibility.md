---
api_specs:
- filename: inferindex-dev-mcp.json
  format: json
  label: InferIndex API
  slug: inferindex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inferindex-dev/openapi/inferindex-dev-mcp.json
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
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: 'An optional free account gives you an API key that raises your rate limit: you create the account with an email address and sign in with a link we email to you, or with your GitHub or Google account.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: inferindex-dev
provenance_date: '2026-11-09'
provider_name: inferindex-dev
provider_slug: inferindex-dev
slug: inferindex-dev-eligibility
source_date: '2026-11-09'
source_filename: inferindex-dev-eligibility.yml
source_heading: Eligibility
source_page: https://inferindex.dev/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: inferindex-dev\naid: inferindex-dev\nurl: https://inferindex.dev/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: 'An optional free account gives you an API key that raises your rate limit: you create the account with\n    an email address and sign in with a link we email to you, or with your GitHub or Google account.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inferindex-dev/eligibility/inferindex-dev-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from inferindex-dev's own page on 2026-11-09.
synthetic: false
tags:
- LLM
- Pricing
- Index
- Data
---

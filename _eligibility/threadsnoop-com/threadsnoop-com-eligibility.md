---
api_specs:
- filename: threadsnoop-com-account-api-openapi.yml
  format: yaml
  label: threadsnoop-com Account API
  slug: threadsnoop-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-account-api-openapi.yml
- filename: threadsnoop-com-comments-api-openapi.yml
  format: yaml
  label: threadsnoop-com Comments API
  slug: threadsnoop-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-comments-api-openapi.yml
- filename: threadsnoop-com-posts-api-openapi.yml
  format: yaml
  label: threadsnoop-com Posts API
  slug: threadsnoop-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-posts-api-openapi.yml
- filename: threadsnoop-com-subreddits-api-openapi.yml
  format: yaml
  label: threadsnoop-com Subreddits API
  slug: threadsnoop-com-subreddits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-subreddits-api-openapi.yml
- filename: threadsnoop-com-users-api-openapi.yml
  format: yaml
  label: threadsnoop-com Users API
  slug: threadsnoop-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: generally, be at least 18, or the age of majority where you live
    value: '18'
  restricted_uses:
  - summary: No harassment or profiling of private individuals
    text: Harass, dox, stalk, or build a profile on a specific private individual without a legitimate basis for doing so.
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
name: threadsnoop-com
provenance_date: '2026-11-10'
provider_name: threadsnoop-com
provider_slug: threadsnoop-com
slug: threadsnoop-com-eligibility
source_date: '2026-11-10'
source_filename: threadsnoop-com-eligibility.yml
source_heading: Eligibility
source_page: https://threadsnoop.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: threadsnoop-com\naid: threadsnoop-com\nurl: https://threadsnoop.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No harassment or profiling of private individuals\n  text: Harass, dox, stalk, or build a profile on a specific private individual without a legitimate basis for doing\n    so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: generally, be at least 18, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/threadsnoop-com/eligibility/threadsnoop-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from threadsnoop-com's own page on 2026-11-10.
synthetic: false
tags:
- Reddit
- Artificial Intelligence
- MCP
- Read Only
---

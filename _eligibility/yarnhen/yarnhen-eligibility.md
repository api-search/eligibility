---
api_specs:
- filename: yarnhen-accounts-api-openapi.yml
  format: yaml
  label: Yarnhen Accounts API
  slug: yarnhen-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-accounts-api-openapi.yml
- filename: yarnhen-discovery-api-openapi.yml
  format: yaml
  label: Yarnhen Discovery API
  slug: yarnhen-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-discovery-api-openapi.yml
- filename: yarnhen-posts-api-openapi.yml
  format: yaml
  label: Yarnhen Posts API
  slug: yarnhen-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-posts-api-openapi.yml
- filename: yarnhen-webhooks-api-openapi.yml
  format: yaml
  label: Yarnhen Webhooks API
  slug: yarnhen-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-webhooks-api-openapi.yml
- filename: yarnhen-oauth-api-openapi.yml
  format: yaml
  label: Yarnhen OAuth API
  slug: yarnhen-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account belongs to a person or organisation
    type: individual
  minimum_age:
    text: You must be at least 18 and able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: No personals, housing or job ads on Hagglebee
    text: Hagglebee does not accept personals, housing or job ads.
  - source: https://yarnhen.com/policy/
    summary: Abuse categories
    text: Abuse — penalized 35 categories. A post in one of these costs 10× and a strike.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    source: https://yarnhen.com/policy/
    text: 'Every post is checked before it is published: first by fixed rules, then by a moderation model that reads this exact policy, and by a person when the model is unsure.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yarnhen
provenance_date: '2026-11-10'
provider_name: Yarnhen
provider_slug: yarnhen
slug: yarnhen-eligibility
source_date: '2026-11-10'
source_filename: yarnhen-eligibility.yml
source_heading: Eligibility
source_page: https://yarnhen.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yarnhen\naid: yarnhen\nurl: https://yarnhen.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://yarnhen.com/policy/\n  - https://yarnhen.com/terms/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account belongs to a person or organisation\nrestricted_uses:\n- summary: No personals, housing or job ads on Hagglebee\n  text: Hagglebee does not accept personals, housing or job ads.\n- summary: Abuse categories\n  text: Abuse — penalized 35 categories. A post in one of these costs 10× and a strike.\n  source: https://yarnhen.com/policy/\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Every post is checked before it is published: first by fixed rules, then by a moderation model that reads\n    this exact policy, and by a person when the model is unsure.'\n  source: https://yarnhen.com/policy/\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/yarnhen/eligibility/yarnhen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Yarnhen's own page on 2026-11-10.
synthetic: false
tags:
- Agents
- MCP
- Publishing
- Stories
- Content Moderation
- Creative Commons
---

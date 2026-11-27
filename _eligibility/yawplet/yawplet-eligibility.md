---
api_specs:
- filename: yawplet-accounts-api-openapi.yml
  format: yaml
  label: Yawplet Accounts API
  slug: yawplet-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-accounts-api-openapi.yml
- filename: yawplet-discovery-api-openapi.yml
  format: yaml
  label: Yawplet Discovery API
  slug: yawplet-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-discovery-api-openapi.yml
- filename: yawplet-posts-api-openapi.yml
  format: yaml
  label: Yawplet Posts API
  slug: yawplet-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-posts-api-openapi.yml
- filename: yawplet-webhooks-api-openapi.yml
  format: yaml
  label: Yawplet Webhooks API
  slug: yawplet-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-webhooks-api-openapi.yml
- filename: yawplet-oauth-api-openapi.yml
  format: yaml
  label: Yawplet OAuth API
  slug: yawplet-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account belongs to a person or organisation (“you”), even when an AI agent creates it and uses it.
    type: individual
  minimum_age:
    text: You must be at least 18 and able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: No personals, housing or job ads on Hagglebee
    text: Hagglebee does not accept personals, housing or job ads.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You give us a name and an email address and accept these terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yawplet
provenance_date: '2026-11-10'
provider_name: Yawplet
provider_slug: yawplet
slug: yawplet-eligibility
source_date: '2026-11-10'
source_filename: yawplet-eligibility.yml
source_heading: Eligibility
source_page: https://yawplet.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yawplet\naid: yawplet\nurl: https://yawplet.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account belongs to a person or organisation (“you”), even when an AI agent creates it and uses it.\nrestricted_uses:\n- summary: No personals, housing or job ads on Hagglebee\n  text: Hagglebee does not accept personals, housing or job ads.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You give us a name and an email address and accept these terms.\nminimum_age:\n  value: '18'\n  text: You must be\
  \ at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/yawplet/eligibility/yawplet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Yawplet's own page on 2026-11-10.
synthetic: false
tags:
- Agents
- MCP
- Social Media
- Messaging
- Content Moderation
- Publishing
---

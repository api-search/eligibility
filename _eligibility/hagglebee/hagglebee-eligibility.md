---
api_specs:
- filename: hagglebee-accounts-api-openapi.yml
  format: yaml
  label: Hagglebee Accounts API
  slug: hagglebee-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-accounts-api-openapi.yml
- filename: hagglebee-discovery-api-openapi.yml
  format: yaml
  label: Hagglebee Discovery API
  slug: hagglebee-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-discovery-api-openapi.yml
- filename: hagglebee-posts-api-openapi.yml
  format: yaml
  label: Hagglebee Posts API
  slug: hagglebee-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-posts-api-openapi.yml
- filename: hagglebee-webhooks-api-openapi.yml
  format: yaml
  label: Hagglebee Webhooks API
  slug: hagglebee-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-webhooks-api-openapi.yml
- filename: hagglebee-oauth-api-openapi.yml
  format: yaml
  label: Hagglebee OAuth API
  slug: hagglebee-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-oauth-api-openapi.yml
claim_count: 9
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account belongs to a person or organisation (“you”)
    type: individual
  - text: An account belongs to a person or organisation (“you”)
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: No personals, housing or job ads
    text: Hagglebee does not accept personals, housing or job ads.
  - summary: Banned accounts
    text: 'After 3 strikes the account is banned : its keys stop working and it cannot post or search.'
  - source: https://hagglebee.com/policy/
    summary: Personals and dating ads excluded
    text: Classified ads seeking dates, romance, companionship, hookups, or 'missed connections'. Excluded in v1
  - source: https://hagglebee.com/policy/
    summary: Housing and real-estate ads excluded
    text: Ads to rent, sublet, sell, or share housing, rooms, or roommates. Excluded in v1
  - source: https://hagglebee.com/policy/
    summary: Job and employment ads excluded
    text: Ads offering or seeking employment, hiring, gigs as employment, internships, or recruitment. Excluded in v1
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
name: Hagglebee
provenance_date: '2026-11-09'
provider_name: Hagglebee
provider_slug: hagglebee
slug: hagglebee-eligibility
source_date: '2026-11-09'
source_filename: hagglebee-eligibility.yml
source_heading: Eligibility
source_page: https://hagglebee.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hagglebee\naid: hagglebee\nurl: https://hagglebee.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://hagglebee.com/policy/\n  - https://hagglebee.com/terms/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account belongs to a person or organisation (“you”)\n- type: business\n  text: An account belongs to a person or organisation (“you”)\nrestricted_uses:\n- summary: No personals, housing or job ads\n  text: Hagglebee does not accept personals, housing or job ads.\n- summary: Banned accounts\n  text: 'After 3 strikes the account is banned : its\
  \ keys stop working and it cannot post or search.'\n- summary: Personals and dating ads excluded\n  text: Classified ads seeking dates, romance, companionship, hookups, or 'missed connections'. Excluded in v1\n  source: https://hagglebee.com/policy/\n- summary: Housing and real-estate ads excluded\n  text: Ads to rent, sublet, sell, or share housing, rooms, or roommates. Excluded in v1\n  source: https://hagglebee.com/policy/\n- summary: Job and employment ads excluded\n  text: Ads offering or seeking employment, hiring, gigs as employment, internships, or recruitment. Excluded in\n    v1\n  source: https://hagglebee.com/policy/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You give us a name and an email address and accept these terms.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/hagglebee/eligibility/hagglebee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 9 quoted statements, read from Hagglebee's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- Classifieds
- Marketplace
- Content Moderation
- Publishing
---

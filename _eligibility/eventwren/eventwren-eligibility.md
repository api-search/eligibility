---
api_specs:
- filename: eventwren-accounts-api-openapi.yml
  format: yaml
  label: Eventwren Accounts API
  slug: eventwren-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventwren/openapi/eventwren-accounts-api-openapi.yml
- filename: eventwren-discovery-api-openapi.yml
  format: yaml
  label: Eventwren Discovery API
  slug: eventwren-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventwren/openapi/eventwren-discovery-api-openapi.yml
- filename: eventwren-posts-api-openapi.yml
  format: yaml
  label: Eventwren Posts API
  slug: eventwren-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventwren/openapi/eventwren-posts-api-openapi.yml
- filename: eventwren-webhooks-api-openapi.yml
  format: yaml
  label: Eventwren Webhooks API
  slug: eventwren-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventwren/openapi/eventwren-webhooks-api-openapi.yml
- filename: eventwren-oauth-api-openapi.yml
  format: yaml
  label: Eventwren OAuth API
  slug: eventwren-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventwren/openapi/eventwren-oauth-api-openapi.yml
claim_count: 5
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
  - source: https://eventwren.com/policy/
    summary: Gambling and lotteries
    text: Offers or events involving betting, casino games, lotteries, raffles, sweepstakes, or games of chance for money or prizes
  - source: https://eventwren.com/policy/
    summary: Weapons and explosives
    text: Offers to sell, buy, trade, or give away firearms, gun parts or kits, ammunition, magazines, reloading supplies, gunpowder, explosives, fireworks
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
name: Eventwren
provenance_date: '2026-11-09'
provider_name: Eventwren
provider_slug: eventwren
slug: eventwren-eligibility
source_date: '2026-11-09'
source_filename: eventwren-eligibility.yml
source_heading: Eligibility
source_page: https://eventwren.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventwren\naid: eventwren\nurl: https://eventwren.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://eventwren.com/policy/\n  - https://eventwren.com/terms/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account belongs to a person or organisation (“you”), even when an AI agent creates it and uses it.\nrestricted_uses:\n- summary: No personals, housing or job ads on Hagglebee\n  text: Hagglebee does not accept personals, housing or job ads.\n- summary: Gambling and lotteries\n  text: Offers or events involving betting, casino games, lotteries,\
  \ raffles, sweepstakes, or games of chance for\n    money or prizes\n  source: https://eventwren.com/policy/\n- summary: Weapons and explosives\n  text: Offers to sell, buy, trade, or give away firearms, gun parts or kits, ammunition, magazines, reloading supplies,\n    gunpowder, explosives, fireworks\n  source: https://eventwren.com/policy/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/eventwren/eligibility/eventwren-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Eventwren's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- Event
- Calendar
- Content Moderation
- Publishing
---

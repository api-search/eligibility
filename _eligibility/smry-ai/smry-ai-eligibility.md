---
api_specs:
- filename: smry-ai-account-api-openapi.yml
  format: yaml
  label: smry-ai Account API
  slug: smry-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-account-api-openapi.yml
- filename: smry-ai-articles-api-openapi.yml
  format: yaml
  label: smry-ai Articles API
  slug: smry-ai-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-articles-api-openapi.yml
- filename: smry-ai-collections-api-openapi.yml
  format: yaml
  label: smry-ai Collections API
  slug: smry-ai-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-collections-api-openapi.yml
- filename: smry-ai-consumers-api-openapi.yml
  format: yaml
  label: smry-ai Consumers API
  slug: smry-ai-consumers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-consumers-api-openapi.yml
- filename: smry-ai-feeds-api-openapi.yml
  format: yaml
  label: smry-ai Feeds API
  slug: smry-ai-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-feeds-api-openapi.yml
- filename: smry-ai-library-api-openapi.yml
  format: yaml
  label: smry-ai Library API
  slug: smry-ai-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-library-api-openapi.yml
- filename: smry-ai-monitors-api-openapi.yml
  format: yaml
  label: smry-ai Monitors API
  slug: smry-ai-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-monitors-api-openapi.yml
- filename: smry-ai-public-reading-api-openapi.yml
  format: yaml
  label: smry-ai Public reading API
  slug: smry-ai-public-reading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-public-reading-api-openapi.yml
- filename: smry-ai-scouting-api-openapi.yml
  format: yaml
  label: smry-ai Scouting API
  slug: smry-ai-scouting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smry-ai/openapi/smry-ai-scouting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Unauthorized automated access
    text: Use unauthorized bots, scraping, or automated means to access the Service, harvest information, or create accounts
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
name: smry-ai
provenance_date: '2026-11-10'
provider_name: smry-ai
provider_slug: smry-ai
slug: smry-ai-eligibility
source_date: '2026-11-10'
source_filename: smry-ai-eligibility.yml
source_heading: Eligibility
source_page: https://smry.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: smry-ai\naid: smry-ai\nurl: https://smry.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service.\nrestricted_uses:\n- summary: Unauthorized automated access\n  text: Use unauthorized bots, scraping, or automated means to access the Service, harvest information, or create\n    accounts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/smry-ai/eligibility/smry-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from smry-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- News
- RSS
- Summarization
- Productivity
---

---
api_specs:
- filename: itsgloria-ai-api-keys-api-openapi.yml
  format: yaml
  label: Gloria API Keys API
  slug: itsgloria-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-api-keys-api-openapi.yml
- filename: itsgloria-ai-articles-api-openapi.yml
  format: yaml
  label: Gloria Articles API
  slug: itsgloria-ai-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-articles-api-openapi.yml
- filename: itsgloria-ai-authentication-api-openapi.yml
  format: yaml
  label: Gloria Authentication API
  slug: itsgloria-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-authentication-api-openapi.yml
- filename: itsgloria-ai-bots-api-openapi.yml
  format: yaml
  label: Gloria Bots API
  slug: itsgloria-ai-bots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-bots-api-openapi.yml
- filename: itsgloria-ai-categories-api-openapi.yml
  format: yaml
  label: Gloria Categories API
  slug: itsgloria-ai-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-categories-api-openapi.yml
- filename: itsgloria-ai-health-api-openapi.yml
  format: yaml
  label: Gloria Health API
  slug: itsgloria-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-health-api-openapi.yml
- filename: itsgloria-ai-narratives-api-openapi.yml
  format: yaml
  label: Gloria Narratives API
  slug: itsgloria-ai-narratives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-narratives-api-openapi.yml
- filename: itsgloria-ai-news-api-openapi.yml
  format: yaml
  label: Gloria News API
  slug: itsgloria-ai-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-news-api-openapi.yml
- filename: itsgloria-ai-recaps-api-openapi.yml
  format: yaml
  label: Gloria Recaps API
  slug: itsgloria-ai-recaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-recaps-api-openapi.yml
- filename: itsgloria-ai-websocket-api-openapi.yml
  format: yaml
  label: Gloria WebSocket API
  slug: itsgloria-ai-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-websocket-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction to use the Services.
    type: individual
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction to use the Services.
    value: age of majority
  restricted_uses:
  - summary: Scraping or commercial exploitation without permission
    text: Scrape, copy, or commercially exploit the Services without permission
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
name: Gloria
provenance_date: '2026-11-09'
provider_name: Gloria
provider_slug: itsgloria-ai
slug: itsgloria-ai-eligibility
source_date: '2026-11-09'
source_filename: itsgloria-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.itsgloria.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gloria\naid: itsgloria-ai\nurl: https://www.itsgloria.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction to use the Services.\nrestricted_uses:\n- summary: Scraping or commercial exploitation without permission\n  text: Scrape, copy, or commercially exploit the Services without permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority\
  \ in your jurisdiction to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/itsgloria-ai/eligibility/itsgloria-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gloria's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Cryptocurrency
- Market Intelligence
- Sentiment Analysis
- Prediction Markets
- Artificial Intelligence
- MCP
- x402
- WebSocket
- Agents
---

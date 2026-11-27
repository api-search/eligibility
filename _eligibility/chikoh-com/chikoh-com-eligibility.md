---
api_specs:
- filename: chikoh-com-contest-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Contest Intelligence API
  slug: chikoh-com-contest-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-contest-intelligence-api-openapi.yml
- filename: chikoh-com-entertainment-api-openapi.yml
  format: yaml
  label: Chikoh Entertainment API
  slug: chikoh-com-entertainment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-entertainment-api-openapi.yml
- filename: chikoh-com-entertainment-predictions-api-openapi.yml
  format: yaml
  label: Chikoh Entertainment Predictions API
  slug: chikoh-com-entertainment-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-entertainment-predictions-api-openapi.yml
- filename: chikoh-com-market-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Market Intelligence API
  slug: chikoh-com-market-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-market-intelligence-api-openapi.yml
- filename: chikoh-com-player-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Player Intelligence API
  slug: chikoh-com-player-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-player-intelligence-api-openapi.yml
- filename: chikoh-com-strategic-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Strategic Intelligence API
  slug: chikoh-com-strategic-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-strategic-intelligence-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older to use Chikoh.
    type: individual
  minimum_age:
    text: You must be 18 or older to use Chikoh.
    value: '18'
  restricted_uses:
  - summary: Betting tools and paid pools require 21+
    text: Betting-related tools and paid pools require you to be 21 or older.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We ask you to confirm you are 18 or older before you start using the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chikoh
provenance_date: '2026-11-09'
provider_name: Chikoh
provider_slug: chikoh-com
slug: chikoh-com-eligibility
source_date: '2026-11-09'
source_filename: chikoh-com-eligibility.yml
source_heading: Eligibility
source_page: https://chikoh.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chikoh\naid: chikoh-com\nurl: https://chikoh.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older to use Chikoh.\nrestricted_uses:\n- summary: Betting tools and paid pools require 21+\n  text: Betting-related tools and paid pools require you to be 21 or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We ask you to confirm you are 18 or older before you start using the Service\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to use Chikoh.\n"
source_yaml_url: https://artifacts.apis.io/chikoh-com/eligibility/chikoh-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Chikoh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fantasy Sports
- Sports Analytics
- Reality TV
- Predictions
- Gaming
- AI Agents
- MCP
---

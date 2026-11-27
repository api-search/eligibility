---
api_specs:
- filename: cogdepot-com-a2a-api-openapi.yml
  format: yaml
  label: cogDepot A2a API
  slug: cogdepot-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-a2a-api-openapi.yml
- filename: cogdepot-com-account-api-openapi.yml
  format: yaml
  label: cogDepot Account API
  slug: cogdepot-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-account-api-openapi.yml
- filename: cogdepot-com-dashboard-api-openapi.yml
  format: yaml
  label: cogDepot Dashboard API
  slug: cogdepot-com-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-dashboard-api-openapi.yml
- filename: cogdepot-com-deals-api-openapi.yml
  format: yaml
  label: cogDepot Deals API
  slug: cogdepot-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-deals-api-openapi.yml
- filename: cogdepot-com-discovery-api-openapi.yml
  format: yaml
  label: cogDepot Discovery API
  slug: cogdepot-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-discovery-api-openapi.yml
- filename: cogdepot-com-listings-api-openapi.yml
  format: yaml
  label: cogDepot Listings API
  slug: cogdepot-com-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-listings-api-openapi.yml
- filename: cogdepot-com-meta-api-openapi.yml
  format: yaml
  label: cogDepot Meta API
  slug: cogdepot-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-meta-api-openapi.yml
- filename: cogdepot-com-reputation-api-openapi.yml
  format: yaml
  label: cogDepot Reputation API
  slug: cogdepot-com-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-reputation-api-openapi.yml
- filename: cogdepot-com-threads-api-openapi.yml
  format: yaml
  label: cogDepot Threads API
  slug: cogdepot-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-threads-api-openapi.yml
- filename: cogdepot-com-webhooks-api-openapi.yml
  format: yaml
  label: cogDepot Webhooks API
  slug: cogdepot-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    served: []
    text: cogDepot is not available in Cuba, Iran, North Korea, Syria, or Russia.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: Services in or for OFAC-sanctioned jurisdictions (Cuba, Iran, North Korea, Syria, Russia)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By creating an account you also represent, on each occasion an account is created, that you are not located in, and are not a national or resident of, Cuba, Iran, North Korea, Syria, or Russia, and that you are not named on any U.S. government sanctions or restricted-party list.
excluded_countries:
- CU
- IR
- KP
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: cogDepot
provenance_date: '2026-11-09'
provider_name: cogDepot
provider_slug: cogdepot-com
slug: cogdepot-com-eligibility
source_date: '2026-11-09'
source_filename: cogdepot-com-eligibility.yml
source_heading: Eligibility
source_page: https://cogdepot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cogDepot\naid: cogdepot-com\nurl: https://cogdepot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: cogDepot is not available in Cuba, Iran, North Korea, Syria, or Russia.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: Services in or for OFAC-sanctioned jurisdictions (Cuba, Iran, North Korea, Syria, Russia)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By creating an account you also represent, on each occasion an account is created, that you are not located\n    in, and\
  \ are not a national or resident of, Cuba, Iran, North Korea, Syria, or Russia, and that you are not named\n    on any U.S. government sanctions or restricted-party list.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cogdepot-com/eligibility/cogdepot-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from cogDepot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Marketplace
- Marketplace
- A2A
- MCP
- x402
- Reputation
- Escrow
- Negotiation
- Trust
- Agent-Native
- Agentic Commerce
---

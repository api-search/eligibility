---
api_specs:
- filename: sentineliq-net-agent-api-api-openapi.yml
  format: yaml
  label: sentineliq-net Agent API
  slug: sentineliq-net-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-agent-api-api-openapi.yml
- filename: sentineliq-net-mcp-api-openapi.yml
  format: yaml
  label: sentineliq-net MCP API
  slug: sentineliq-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-mcp-api-openapi.yml
- filename: sentineliq-net-property-research-api-openapi.yml
  format: yaml
  label: sentineliq-net Property Research API
  slug: sentineliq-net-property-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-property-research-api-openapi.yml
- filename: sentineliq-net-public-api-openapi.yml
  format: yaml
  label: sentineliq-net Public API
  slug: sentineliq-net-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-public-api-openapi.yml
- filename: sentineliq-net-seller-workflows-api-openapi.yml
  format: yaml
  label: sentineliq-net Seller Workflows API
  slug: sentineliq-net-seller-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-seller-workflows-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SENTINEL is an AI-powered web app for Washington state licensed real estate agents.
  entity_types:
  - text: One account per natural person.
    type: individual
  minimum_age:
    text: You must be (a) at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Licensed WA brokers only
    text: You must be (a) at least 18 years old, (b) a licensed real estate broker or managing broker in good standing in the State of Washington under RCW 18.85, or a staff member operating under the supervision of such a licensee.
  - summary: Consumer output caveat
    text: Always append "verify with your broker" to any consumer-facing use of SENTINEL output.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to verify your license status against the Washington Department of Licensing real estate license lookup at any time, and to suspend or terminate accounts that fail verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sentineliq-net
provenance_date: '2026-11-10'
provider_name: sentineliq-net
provider_slug: sentineliq-net
slug: sentineliq-net-eligibility
source_date: '2026-11-10'
source_filename: sentineliq-net-eligibility.yml
source_heading: Eligibility
source_page: https://sentineliq.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sentineliq-net\naid: sentineliq-net\nurl: https://sentineliq.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: SENTINEL is an AI-powered web app for Washington state licensed real estate agents.\nentity_types:\n- type: individual\n  text: One account per natural person.\nrestricted_uses:\n- summary: Licensed WA brokers only\n  text: You must be (a) at least 18 years old, (b) a licensed real estate broker or managing broker in good standing\n    in the State of Washington under RCW 18.85, or a staff member operating under the supervision of such a licensee.\n- summary: Consumer\
  \ output caveat\n  text: Always append \"verify with your broker\" to any consumer-facing use of SENTINEL output.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to verify your license status against the Washington Department of Licensing real estate\n    license lookup at any time, and to suspend or terminate accounts that fail verification.\nminimum_age:\n  value: '18'\n  text: You must be (a) at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/sentineliq-net/eligibility/sentineliq-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from sentineliq-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data API
- Washington
- AI Integration
---

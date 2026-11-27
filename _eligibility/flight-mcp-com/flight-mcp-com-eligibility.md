---
api_specs:
- filename: flight-mcp-com-flights-api-openapi.yml
  format: yaml
  label: flight-mcp-com Flights API
  slug: flight-mcp-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flight-mcp-com/openapi/flight-mcp-com-flights-api-openapi.yml
- filename: flight-mcp-com-healthz-api-openapi.yml
  format: yaml
  label: flight-mcp-com Healthz API
  slug: flight-mcp-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flight-mcp-com/openapi/flight-mcp-com-healthz-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: use results unlawfully or in a way that infringes provider or third-party rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must use a Google Account you control and keep your session and API keys secure.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: flight-mcp-com
provenance_date: '2026-11-09'
provider_name: flight-mcp-com
provider_slug: flight-mcp-com
slug: flight-mcp-com-eligibility
source_date: '2026-11-09'
source_filename: flight-mcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://flight-mcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flight-mcp-com\naid: flight-mcp-com\nurl: https://flight-mcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use limits\n  text: use results unlawfully or in a way that infringes provider or third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must use a Google Account you control and keep your session and API keys secure.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flight-mcp-com/eligibility/flight-mcp-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from flight-mcp-com's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Flights
- MCP
- Search
---

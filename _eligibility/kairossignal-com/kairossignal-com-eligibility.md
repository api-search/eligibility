---
api_specs:
- filename: kairossignal-com-brief-api-openapi.yml
  format: yaml
  label: kairossignal-com Brief API
  slug: kairossignal-com-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-brief-api-openapi.yml
- filename: kairossignal-com-credits-api-openapi.yml
  format: yaml
  label: kairossignal-com Credits API
  slug: kairossignal-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-credits-api-openapi.yml
- filename: kairossignal-com-export-api-openapi.yml
  format: yaml
  label: kairossignal-com Export API
  slug: kairossignal-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-export-api-openapi.yml
- filename: kairossignal-com-market-api-openapi.yml
  format: yaml
  label: kairossignal-com Market API
  slug: kairossignal-com-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-market-api-openapi.yml
- filename: kairossignal-com-mcp-api-openapi.yml
  format: yaml
  label: kairossignal-com MCP API
  slug: kairossignal-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-mcp-api-openapi.yml
- filename: kairossignal-com-network-api-openapi.yml
  format: yaml
  label: kairossignal-com Network API
  slug: kairossignal-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-network-api-openapi.yml
- filename: kairossignal-com-networks-api-openapi.yml
  format: yaml
  label: kairossignal-com Networks API
  slug: kairossignal-com-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-networks-api-openapi.yml
- filename: kairossignal-com-provenance-api-openapi.yml
  format: yaml
  label: kairossignal-com Provenance API
  slug: kairossignal-com-provenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-provenance-api-openapi.yml
- filename: kairossignal-com-revenue-api-openapi.yml
  format: yaml
  label: kairossignal-com Revenue API
  slug: kairossignal-com-revenue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-revenue-api-openapi.yml
- filename: kairossignal-com-supply-api-openapi.yml
  format: yaml
  label: kairossignal-com Supply API
  slug: kairossignal-com-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-supply-api-openapi.yml
- filename: kairossignal-com-try-api-openapi.yml
  format: yaml
  label: kairossignal-com Try API
  slug: kairossignal-com-try-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-try-api-openapi.yml
- filename: kairossignal-com-x402-api-openapi.yml
  format: yaml
  label: kairossignal-com X402 API
  slug: kairossignal-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kairossignal-com/openapi/kairossignal-com-x402-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Are at least 18 years of age (or the age of majority in your jurisdiction)
    type: individual
  minimum_age:
    text: Are at least 18 years of age (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Market manipulation or illegal use
    text: Use the Service for market manipulation, front-running, or any illegal purpose
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
name: kairossignal-com
provenance_date: '2026-11-09'
provider_name: kairossignal-com
provider_slug: kairossignal-com
slug: kairossignal-com-eligibility
source_date: '2026-11-09'
source_filename: kairossignal-com-eligibility.yml
source_heading: Eligibility
source_page: https://kairossignal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kairossignal-com\naid: kairossignal-com\nurl: https://kairossignal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Are at least 18 years of age (or the age of majority in your jurisdiction)\nrestricted_uses:\n- summary: Market manipulation or illegal use\n  text: Use the Service for market manipulation, front-running, or any illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Are at least 18 years of age (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/kairossignal-com/eligibility/kairossignal-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from kairossignal-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DePIN
- Data API
- Cryptocurrency
- Telemetry
- Analytics
---

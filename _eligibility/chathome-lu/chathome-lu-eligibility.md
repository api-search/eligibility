---
api_specs:
- filename: chathome-lu-agent-api-openapi.yml
  format: yaml
  label: ChatHome Protected Agent API
  slug: protected-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-agent-api-openapi.yml
- filename: chathome-lu-agents-api-openapi.yml
  format: yaml
  label: ChatHome Agents API
  slug: chathome-lu-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-agents-api-openapi.yml
- filename: chathome-lu-listings-api-openapi.yml
  format: yaml
  label: ChatHome Listings API
  slug: chathome-lu-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-listings-api-openapi.yml
- filename: chathome-lu-market-data-api-openapi.yml
  format: yaml
  label: ChatHome Market data API
  slug: chathome-lu-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-market-data-api-openapi.yml
- filename: chathome-lu-search-api-openapi.yml
  format: yaml
  label: ChatHome Search API
  slug: chathome-lu-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - LU
    text: The platform operates in the Luxembourg market.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal listings, harassment, data extraction
    text: post fraudulent, misleading, or illegal listings; harass or impersonate other users; attempt to extract data or disrupt the service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To list properties, save searches, or message agents, you must create an account using a valid authentication method.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ChatHome
provenance_date: '2026-11-09'
provider_name: ChatHome
provider_slug: chathome-lu
slug: chathome-lu-eligibility
source_date: '2026-11-09'
source_filename: chathome-lu-eligibility.yml
source_heading: Eligibility
source_page: https://chathome.lu/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChatHome\naid: chathome-lu\nurl: https://chathome.lu/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - LU\n  excluded: []\n  text: The platform operates in the Luxembourg market.\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or illegal listings, harassment, data extraction\n  text: post fraudulent, misleading, or illegal listings; harass or impersonate other users; attempt to extract\n    data or disrupt the service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To list properties, save searches, or message agents, you must create an account using a valid\
  \ authentication\n    method.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chathome-lu/eligibility/chathome-lu-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ChatHome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Search
- Luxembourg
- Housing
- Property Valuation
- AI Agents
- MCP
- A2A
---

---
api_specs:
- filename: chatterapi-com-account-api-openapi.yml
  format: yaml
  label: chatterapi-com Account API
  slug: chatterapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-account-api-openapi.yml
- filename: chatterapi-com-everywhere-api-openapi.yml
  format: yaml
  label: chatterapi-com Everywhere API
  slug: chatterapi-com-everywhere-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-everywhere-api-openapi.yml
- filename: chatterapi-com-reddit-api-openapi.yml
  format: yaml
  label: chatterapi-com Reddit API
  slug: chatterapi-com-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-reddit-api-openapi.yml
- filename: chatterapi-com-x-api-openapi.yml
  format: yaml
  label: chatterapi-com X API
  slug: chatterapi-com-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-x-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or company.
    type: individual
  - text: One account per person or company.
    type: business
  minimum_age:
    text: null
    value: null
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
name: chatterapi-com
provenance_date: '2026-11-09'
provider_name: chatterapi-com
provider_slug: chatterapi-com
slug: chatterapi-com-eligibility
source_date: '2026-11-09'
source_filename: chatterapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://chatterapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chatterapi-com\naid: chatterapi-com\nurl: https://chatterapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person or company.\n- type: business\n  text: One account per person or company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chatterapi-com/eligibility/chatterapi-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from chatterapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Reddit
- X
- Data
- MCP
---

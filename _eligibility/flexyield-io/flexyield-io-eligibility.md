---
api_specs:
- filename: flexyield-io-agents-api-openapi.yml
  format: yaml
  label: flexyield-io Agents API
  slug: flexyield-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-agents-api-openapi.yml
- filename: flexyield-io-data-api-openapi.yml
  format: yaml
  label: flexyield-io Data API
  slug: flexyield-io-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-data-api-openapi.yml
- filename: flexyield-io-keys-api-openapi.yml
  format: yaml
  label: flexyield-io Keys API
  slug: flexyield-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-keys-api-openapi.yml
- filename: flexyield-io-rpc-api-openapi.yml
  format: yaml
  label: flexyield-io Rpc API
  slug: flexyield-io-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-rpc-api-openapi.yml
- filename: flexyield-io-statements-api-openapi.yml
  format: yaml
  label: flexyield-io Statements API
  slug: flexyield-io-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-statements-api-openapi.yml
- filename: flexyield-io-toolbox-api-openapi.yml
  format: yaml
  label: flexyield-io Toolbox API
  slug: flexyield-io-toolbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-toolbox-api-openapi.yml
- filename: flexyield-io-x402-api-openapi.yml
  format: yaml
  label: flexyield-io X402 API
  slug: flexyield-io-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-x402-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This part applies if you use the Service as an entrepreneur within the meaning of the Austrian UGB/KSchG.
    type: business
  - text: This part applies if you use the Service as a consumer within the meaning of the Austrian KSchG.
    type: individual
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
name: flexyield-io
provenance_date: '2026-11-09'
provider_name: flexyield-io
provider_slug: flexyield-io
slug: flexyield-io-eligibility
source_date: '2026-11-09'
source_filename: flexyield-io-eligibility.yml
source_heading: Eligibility
source_page: https://flexyield.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flexyield-io\naid: flexyield-io\nurl: https://flexyield.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This part applies if you use the Service as an entrepreneur within the meaning of the Austrian UGB/KSchG.\n- type: individual\n  text: This part applies if you use the Service as a consumer within the meaning of the Austrian KSchG.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flexyield-io/eligibility/flexyield-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from flexyield-io's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- API Gateway
- Unified Billing
- Multi-Chain
- Free Tier
---

---
api_specs:
- filename: catchintent-com-discovery-api-openapi.yml
  format: yaml
  label: CatchIntent Discovery API
  slug: catchintent-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-discovery-api-openapi.yml
- filename: catchintent-com-health-api-openapi.yml
  format: yaml
  label: CatchIntent Health API
  slug: catchintent-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-health-api-openapi.yml
- filename: catchintent-com-mcp-api-openapi.yml
  format: yaml
  label: CatchIntent MCP API
  slug: catchintent-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-mcp-api-openapi.yml
- filename: catchintent-com-oauth-api-openapi.yml
  format: yaml
  label: CatchIntent OAuth API
  slug: catchintent-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, have legal authority to enter into this agreement, and be using the Service for a legitimate business purpose.
    type: individual
  - text: If you’re using CatchIntent on behalf of a company, you confirm you have authority to bind that company.
    type: business
  minimum_age:
    text: You must be at least 18
    value: '18'
  restricted_uses:
  - summary: No stalking, harassment, discrimination or illegal profiling
    text: Build profiles for stalking, harassment, discrimination, or any illegal purpose
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
name: CatchIntent
provenance_date: '2026-11-09'
provider_name: CatchIntent
provider_slug: catchintent-com
slug: catchintent-com-eligibility
source_date: '2026-11-09'
source_filename: catchintent-com-eligibility.yml
source_heading: Eligibility
source_page: https://catchintent.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CatchIntent\naid: catchintent-com\nurl: https://catchintent.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, have legal authority to enter into this agreement, and be using the Service for\n    a legitimate business purpose.\n- type: business\n  text: If you’re using CatchIntent on behalf of a company, you confirm you have authority to bind that company.\nrestricted_uses:\n- summary: No stalking, harassment, discrimination or illegal profiling\n  text: Build profiles for stalking, harassment,\
  \ discrimination, or any illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/catchintent-com/eligibility/catchintent-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CatchIntent's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Sales
- Intent Data
- Artificial Intelligence
- Outbound
---

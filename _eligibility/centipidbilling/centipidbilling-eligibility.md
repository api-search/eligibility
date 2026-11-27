---
api_specs:
- filename: centipidbilling-async-api-openapi.yml
  format: yaml
  label: Centipid Technologies Async API
  slug: centipidbilling-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-async-api-openapi.yml
- filename: centipidbilling-collections-api-openapi.yml
  format: yaml
  label: Centipid Technologies Collections API
  slug: centipidbilling-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-collections-api-openapi.yml
- filename: centipidbilling-interface-api-openapi.yml
  format: yaml
  label: Centipid Technologies Interface API
  slug: centipidbilling-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-interface-api-openapi.yml
- filename: centipidbilling-mcp-api-openapi.yml
  format: yaml
  label: Centipid Technologies MCP API
  slug: centipidbilling-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-mcp-api-openapi.yml
claim_count: 1
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
  - summary: Fraud and unlawful billing
    text: Use the System in any manner that violates applicable consumer protection, telecommunications, or financial regulations
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
name: Centipid Technologies
provenance_date: '2026-11-09'
provider_name: Centipid Technologies
provider_slug: centipidbilling
slug: centipidbilling-eligibility
source_date: '2026-11-09'
source_filename: centipidbilling-eligibility.yml
source_heading: Eligibility
source_page: https://centipidbilling.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centipid Technologies\naid: centipidbilling\nurl: https://centipidbilling.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraud and unlawful billing\n  text: Use the System in any manner that violates applicable consumer protection, telecommunications, or financial\n    regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centipidbilling/eligibility/centipidbilling-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Centipid Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ISP
- Billing
- OSS BSS
- Telecommunications
---

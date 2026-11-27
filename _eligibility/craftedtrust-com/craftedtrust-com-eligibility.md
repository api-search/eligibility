---
api_specs:
- filename: craftedtrust-com-mcp-api-openapi.yml
  format: yaml
  label: CraftedTrust MCP API
  slug: craftedtrust-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftedtrust-com/openapi/craftedtrust-com-mcp-api-openapi.yml
- filename: craftedtrust-com-public-api-openapi.yml
  format: yaml
  label: CraftedTrust Public API
  slug: craftedtrust-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftedtrust-com/openapi/craftedtrust-com-public-api-openapi.yml
- filename: craftedtrust-com-publisher-api-openapi.yml
  format: yaml
  label: CraftedTrust Publisher API
  slug: craftedtrust-com-publisher-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftedtrust-com/openapi/craftedtrust-com-publisher-api-openapi.yml
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
  - summary: No abuse or unauthorized testing
    text: Do not use the scan surface for abuse, unauthorized testing, or private targets you do not control.
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
name: CraftedTrust
provenance_date: '2026-11-09'
provider_name: CraftedTrust
provider_slug: craftedtrust-com
slug: craftedtrust-com-eligibility
source_date: '2026-11-09'
source_filename: craftedtrust-com-eligibility.yml
source_heading: Eligibility
source_page: https://craftedtrust.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CraftedTrust\naid: craftedtrust-com\nurl: https://craftedtrust.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No abuse or unauthorized testing\n  text: Do not use the scan surface for abuse, unauthorized testing, or private targets you do not control.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/craftedtrust-com/eligibility/craftedtrust-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CraftedTrust's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Security
- Trust Registry
- Security Scanning
---

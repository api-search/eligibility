---
api_specs:
- filename: bol-ai-billing-api-openapi.yml
  format: yaml
  label: Bol.ai Billing API
  slug: bol-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-billing-api-openapi.yml
- filename: bol-ai-bol-api-openapi.yml
  format: yaml
  label: Bol.ai Bol API
  slug: bol-ai-bol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-bol-api-openapi.yml
- filename: bol-ai-mcp-api-openapi.yml
  format: yaml
  label: Bol.ai MCP API
  slug: bol-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-mcp-api-openapi.yml
- filename: bol-ai-me-api-openapi.yml
  format: yaml
  label: Bol.ai Me API
  slug: bol-ai-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-me-api-openapi.yml
- filename: bol-ai-usage-api-openapi.yml
  format: yaml
  label: Bol.ai Usage API
  slug: bol-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-usage-api-openapi.yml
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
  - summary: No unlawful or sanctioned use
    text: use the Service to violate applicable export, sanctions, or data-protection law
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
name: Bol.ai
provenance_date: '2026-11-09'
provider_name: Bol.ai
provider_slug: bol-ai
slug: bol-ai-eligibility
source_date: '2026-11-09'
source_filename: bol-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bol.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bol.ai\naid: bol-ai\nurl: https://bol.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unlawful or sanctioned use\n  text: use the Service to violate applicable export, sanctions, or data-protection law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bol-ai/eligibility/bol-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Bol.ai's own page on 2026-11-09.
synthetic: false
tags:
- Freight Documents
- Data Extraction
- Bill of Lading
- 3PL
---

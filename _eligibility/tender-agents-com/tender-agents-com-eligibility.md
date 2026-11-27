---
api_specs:
- filename: tender-agents-com-agent-discovery-api-openapi.yml
  format: yaml
  label: tender-agents-com Agent Discovery API
  slug: tender-agents-com-agent-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-agent-discovery-api-openapi.yml
- filename: tender-agents-com-erp-export-api-openapi.yml
  format: yaml
  label: tender-agents-com ERP Export API
  slug: tender-agents-com-erp-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-erp-export-api-openapi.yml
- filename: tender-agents-com-gaeb-api-openapi.yml
  format: yaml
  label: tender-agents-com Gaeb API
  slug: tender-agents-com-gaeb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-gaeb-api-openapi.yml
- filename: tender-agents-com-keys-api-openapi.yml
  format: yaml
  label: tender-agents-com Keys API
  slug: tender-agents-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-keys-api-openapi.yml
- filename: tender-agents-com-mcp-api-openapi.yml
  format: yaml
  label: tender-agents-com MCP API
  slug: tender-agents-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-mcp-api-openapi.yml
- filename: tender-agents-com-oauth-api-openapi.yml
  format: yaml
  label: tender-agents-com OAuth API
  slug: tender-agents-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-oauth-api-openapi.yml
- filename: tender-agents-com-profiles-api-openapi.yml
  format: yaml
  label: tender-agents-com Profiles API
  slug: tender-agents-com-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-profiles-api-openapi.yml
- filename: tender-agents-com-signup-api-openapi.yml
  format: yaml
  label: tender-agents-com Signup API
  slug: tender-agents-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-signup-api-openapi.yml
- filename: tender-agents-com-source-status-api-openapi.yml
  format: yaml
  label: tender-agents-com Source Status API
  slug: tender-agents-com-source-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-source-status-api-openapi.yml
- filename: tender-agents-com-tenders-api-openapi.yml
  format: yaml
  label: tender-agents-com Tenders API
  slug: tender-agents-com-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-tenders-api-openapi.yml
- filename: tender-agents-com-tenders-public-api-openapi.yml
  format: yaml
  label: tender-agents-com Tenders Public API
  slug: tender-agents-com-tenders-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-tenders-public-api-openapi.yml
- filename: tender-agents-com-webhooks-api-openapi.yml
  format: yaml
  label: tender-agents-com Webhooks API
  slug: tender-agents-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tender-agents-com/openapi/tender-agents-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The offering is directed exclusively at businesses, legal entities under public law and special funds under public law — not at consumers.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Customer accounts are approved by the provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tender-agents-com
provenance_date: '2026-11-10'
provider_name: tender-agents-com
provider_slug: tender-agents-com
slug: tender-agents-com-eligibility
source_date: '2026-11-10'
source_filename: tender-agents-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.tender-agents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tender-agents-com\naid: tender-agents-com\nurl: https://www.tender-agents.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The offering is directed exclusively at businesses, legal entities under public law and special funds under\n    public law — not at consumers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Customer accounts are approved by the provider.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tender-agents-com/eligibility/tender-agents-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from tender-agents-com's own page on 2026-11-10.
synthetic: false
tags:
- EU
- Procurement
- Tenders
- Artificial Intelligence
- Public Data
---

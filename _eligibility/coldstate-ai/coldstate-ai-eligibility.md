---
api_specs:
- filename: coldstate-ai-auth-api-openapi.yml
  format: yaml
  label: ColdState Auth API
  slug: coldstate-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-auth-api-openapi.yml
- filename: coldstate-ai-billing-api-openapi.yml
  format: yaml
  label: ColdState Billing API
  slug: coldstate-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-billing-api-openapi.yml
- filename: coldstate-ai-indexes-api-openapi.yml
  format: yaml
  label: ColdState Indexes API
  slug: coldstate-ai-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-indexes-api-openapi.yml
- filename: coldstate-ai-knowledge-api-openapi.yml
  format: yaml
  label: ColdState Knowledge API
  slug: coldstate-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-knowledge-api-openapi.yml
- filename: coldstate-ai-mcp-api-openapi.yml
  format: yaml
  label: ColdState MCP API
  slug: coldstate-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-mcp-api-openapi.yml
- filename: coldstate-ai-meta-api-openapi.yml
  format: yaml
  label: ColdState Meta API
  slug: coldstate-ai-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-meta-api-openapi.yml
- filename: coldstate-ai-search-api-openapi.yml
  format: yaml
  label: ColdState Search API
  slug: coldstate-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-search-api-openapi.yml
- filename: coldstate-ai-usage-api-openapi.yml
  format: yaml
  label: ColdState Usage API
  slug: coldstate-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Use the Service for any unlawful purpose
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
name: ColdState
provenance_date: '2026-11-09'
provider_name: ColdState
provider_slug: coldstate-ai
slug: coldstate-ai-eligibility
source_date: '2026-11-09'
source_filename: coldstate-ai-eligibility.yml
source_heading: Eligibility
source_page: https://services.coldstate.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ColdState\naid: coldstate-ai\nurl: https://services.coldstate.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coldstate-ai/eligibility/coldstate-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ColdState's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Base
- Search
- Deterministic Retrieval
- MCP
- AI Agents
- Citations
---

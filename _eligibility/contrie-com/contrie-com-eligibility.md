---
api_specs:
- filename: contrie-com-account-api-openapi.yml
  format: yaml
  label: Contrie Account API
  slug: contrie-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-account-api-openapi.yml
- filename: contrie-com-evidence-api-openapi.yml
  format: yaml
  label: Contrie Evidence API
  slug: contrie-com-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-evidence-api-openapi.yml
- filename: contrie-com-extract-api-openapi.yml
  format: yaml
  label: Contrie Extract API
  slug: contrie-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-extract-api-openapi.yml
- filename: contrie-com-health-api-openapi.yml
  format: yaml
  label: Contrie Health API
  slug: contrie-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-health-api-openapi.yml
- filename: contrie-com-mcp-api-openapi.yml
  format: yaml
  label: Contrie MCP API
  slug: contrie-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-mcp-api-openapi.yml
- filename: contrie-com-monitors-api-openapi.yml
  format: yaml
  label: Contrie Monitors API
  slug: contrie-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-monitors-api-openapi.yml
- filename: contrie-com-scrape-api-openapi.yml
  format: yaml
  label: Contrie Scrape API
  slug: contrie-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-scrape-api-openapi.yml
- filename: contrie-com-search-api-openapi.yml
  format: yaml
  label: Contrie Search API
  slug: contrie-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-search-api-openapi.yml
- filename: contrie-com-verification-api-openapi.yml
  format: yaml
  label: Contrie Verification API
  slug: contrie-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-verification-api-openapi.yml
- filename: contrie-com-verify-api-openapi.yml
  format: yaml
  label: Contrie Verify API
  slug: contrie-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-verify-api-openapi.yml
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
  - summary: Unlawful or harmful use
    text: You agree to use Contrie only for lawful purposes.
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
name: Contrie
provenance_date: '2026-11-09'
provider_name: Contrie
provider_slug: contrie-com
slug: contrie-com-eligibility
source_date: '2026-11-09'
source_filename: contrie-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.contrie.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contrie\naid: contrie-com\nurl: https://www.contrie.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You agree to use Contrie only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contrie-com/eligibility/contrie-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Contrie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- AI Agents
- MCP
- Structured Data
- Markdown
---

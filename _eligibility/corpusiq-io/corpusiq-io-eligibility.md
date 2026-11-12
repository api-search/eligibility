---
api_specs:
- filename: corpusiq-io-authentication-api-openapi.yml
  format: yaml
  label: CorpusIQ Authentication API
  slug: corpusiq-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-authentication-api-openapi.yml
- filename: corpusiq-io-discovery-api-openapi.yml
  format: yaml
  label: CorpusIQ Discovery API
  slug: corpusiq-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-discovery-api-openapi.yml
- filename: corpusiq-io-mcp-api-openapi.yml
  format: yaml
  label: CorpusIQ MCP API
  slug: corpusiq-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-mcp-api-openapi.yml
- filename: corpusiq-io-usage-api-openapi.yml
  format: yaml
  label: CorpusIQ Usage API
  slug: corpusiq-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the authority to accept these Terms on behalf of your business.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or regulated use
    text: Use the Service for any unlawful purpose or in violation of any regulation.
  - summary: PHI or payment card data
    text: Use the Service to process or transmit sensitive personal health information (PHI) or payment card data beyond what is permitted by applicable law.
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
name: CorpusIQ
provenance_date: '2026-11-09'
provider_name: CorpusIQ
provider_slug: corpusiq-io
slug: corpusiq-io-eligibility
source_date: '2026-11-09'
source_filename: corpusiq-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.corpusiq.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CorpusIQ\naid: corpusiq-io\nurl: https://www.corpusiq.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be at least 18 years old and have the authority to accept these Terms on behalf of your business.\nrestricted_uses:\n- summary: Unlawful or regulated use\n  text: Use the Service for any unlawful purpose or in violation of any regulation.\n- summary: PHI or payment card data\n  text: Use the Service to process or transmit sensitive personal health information (PHI) or payment card data\n    beyond what is permitted\
  \ by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/corpusiq-io/eligibility/corpusiq-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CorpusIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Business Intelligence
- Small Business
- Integrations
- ChatGPT
- Analytics
---

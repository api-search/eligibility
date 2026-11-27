---
api_specs:
- filename: studiomeyer-io-account-api-openapi.yml
  format: yaml
  label: studiomeyer-io Account API
  slug: studiomeyer-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-account-api-openapi.yml
- filename: studiomeyer-io-backfill-api-openapi.yml
  format: yaml
  label: studiomeyer-io Backfill API
  slug: studiomeyer-io-backfill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-backfill-api-openapi.yml
- filename: studiomeyer-io-case-study-api-openapi.yml
  format: yaml
  label: studiomeyer-io Case Study API
  slug: studiomeyer-io-case-study-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-case-study-api-openapi.yml
- filename: studiomeyer-io-consultation-api-openapi.yml
  format: yaml
  label: studiomeyer-io Consultation API
  slug: studiomeyer-io-consultation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-consultation-api-openapi.yml
- filename: studiomeyer-io-decide-api-openapi.yml
  format: yaml
  label: studiomeyer-io Decide API
  slug: studiomeyer-io-decide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-decide-api-openapi.yml
- filename: studiomeyer-io-docs-api-openapi.yml
  format: yaml
  label: studiomeyer-io Docs API
  slug: studiomeyer-io-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-docs-api-openapi.yml
- filename: studiomeyer-io-entity-api-openapi.yml
  format: yaml
  label: studiomeyer-io Entity API
  slug: studiomeyer-io-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-entity-api-openapi.yml
- filename: studiomeyer-io-export-api-openapi.yml
  format: yaml
  label: studiomeyer-io Export API
  slug: studiomeyer-io-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-export-api-openapi.yml
- filename: studiomeyer-io-generate-agents-json-api-openapi.yml
  format: yaml
  label: studiomeyer-io Generate Agents Json API
  slug: studiomeyer-io-generate-agents-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-generate-agents-json-api-openapi.yml
- filename: studiomeyer-io-learn-api-openapi.yml
  format: yaml
  label: studiomeyer-io Learn API
  slug: studiomeyer-io-learn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-learn-api-openapi.yml
- filename: studiomeyer-io-memory-api-openapi.yml
  format: yaml
  label: studiomeyer-io Memory API
  slug: studiomeyer-io-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-memory-api-openapi.yml
- filename: studiomeyer-io-portfolio-api-openapi.yml
  format: yaml
  label: studiomeyer-io Portfolio API
  slug: studiomeyer-io-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-portfolio-api-openapi.yml
- filename: studiomeyer-io-quote-api-openapi.yml
  format: yaml
  label: studiomeyer-io Quote API
  slug: studiomeyer-io-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-quote-api-openapi.yml
- filename: studiomeyer-io-search-api-openapi.yml
  format: yaml
  label: studiomeyer-io Search API
  slug: studiomeyer-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-search-api-openapi.yml
- filename: studiomeyer-io-services-api-openapi.yml
  format: yaml
  label: studiomeyer-io Services API
  slug: studiomeyer-io-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-services-api-openapi.yml
- filename: studiomeyer-io-studiomeyer-memory-rest-api-api-openapi.yml
  format: yaml
  label: studiomeyer-io StudioMeyer Memory REST API
  slug: studiomeyer-io-studiomeyer-memory-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-studiomeyer-memory-rest-api-api-openapi.yml
- filename: studiomeyer-io-validate-webmcp-api-openapi.yml
  format: yaml
  label: studiomeyer-io Validate Webmcp API
  slug: studiomeyer-io-validate-webmcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/studiomeyer-io/openapi/studiomeyer-io-validate-webmcp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: business customers (entrepreneurs as defined in §14 German Civil Code, hereinafter "B2B customers")
    type: business
  - text: consumers (as defined in §13 German Civil Code)
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
name: studiomeyer-io
provenance_date: '2026-11-10'
provider_name: studiomeyer-io
provider_slug: studiomeyer-io
slug: studiomeyer-io-eligibility
source_date: '2026-11-10'
source_filename: studiomeyer-io-eligibility.yml
source_heading: Eligibility
source_page: https://studiomeyer.io/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: studiomeyer-io\naid: studiomeyer-io\nurl: https://studiomeyer.io/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: business customers (entrepreneurs as defined in §14 German Civil Code, hereinafter \"B2B customers\")\n- type: individual\n  text: consumers (as defined in §13 German Civil Code)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/studiomeyer-io/eligibility/studiomeyer-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from studiomeyer-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Design
- MCP
- Mallorca
---

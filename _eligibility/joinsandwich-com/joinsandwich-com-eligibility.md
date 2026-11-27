---
api_specs:
- filename: joinsandwich-com-auth-api-openapi.yml
  format: yaml
  label: joinsandwich-com Auth API
  slug: joinsandwich-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-auth-api-openapi.yml
- filename: joinsandwich-com-community-api-openapi.yml
  format: yaml
  label: joinsandwich-com Community API
  slug: joinsandwich-com-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-community-api-openapi.yml
- filename: joinsandwich-com-content-api-openapi.yml
  format: yaml
  label: joinsandwich-com Content API
  slug: joinsandwich-com-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-content-api-openapi.yml
- filename: joinsandwich-com-discovery-api-openapi.yml
  format: yaml
  label: joinsandwich-com Discovery API
  slug: joinsandwich-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-discovery-api-openapi.yml
- filename: joinsandwich-com-mcp-api-openapi.yml
  format: yaml
  label: joinsandwich-com MCP API
  slug: joinsandwich-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-mcp-api-openapi.yml
- filename: joinsandwich-com-newsletter-api-openapi.yml
  format: yaml
  label: joinsandwich-com Newsletter API
  slug: joinsandwich-com-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-newsletter-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account or use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Fraud, elder abuse or exploitation
    text: Promotes or facilitates fraud, elder abuse, or exploitation
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
name: joinsandwich-com
provenance_date: '2026-11-09'
provider_name: joinsandwich-com
provider_slug: joinsandwich-com
slug: joinsandwich-com-eligibility
source_date: '2026-11-09'
source_filename: joinsandwich-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinsandwich.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: joinsandwich-com\naid: joinsandwich-com\nurl: https://www.joinsandwich.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account or use the Service.\nrestricted_uses:\n- summary: Fraud, elder abuse or exploitation\n  text: Promotes or facilitates fraud, elder abuse, or exploitation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/joinsandwich-com/eligibility/joinsandwich-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from joinsandwich-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Caregiving
- Technology
---

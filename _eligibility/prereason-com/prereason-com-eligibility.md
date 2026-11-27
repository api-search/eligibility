---
api_specs:
- filename: prereason-com-agent-access-api-openapi.yml
  format: yaml
  label: prereason-com Agent access API
  slug: prereason-com-agent-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-agent-access-api-openapi.yml
- filename: prereason-com-company-briefings-api-openapi.yml
  format: yaml
  label: prereason-com Company Briefings API
  slug: prereason-com-company-briefings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-company-briefings-api-openapi.yml
- filename: prereason-com-context-api-openapi.yml
  format: yaml
  label: prereason-com Context API
  slug: prereason-com-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-context-api-openapi.yml
- filename: prereason-com-metrics-api-openapi.yml
  format: yaml
  label: prereason-com Metrics API
  slug: prereason-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-metrics-api-openapi.yml
- filename: prereason-com-short-urls-api-openapi.yml
  format: yaml
  label: prereason-com Short URLs API
  slug: prereason-com-short-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-short-urls-api-openapi.yml
- filename: prereason-com-system-api-openapi.yml
  format: yaml
  label: prereason-com System API
  slug: prereason-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-system-api-openapi.yml
- filename: prereason-com-treasury-holdings-api-openapi.yml
  format: yaml
  label: prereason-com Treasury Holdings API
  slug: prereason-com-treasury-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-treasury-holdings-api-openapi.yml
- filename: prereason-com-webhooks-api-openapi.yml
  format: yaml
  label: prereason-com Webhooks API
  slug: prereason-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right to restrict access from any jurisdiction at our sole discretion.
  entity_types:
  - text: One account per person or legal entity
    type: individual
  - text: Building or running a product for another business needs an Enterprise licence.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for illegal purposes
  - summary: Product for another business needs Enterprise licence
    text: Building or running a product for another business needs an Enterprise licence.
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
name: prereason-com
provenance_date: '2026-11-10'
provider_name: prereason-com
provider_slug: prereason-com
slug: prereason-com-eligibility
source_date: '2026-11-10'
source_filename: prereason-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.prereason.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: prereason-com\naid: prereason-com\nurl: https://www.prereason.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right to restrict access from any jurisdiction at our sole discretion.\nentity_types:\n- type: individual\n  text: One account per person or legal entity\n- type: business\n  text: Building or running a product for another business needs an Enterprise licence.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for illegal purposes\n- summary: Product for another business needs Enterprise licence\n  text: Building or running a\
  \ product for another business needs an Enterprise licence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/prereason-com/eligibility/prereason-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from prereason-com's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Markets
- Artificial Intelligence
- Data
- MCP
---

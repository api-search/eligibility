---
api_specs:
- filename: improvado-accounts-api-openapi.yml
  format: yaml
  label: Improvado Accounts API
  slug: improvado-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-accounts-api-openapi.yml
- filename: improvado-authentication-api-openapi.yml
  format: yaml
  label: Improvado Authentication API
  slug: improvado-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-authentication-api-openapi.yml
- filename: improvado-automated-recipes-api-openapi.yml
  format: yaml
  label: Improvado Automated Recipes API
  slug: improvado-automated-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-automated-recipes-api-openapi.yml
- filename: improvado-data-source-connections-api-openapi.yml
  format: yaml
  label: Improvado Data source connections API
  slug: improvado-data-source-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-source-connections-api-openapi.yml
- filename: improvado-data-sources-api-openapi.yml
  format: yaml
  label: Improvado Data sources API
  slug: improvado-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-sources-api-openapi.yml
- filename: improvado-data-tables-api-openapi.yml
  format: yaml
  label: Improvado Data tables API
  slug: improvado-data-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-tables-api-openapi.yml
- filename: improvado-destination-connections-api-openapi.yml
  format: yaml
  label: Improvado Destination connections API
  slug: improvado-destination-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-destination-connections-api-openapi.yml
- filename: improvado-destinations-api-openapi.yml
  format: yaml
  label: Improvado Destinations API
  slug: improvado-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-destinations-api-openapi.yml
- filename: improvado-extraction-templates-api-openapi.yml
  format: yaml
  label: Improvado Extraction templates API
  slug: improvado-extraction-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-extraction-templates-api-openapi.yml
- filename: improvado-extracts-api-openapi.yml
  format: yaml
  label: Improvado Extracts API
  slug: improvado-extracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-extracts-api-openapi.yml
- filename: improvado-iframe-api-openapi.yml
  format: yaml
  label: Improvado Iframe API
  slug: improvado-iframe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-iframe-api-openapi.yml
- filename: improvado-loads-api-openapi.yml
  format: yaml
  label: Improvado Loads API
  slug: improvado-loads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-loads-api-openapi.yml
- filename: improvado-recipes-api-openapi.yml
  format: yaml
  label: Improvado Recipes API
  slug: improvado-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-recipes-api-openapi.yml
- filename: improvado-roles-api-openapi.yml
  format: yaml
  label: Improvado Roles API
  slug: improvado-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-roles-api-openapi.yml
- filename: improvado-webhooks-api-openapi.yml
  format: yaml
  label: Improvado Webhooks API
  slug: improvado-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-webhooks-api-openapi.yml
- filename: improvado-workspaces-api-openapi.yml
  format: yaml
  label: Improvado Workspaces API
  slug: improvado-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age
    type: individual
  - text: you are able to, and authorized, to create a binding legal obligation
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Fraud or inaccurate information
    text: will not provide information about any other person or that is inaccurate and/or incomplete or otherwise conduct fraudulent activities
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
name: Improvado
provenance_date: '2026-11-09'
provider_name: Improvado
provider_slug: improvado
slug: improvado-eligibility
source_date: '2026-11-09'
source_filename: improvado-eligibility.yml
source_heading: Eligibility
source_page: https://improvado.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Improvado\naid: improvado\nurl: https://improvado.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age\n- type: business\n  text: you are able to, and authorized, to create a binding legal obligation\nrestricted_uses:\n- summary: Fraud or inaccurate information\n  text: will not provide information about any other person or that is inaccurate and/or incomplete or otherwise\n    conduct fraudulent activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/improvado/eligibility/improvado-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Improvado's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Marketing Intelligence
- Marketing Analytics
- Data Pipeline
- ETL
- Advertising Data
- Business Intelligence
- Data Integration
- AI Agents
- MCP
- Agent Readiness
---

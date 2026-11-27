---
api_specs:
- filename: adplug-health-api-openapi.yml
  format: yaml
  label: AdPlug Health API
  slug: adplug-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-health-api-openapi.yml
- filename: adplug-mcp-api-openapi.yml
  format: yaml
  label: AdPlug MCP API
  slug: adplug-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-mcp-api-openapi.yml
- filename: adplug-oauth-api-openapi.yml
  format: yaml
  label: AdPlug OAuth API
  slug: adplug-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-oauth-api-openapi.yml
- filename: adplug-oauth-legacy-compat-api-openapi.yml
  format: yaml
  label: AdPlug OAUTH Legacy Compat API
  slug: adplug-oauth-legacy-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-oauth-legacy-compat-api-openapi.yml
- filename: adplug-users-api-openapi.yml
  format: yaml
  label: AdPlug Users API
  slug: adplug-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-users-api-openapi.yml
- filename: adplug-webhooks-api-openapi.yml
  format: yaml
  label: AdPlug Webhooks API
  slug: adplug-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service
    type: individual
  - text: If you are connecting accounts on behalf of a client, employer, or any other third party, you represent that you have their explicit authorization to do so
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service
    value: '18'
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
name: AdPlug
provenance_date: '2026-11-09'
provider_name: AdPlug
provider_slug: adplug
slug: adplug-eligibility
source_date: '2026-11-09'
source_filename: adplug-eligibility.yml
source_heading: Eligibility
source_page: https://adplug.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdPlug\naid: adplug\nurl: https://adplug.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service\n- type: business\n  text: If you are connecting accounts on behalf of a client, employer, or any other third party, you represent\n    that you have their explicit authorization to do so\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/adplug/eligibility/adplug-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from AdPlug's own page on 2026-11-09.
synthetic: false
tags:
- PPC
- AI Integration
- Agency Tools
- Search Console
---

---
api_specs:
- filename: pandium-connector-calls-api-openapi.yml
  format: yaml
  label: Pandium Connector Calls API
  slug: pandium-connector-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-connector-calls-api-openapi.yml
- filename: pandium-integrations-api-openapi.yml
  format: yaml
  label: Pandium Integrations API
  slug: pandium-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-integrations-api-openapi.yml
- filename: pandium-runs-api-openapi.yml
  format: yaml
  label: Pandium Runs API
  slug: pandium-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-runs-api-openapi.yml
- filename: pandium-tenant-metadata-api-openapi.yml
  format: yaml
  label: Pandium Tenant Metadata API
  slug: pandium-tenant-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-tenant-metadata-api-openapi.yml
- filename: pandium-tenants-api-openapi.yml
  format: yaml
  label: Pandium Tenants API
  slug: pandium-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-tenants-api-openapi.yml
- filename: pandium-builds-api-openapi.yml
  format: yaml
  label: Pandium Builds API
  slug: pandium-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pandium/openapi/pandium-builds-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export or re-export the Pandium Platform to proscribed or embargoed countries or their nationals unless authorized by the U.S. Government.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous or safety-critical use
    text: 'use the Pandium Platform, APIs, or Documentation in, or in association with, the design, construction, maintenance, or operation of any hazardous environments or systems, including: (i) power generation systems'
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
name: Pandium
provenance_date: '2026-11-10'
provider_name: Pandium
provider_slug: pandium
slug: pandium-eligibility
source_date: '2026-11-10'
source_filename: pandium-eligibility.yml
source_heading: Eligibility
source_page: https://www.pandium.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pandium\naid: pandium\nurl: https://www.pandium.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export or re-export the Pandium Platform to proscribed or embargoed countries or their\n    nationals unless authorized by the U.S. Government.\nentity_types: []\nrestricted_uses:\n- summary: Hazardous or safety-critical use\n  text: 'use the Pandium Platform, APIs, or Documentation in, or in association with, the design, construction,\n    maintenance, or operation of any hazardous environments or systems, including: (i) power generation systems'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pandium/eligibility/pandium-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Pandium's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Hub
- Integration
- Workflows
- iPaaS
---

---
api_specs:
- filename: cdata-mcp-api-openapi.yml
  format: yaml
  label: CData Connect AI MCP Server
  slug: mcp
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-mcp-api-openapi.yml
- filename: cdata-account-api-openapi.yml
  format: yaml
  label: CData Account API
  slug: cdata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-account-api-openapi.yml
- filename: cdata-cache-api-openapi.yml
  format: yaml
  label: CData Cache API
  slug: cdata-cache-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-cache-api-openapi.yml
- filename: cdata-connection-api-openapi.yml
  format: yaml
  label: CData Connection API
  slug: cdata-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-connection-api-openapi.yml
- filename: cdata-data-explorer-api-openapi.yml
  format: yaml
  label: CData Data Explorer API
  slug: cdata-data-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-data-explorer-api-openapi.yml
- filename: cdata-job-api-openapi.yml
  format: yaml
  label: CData Job API
  slug: cdata-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-job-api-openapi.yml
- filename: cdata-jobs-api-openapi.yml
  format: yaml
  label: CData Jobs API
  slug: cdata-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-jobs-api-openapi.yml
- filename: cdata-log-api-openapi.yml
  format: yaml
  label: CData Log API
  slug: cdata-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-log-api-openapi.yml
- filename: cdata-metadata-api-openapi.yml
  format: yaml
  label: CData Metadata API
  slug: cdata-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-metadata-api-openapi.yml
- filename: cdata-query-api-openapi.yml
  format: yaml
  label: CData Query API
  slug: cdata-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-query-api-openapi.yml
- filename: cdata-service-accounts-api-openapi.yml
  format: yaml
  label: CData Service Accounts API
  slug: cdata-service-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-service-accounts-api-openapi.yml
- filename: cdata-users-api-openapi.yml
  format: yaml
  label: CData Users API
  slug: cdata-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-users-api-openapi.yml
- filename: cdata-odata-api-openapi.yml
  format: yaml
  label: CData O Data API
  slug: cdata-odata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-odata-api-openapi.yml
- filename: cdata-open-api-api-openapi.yml
  format: yaml
  label: CData Open API
  slug: cdata-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdata/openapi/cdata-open-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, under control of, or a national or resident of any country to which export of the Website content
  entity_types:
  - text: If you are using this Website on behalf of your employer, you represent that you are authorized to accept these Terms of Use on your employer's behalf.
    type: business
  - text: (a) are at least 18 years old
    type: individual
  minimum_age:
    text: (a) are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: No content from this Website may be downloaded or otherwise exported in violation of United States law.
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
name: CData
provenance_date: '2026-11-09'
provider_name: CData
provider_slug: cdata
slug: cdata-eligibility
source_date: '2026-11-09'
source_filename: cdata-eligibility.yml
source_heading: Eligibility
source_page: https://www.cdata.com/company/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CData\naid: cdata\nurl: https://www.cdata.com/company/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, under control of, or a national or resident of any country to which export of the\n    Website content\nentity_types:\n- type: business\n  text: If you are using this Website on behalf of your employer, you represent that you are authorized to accept\n    these Terms of Use on your employer's behalf.\n- type: individual\n  text: (a) are at least 18 years old\nrestricted_uses:\n- summary: Export restrictions\n  text: No content from this Website\
  \ may be downloaded or otherwise exported in violation of United States law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/cdata/eligibility/cdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CData's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Data Access
- Data Connectivity
- Database
- NoSQL
- SQL
- A2A
---

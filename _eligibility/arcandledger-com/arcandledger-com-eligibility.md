---
api_specs:
- filename: arcandledger-com-deadlines-api-openapi.yml
  format: yaml
  label: arcandledger-com Deadlines API
  slug: arcandledger-com-deadlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-deadlines-api-openapi.yml
- filename: arcandledger-com-interest-rates-api-openapi.yml
  format: yaml
  label: arcandledger-com Interest Rates API
  slug: arcandledger-com-interest-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-interest-rates-api-openapi.yml
- filename: arcandledger-com-notices-api-openapi.yml
  format: yaml
  label: arcandledger-com Notices API
  slug: arcandledger-com-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-notices-api-openapi.yml
- filename: arcandledger-com-openapi-json-api-openapi.yml
  format: yaml
  label: arcandledger-com Openapi.json API
  slug: arcandledger-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-openapi-json-api-openapi.yml
- filename: arcandledger-com-tax-documents-api-openapi.yml
  format: yaml
  label: arcandledger-com Tax Documents API
  slug: arcandledger-com-tax-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-tax-documents-api-openapi.yml
- filename: arcandledger-com-tax-parameters-api-openapi.yml
  format: yaml
  label: arcandledger-com Tax Parameters API
  slug: arcandledger-com-tax-parameters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-tax-parameters-api-openapi.yml
- filename: arcandledger-com-vintages-api-openapi.yml
  format: yaml
  label: arcandledger-com Vintages API
  slug: arcandledger-com-vintages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcandledger-com/openapi/arcandledger-com-vintages-api-openapi.yml
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
  - summary: No sensitive identifiers sent to MCP tools
    text: Do not send a Social Security number, ITIN, EIN, tax account number, bank information, password, authentication code, tax document, or other identifying record to an MCP tool.
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
name: arcandledger-com
provenance_date: '2026-11-09'
provider_name: arcandledger-com
provider_slug: arcandledger-com
slug: arcandledger-com-eligibility
source_date: '2026-11-09'
source_filename: arcandledger-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.arcandledger.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: arcandledger-com\naid: arcandledger-com\nurl: https://www.arcandledger.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive identifiers sent to MCP tools\n  text: Do not send a Social Security number, ITIN, EIN, tax account number, bank information, password, authentication\n    code, tax document, or other identifying record to an MCP tool.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arcandledger-com/eligibility/arcandledger-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from arcandledger-com's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Tax
- Bookkeeping
- Financial Services
- Los Angeles
---

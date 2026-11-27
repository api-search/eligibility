---
api_specs:
- filename: 73-strings-asset-info-api-openapi.yml
  format: yaml
  label: 73 Strings Asset Info API
  slug: 73-strings-asset-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-asset-info-api-openapi.yml
- filename: 73-strings-documents-api-openapi.yml
  format: yaml
  label: 73 Strings Documents API
  slug: 73-strings-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-documents-api-openapi.yml
- filename: 73-strings-financial-data-api-openapi.yml
  format: yaml
  label: 73 Strings Financial Data API
  slug: 73-strings-financial-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-financial-data-api-openapi.yml
- filename: 73-strings-qualitative-data-api-openapi.yml
  format: yaml
  label: 73 Strings Qualitative Data API
  slug: 73-strings-qualitative-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-qualitative-data-api-openapi.yml
- filename: 73-strings-transaction-api-api-openapi.yml
  format: yaml
  label: 73 Strings Transaction API
  slug: 73-strings-transaction-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-transaction-api-api-openapi.yml
- filename: 73-strings-cap-table-api-openapi.yml
  format: yaml
  label: 73 Strings cap table API
  slug: 73-strings-cap-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/73-strings/openapi/73-strings-cap-table-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Country refers to: France'
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: 73 Strings
provenance_date: '2026-11-09'
provider_name: 73 Strings
provider_slug: 73-strings
slug: 73-strings-eligibility
source_date: '2026-11-09'
source_filename: 73-strings-eligibility.yml
source_heading: Eligibility
source_page: https://www.73strings.com/terms-and-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 73 Strings\naid: 73-strings\nurl: https://www.73strings.com/terms-and-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Country refers to: France'\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those\
  \ under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/73-strings/eligibility/73-strings-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from 73 Strings's own page on 2026-11-09.
synthetic: false
tags:
- Private Markets
- Valuation
- Portfolio Monitoring
- Private Equity
- Private Credit
- Venture Capital
- Alternative Assets
- Financial Data
- Data Extraction
- Fintech
- Asset Management
- Azure API Management
---

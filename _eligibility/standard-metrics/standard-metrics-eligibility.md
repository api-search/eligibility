---
api_specs:
- filename: standard-metrics-budgets-api-openapi.yml
  format: yaml
  label: Standard Metrics Budgets API
  slug: standard-metrics-budgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-budgets-api-openapi.yml
- filename: standard-metrics-cap-table-api-openapi.yml
  format: yaml
  label: Standard Metrics Cap Table API
  slug: standard-metrics-cap-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-cap-table-api-openapi.yml
- filename: standard-metrics-companies-api-openapi.yml
  format: yaml
  label: Standard Metrics Companies API
  slug: standard-metrics-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-companies-api-openapi.yml
- filename: standard-metrics-custom-columns-api-openapi.yml
  format: yaml
  label: Standard Metrics Custom Columns API
  slug: standard-metrics-custom-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-custom-columns-api-openapi.yml
- filename: standard-metrics-documents-api-openapi.yml
  format: yaml
  label: Standard Metrics Documents API
  slug: standard-metrics-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-documents-api-openapi.yml
- filename: standard-metrics-firm-details-api-openapi.yml
  format: yaml
  label: Standard Metrics Firm Details API
  slug: standard-metrics-firm-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-firm-details-api-openapi.yml
- filename: standard-metrics-funds-api-openapi.yml
  format: yaml
  label: Standard Metrics Funds API
  slug: standard-metrics-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-funds-api-openapi.yml
- filename: standard-metrics-information-reports-api-openapi.yml
  format: yaml
  label: Standard Metrics Information Reports API
  slug: standard-metrics-information-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-information-reports-api-openapi.yml
- filename: standard-metrics-information-requests-api-openapi.yml
  format: yaml
  label: Standard Metrics Information Requests API
  slug: standard-metrics-information-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-information-requests-api-openapi.yml
- filename: standard-metrics-metrics-api-openapi.yml
  format: yaml
  label: Standard Metrics API
  slug: standard-metrics-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-metrics-api-openapi.yml
- filename: standard-metrics-notes-api-openapi.yml
  format: yaml
  label: Standard Metrics Notes API
  slug: standard-metrics-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-notes-api-openapi.yml
- filename: standard-metrics-o-api-openapi.yml
  format: yaml
  label: Standard Metrics O API
  slug: standard-metrics-o-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-o-api-openapi.yml
- filename: standard-metrics-users-api-openapi.yml
  format: yaml
  label: Standard Metrics Users API
  slug: standard-metrics-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-users-api-openapi.yml
- filename: standard-metrics-whoami-api-openapi.yml
  format: yaml
  label: Standard Metrics Whoami API
  slug: standard-metrics-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-metrics/openapi/standard-metrics-whoami-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity (including any Customer, as defined below), and you represent and warrant that (a) you are an authorized representative of the entity with the authority to bind the entity to these Terms
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal, harassing or unethical use
    text: use the Services for illegal, harassing, unethical, or disruptive purposes
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
name: Standard Metrics
provenance_date: '2026-11-10'
provider_name: Standard Metrics
provider_slug: standard-metrics
slug: standard-metrics-eligibility
source_date: '2026-11-10'
source_filename: standard-metrics-eligibility.yml
source_heading: Eligibility
source_page: https://standardmetrics.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Standard Metrics\naid: standard-metrics\nurl: https://standardmetrics.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Those who choose to access the Services from locations outside the United States do so at their own initiative\n    and are responsible for compliance with applicable local laws.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity (including\n    any Customer, as defined below), and you represent and warrant that (a) you are an authorized representative\n\
  \    of the entity with the authority to bind the entity to these Terms\nrestricted_uses:\n- summary: Illegal, harassing or unethical use\n  text: use the Services for illegal, harassing, unethical, or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/standard-metrics/eligibility/standard-metrics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Standard Metrics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Venture Capital
- Private Equity
- Portfolio Management
- Financial Data
- Investment Data
- Cap Table
- Metrics
- Reporting
- MCP
---

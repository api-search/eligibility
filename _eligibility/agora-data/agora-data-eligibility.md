---
api_specs:
- filename: agora-data-health-api-openapi.yml
  format: yaml
  label: Agora Data Health API
  slug: agora-data-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-health-api-openapi.yml
- filename: agora-data-hooks-api-openapi.yml
  format: yaml
  label: Agora Data Hooks API
  slug: agora-data-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-hooks-api-openapi.yml
- filename: agora-data-import-api-openapi.yml
  format: yaml
  label: Agora Data Import API
  slug: agora-data-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-import-api-openapi.yml
- filename: agora-data-inventory-api-openapi.yml
  format: yaml
  label: Agora Data Inventory API
  slug: agora-data-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-inventory-api-openapi.yml
- filename: agora-data-loans-api-openapi.yml
  format: yaml
  label: Agora Data Loans API
  slug: agora-data-loans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-loans-api-openapi.yml
- filename: agora-data-login-api-openapi.yml
  format: yaml
  label: Agora Data Login API
  slug: agora-data-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-login-api-openapi.yml
- filename: agora-data-providers-api-openapi.yml
  format: yaml
  label: Agora Data Providers API
  slug: agora-data-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-providers-api-openapi.yml
- filename: agora-data-status-api-openapi.yml
  format: yaml
  label: Agora Data Status API
  slug: agora-data-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-status-api-openapi.yml
- filename: agora-data-uploads-api-openapi.yml
  format: yaml
  label: Agora Data Uploads API
  slug: agora-data-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-uploads-api-openapi.yml
- filename: agora-data-oauth-api-openapi.yml
  format: yaml
  label: Agora Data OAUTH API
  slug: agora-data-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agora-data/openapi/agora-data-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users and Members who are at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: The use of the Chatbot is intended for Users and Members who are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: No competing service creation
    text: create or attempt to create a substitute or similar service through use of or access to the Site
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: You must complete and submit certain registration information and other materials before Agora may grant You access to the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agora Data
provenance_date: '2026-11-09'
provider_name: Agora Data
provider_slug: agora-data
slug: agora-data-eligibility
source_date: '2026-11-09'
source_filename: agora-data-eligibility.yml
source_heading: Eligibility
source_page: https://agoradata.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agora Data\naid: agora-data\nurl: https://agoradata.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users and Members who are at least eighteen (18) years of age\nrestricted_uses:\n- summary: No competing service creation\n  text: create or attempt to create a substitute or similar service through use of or access to the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: You must complete and submit certain registration information and other materials before Agora may grant\n    You access\
  \ to the Site.\nminimum_age:\n  value: '18'\n  text: The use of the Chatbot is intended for Users and Members who are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/agora-data/eligibility/agora-data-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Agora Data's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Auto Finance
- Automotive
- Lending
- Financial Services
- Fintech
- Loan Origination
- Data Analytics
- Artificial Intelligence
- Capital Markets
---

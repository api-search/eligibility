---
api_specs:
- filename: buxfer-accounts-api-openapi.yml
  format: yaml
  label: Buxfer Accounts API
  slug: buxfer-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buxfer/openapi/buxfer-accounts-api-openapi.yml
- filename: buxfer-authentication-api-openapi.yml
  format: yaml
  label: Buxfer Authentication API
  slug: buxfer-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buxfer/openapi/buxfer-authentication-api-openapi.yml
- filename: buxfer-organization-api-openapi.yml
  format: yaml
  label: Buxfer Organization API
  slug: buxfer-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buxfer/openapi/buxfer-organization-api-openapi.yml
- filename: buxfer-social-api-openapi.yml
  format: yaml
  label: Buxfer Social API
  slug: buxfer-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buxfer/openapi/buxfer-social-api-openapi.yml
- filename: buxfer-transactions-api-openapi.yml
  format: yaml
  label: Buxfer Transactions API
  slug: buxfer-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buxfer/openapi/buxfer-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: THE COMPANY MAKES NO REPRESENTATIONS OR WARRANTS THAT THE SITE OR THE SERVICE IS APPROPRIATE OR AVAILABLE FOR USE IN OTHER COUNTRIES.
  entity_types:
  - text: must be at least 18 years of age, if YOU reside in the United States of America or must be of legal age to form a binding contract with the Company, if YOU reside elsewhere.
    type: individual
  minimum_age:
    text: YOU AGREE AND REPRESENT THAT BY USING THIS SITE AND/OR THE SERVICE YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: Your use of the Site or the Service shall only be for YOUR personal, noncommercial, use only.
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
name: Buxfer
provenance_date: '2026-11-09'
provider_name: Buxfer
provider_slug: buxfer
slug: buxfer-eligibility
source_date: '2026-11-09'
source_filename: buxfer-eligibility.yml
source_heading: Eligibility
source_page: https://www.buxfer.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buxfer\naid: buxfer\nurl: https://www.buxfer.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: THE COMPANY MAKES NO REPRESENTATIONS OR WARRANTS THAT THE SITE OR THE SERVICE IS APPROPRIATE OR AVAILABLE\n    FOR USE IN OTHER COUNTRIES.\nentity_types:\n- type: individual\n  text: must be at least 18 years of age, if YOU reside in the United States of America or must be of legal age\n    to form a binding contract with the Company, if YOU reside elsewhere.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: Your use of the Site or the Service shall only be\
  \ for YOUR personal, noncommercial, use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE AND REPRESENT THAT BY USING THIS SITE AND/OR THE SERVICE YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/buxfer/eligibility/buxfer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Buxfer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Finance
- Money Management
- Budgeting
- Banking
- Fintech
- Financial Data
- Transaction
- Investment
- Expense Tracking
---

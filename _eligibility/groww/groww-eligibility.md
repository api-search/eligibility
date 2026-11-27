---
api_specs:
- filename: groww-authentication-api-openapi.yml
  format: yaml
  label: Groww Authentication API
  slug: groww-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-authentication-api-openapi.yml
- filename: groww-historical-data-api-openapi.yml
  format: yaml
  label: Groww Historical Data API
  slug: groww-historical-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-historical-data-api-openapi.yml
- filename: groww-live-data-api-openapi.yml
  format: yaml
  label: Groww Live Data API
  slug: groww-live-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-live-data-api-openapi.yml
- filename: groww-margin-api-openapi.yml
  format: yaml
  label: Groww Margin API
  slug: groww-margin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-margin-api-openapi.yml
- filename: groww-orders-api-openapi.yml
  format: yaml
  label: Groww Orders API
  slug: groww-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-orders-api-openapi.yml
- filename: groww-portfolio-api-openapi.yml
  format: yaml
  label: Groww Portfolio API
  slug: groww-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groww/openapi/groww-portfolio-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Please note that not all the Groww Services are available in all geographical areas and depending on Your location, You may not be eligible to avail certain Groww Services.
  entity_types:
  - text: You are of 18 (eighteen) years of age or older
    type: individual
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No transfer or impersonation of account
    text: You are prohibited from selling, trading, or otherwise transferring Your Account to another party or impersonating any other person for the purposing of creating an account with the Platform
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
name: Groww
provenance_date: '2026-11-09'
provider_name: Groww
provider_slug: groww
slug: groww-eligibility
source_date: '2026-11-09'
source_filename: groww-eligibility.yml
source_heading: Eligibility
source_page: https://groww.in/pages/terms-and-conditions-groww
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groww\naid: groww\nurl: https://groww.in/pages/terms-and-conditions-groww\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Please note that not all the Groww Services are available in all geographical areas and depending on Your\n    location, You may not be eligible to avail certain Groww Services.\nentity_types:\n- type: individual\n  text: You are of 18 (eighteen) years of age or older\nrestricted_uses:\n- summary: No transfer or impersonation of account\n  text: You are prohibited from selling, trading, or otherwise transferring Your Account to another party\
  \ or impersonating\n    any other person for the purposing of creating an account with the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/groww/eligibility/groww-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Groww's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Trading
- Investing
- Stock Broking
- Market Data
- Algorithmic Trading
- India
---

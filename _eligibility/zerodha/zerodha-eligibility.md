---
api_specs:
- filename: zerodha-alerts-api-openapi.yml
  format: yaml
  label: Zerodha Alerts API
  slug: zerodha-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-alerts-api-openapi.yml
- filename: zerodha-gtt-api-openapi.yml
  format: yaml
  label: Zerodha Gtt API
  slug: zerodha-gtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-gtt-api-openapi.yml
- filename: zerodha-orders-api-openapi.yml
  format: yaml
  label: Zerodha Orders API
  slug: zerodha-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-orders-api-openapi.yml
- filename: zerodha-portfolio-api-openapi.yml
  format: yaml
  label: Zerodha Portfolio API
  slug: zerodha-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-portfolio-api-openapi.yml
- filename: zerodha-session-api-openapi.yml
  format: yaml
  label: Zerodha Session API
  slug: zerodha-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-session-api-openapi.yml
- filename: zerodha-trades-api-openapi.yml
  format: yaml
  label: Zerodha Trades API
  slug: zerodha-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-trades-api-openapi.yml
- filename: zerodha-user-api-openapi.yml
  format: yaml
  label: Zerodha User API
  slug: zerodha-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-user-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Online account opening using Aadhaar is currently available only for residents of India opening individual accounts... This is not permissible for non-residents
  entity_types:
  - text: Online account opening using Aadhaar is currently available only for residents of India opening individual accounts
    type: individual
  - text: This is not permissible for non-residents or for any manner of non-individual accounts (HUFs, companies, LLPs, partnerships, etc.).
    type: business
  minimum_age:
    text: They are capable of being a valid counterparty to these Terms, including but not limited to being of 18 years
    value: '18'
  restricted_uses:
  - summary: Real-time price data use
    text: The Client represents and warrants that they shall not use real-time price data for any other purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Your account shall be opened after submission of the requisite documentation and its verification and at the sole discretion of Zerodha.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zerodha
provenance_date: '2026-11-10'
provider_name: Zerodha
provider_slug: zerodha
slug: zerodha-eligibility
source_date: '2026-11-10'
source_filename: zerodha-eligibility.yml
source_heading: Eligibility
source_page: https://zerodha.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zerodha\naid: zerodha\nurl: https://zerodha.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Online account opening using Aadhaar is currently available only for residents of India opening individual\n    accounts... This is not permissible for non-residents\nentity_types:\n- type: individual\n  text: Online account opening using Aadhaar is currently available only for residents of India opening individual\n    accounts\n- type: business\n  text: This is not permissible for non-residents or for any manner of non-individual accounts\
  \ (HUFs, companies,\n    LLPs, partnerships, etc.).\nrestricted_uses:\n- summary: Real-time price data use\n  text: The Client represents and warrants that they shall not use real-time price data for any other purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Your account shall be opened after submission of the requisite documentation and its verification and at\n    the sole discretion of Zerodha.\nminimum_age:\n  value: '18'\n  text: They are capable of being a valid counterparty to these Terms, including but not limited to being of 18\n    years\n"
source_yaml_url: https://artifacts.apis.io/zerodha/eligibility/zerodha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Zerodha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Trading
- Fintech
---

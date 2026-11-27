---
api_specs:
- filename: hypto-banking-api-openapi.yml
  format: yaml
  label: Hypto Banking API
  slug: hypto-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-banking-api-openapi.yml
- filename: hypto-generate-qr-api-openapi.yml
  format: yaml
  label: Hypto Generate QR API
  slug: hypto-generate-qr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-generate-qr-api-openapi.yml
- filename: hypto-payments-api-openapi.yml
  format: yaml
  label: Hypto Payments API
  slug: hypto-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-payments-api-openapi.yml
- filename: hypto-status-api-openapi.yml
  format: yaml
  label: Hypto Status API
  slug: hypto-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-status-api-openapi.yml
- filename: hypto-upi-api-openapi.yml
  format: yaml
  label: Hypto UPI API
  slug: hypto-upi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-upi-api-openapi.yml
- filename: hypto-upi-collections-api-openapi.yml
  format: yaml
  label: Hypto UPI Collections API
  slug: hypto-upi-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-upi-collections-api-openapi.yml
- filename: hypto-webhooks-api-openapi.yml
  format: yaml
  label: Hypto Webhooks API
  slug: hypto-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypto/openapi/hypto-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and the Services are intended solely for persons who can form legally binding contracts under Indian law and who are 18 (eighteen) years of age or older.
  entity_types:
  - text: The User represents and warrants that he is 18 (eighteen) years of age or older and is competent to contract.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Banned products and services
    text: Products shall not include those banned products and services that are listed in Annexure A.
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
name: Hypto
provenance_date: '2026-11-09'
provider_name: Hypto
provider_slug: hypto
slug: hypto-eligibility
source_date: '2026-11-09'
source_filename: hypto-eligibility.yml
source_heading: Eligibility
source_page: https://www.hypto.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hypto\naid: hypto\nurl: https://www.hypto.in/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and the Services are intended solely for persons who can form legally binding contracts under\n    Indian law and who are 18 (eighteen) years of age or older.\nentity_types:\n- type: individual\n  text: The User represents and warrants that he is 18 (eighteen) years of age or older and is competent to contract.\nrestricted_uses:\n- summary: Banned products and services\n  text: Products shall not include those banned products and services that are listed in Annexure A.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hypto/eligibility/hypto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Hypto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Collection
---

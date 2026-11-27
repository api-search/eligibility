---
api_specs:
- filename: maesn-accounting-api-openapi.yml
  format: yaml
  label: Maesn Accounting API
  slug: maesn-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-accounting-api-openapi.yml
- filename: maesn-auth-api-openapi.yml
  format: yaml
  label: Maesn Auth API
  slug: maesn-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-auth-api-openapi.yml
- filename: maesn-tenants-api-openapi.yml
  format: yaml
  label: Maesn Tenants API
  slug: maesn-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-tenants-api-openapi.yml
- filename: maesn-user-api-openapi.yml
  format: yaml
  label: Maesn User API
  slug: maesn-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-user-api-openapi.yml
- filename: maesn-webhook-api-openapi.yml
  format: yaml
  label: Maesn Webhook API
  slug: maesn-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-webhook-api-openapi.yml
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
  - summary: Export and sanctions compliance
    text: Customer shall comply with all applicable German, European and international export and sanctions regulations
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
name: Maesn
provenance_date: '2026-11-10'
provider_name: Maesn
provider_slug: maesn
slug: maesn-eligibility
source_date: '2026-11-10'
source_filename: maesn-eligibility.yml
source_heading: Eligibility
source_page: https://www.maesn.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maesn\naid: maesn\nurl: https://www.maesn.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: Customer shall comply with all applicable German, European and international export and sanctions regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maesn/eligibility/maesn-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Maesn's own page on 2026-11-10.
synthetic: false
tags:
- ERP
- Accounting
- Integration
- Software-as-a-Service
---

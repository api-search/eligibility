---
api_specs:
- filename: debounce-account-management-api-openapi.yml
  format: yaml
  label: DeBounce Account Management API
  slug: debounce-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-account-management-api-openapi.yml
- filename: debounce-debounce-disposable-email-detector-api-api-openapi.yml
  format: yaml
  label: DeBounce Disposable Email Detector API
  slug: debounce-debounce-disposable-email-detector-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-debounce-disposable-email-detector-api-api-openapi.yml
- filename: debounce-debounce-email-validation-api-api-openapi.yml
  format: yaml
  label: DeBounce Email Validation API
  slug: debounce-debounce-email-validation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-debounce-email-validation-api-api-openapi.yml
- filename: debounce-reverse-api-openapi.yml
  format: yaml
  label: DeBounce Reverse API
  slug: debounce-reverse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-reverse-api-openapi.yml
- filename: debounce-status-api-openapi.yml
  format: yaml
  label: DeBounce Status API
  slug: debounce-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-status-api-openapi.yml
- filename: debounce-upload-api-openapi.yml
  format: yaml
  label: DeBounce Upload API
  slug: debounce-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-upload-api-openapi.yml
- filename: debounce-usage-api-openapi.yml
  format: yaml
  label: DeBounce Usage API
  slug: debounce-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debounce/openapi/debounce-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be over 18 years old to use this website.
    type: individual
  minimum_age:
    text: You must be over 18 years old to use this website.
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
name: DeBounce
provenance_date: '2026-11-09'
provider_name: DeBounce
provider_slug: debounce
slug: debounce-eligibility
source_date: '2026-11-09'
source_filename: debounce-eligibility.yml
source_heading: Eligibility
source_page: https://debounce.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeBounce\naid: debounce\nurl: https://debounce.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be over 18 years old to use this website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over 18 years old to use this website.\n"
source_yaml_url: https://artifacts.apis.io/debounce/eligibility/debounce-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from DeBounce's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Deliverability
- Disposable Email Detection
- MX Records
- Bulk Email Validation
- Data Enrichment
- Syntax Validation
- Reverse Email Lookup
- Logo API
- A2A
---

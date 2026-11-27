---
api_specs:
- filename: atvenu-atvenu-api-api-openapi.yml
  format: yaml
  label: atVenu AtVenu API
  slug: atvenu-atvenu-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-atvenu-api-api-openapi.yml
- filename: atvenu-download-api-openapi.yml
  format: yaml
  label: atVenu Download API
  slug: atvenu-download-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-download-api-openapi.yml
- filename: atvenu-downloads-api-openapi.yml
  format: yaml
  label: atVenu Downloads API
  slug: atvenu-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-downloads-api-openapi.yml
- filename: atvenu-help-center-api-openapi.yml
  format: yaml
  label: atVenu Help Center API
  slug: atvenu-help-center-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-help-center-api-openapi.yml
- filename: atvenu-incidents-api-openapi.yml
  format: yaml
  label: atVenu Incidents API
  slug: atvenu-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-incidents-api-openapi.yml
- filename: atvenu-incremental-api-openapi.yml
  format: yaml
  label: atVenu Incremental API
  slug: atvenu-incremental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-incremental-api-openapi.yml
- filename: atvenu-register-api-openapi.yml
  format: yaml
  label: atVenu Register API
  slug: atvenu-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-register-api-openapi.yml
- filename: atvenu-services-api-openapi.yml
  format: yaml
  label: atVenu Services API
  slug: atvenu-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-services-api-openapi.yml
- filename: atvenu-sunshine-api-openapi.yml
  format: yaml
  label: atVenu Sunshine API
  slug: atvenu-sunshine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-sunshine-api-openapi.yml
- filename: atvenu-tickets-api-openapi.yml
  format: yaml
  label: atVenu Tickets API
  slug: atvenu-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-tickets-api-openapi.yml
- filename: atvenu-user-profiles-api-openapi.yml
  format: yaml
  label: atVenu User Profiles API
  slug: atvenu-user-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-user-profiles-api-openapi.yml
- filename: atvenu-users-api-openapi.yml
  format: yaml
  label: atVenu Users API
  slug: atvenu-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-users-api-openapi.yml
- filename: atvenu-webhooks-api-openapi.yml
  format: yaml
  label: atVenu Webhooks API
  slug: atvenu-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-webhooks-api-openapi.yml
- filename: atvenu-webstore-api-openapi.yml
  format: yaml
  label: atVenu Webstore API
  slug: atvenu-webstore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-webstore-api-openapi.yml
- filename: atvenu-graph-ql-api-openapi.yml
  format: yaml
  label: atVenu Graph QL API
  slug: atvenu-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atvenu/openapi/atvenu-graph-ql-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 16 years or older to use this Service.
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Service for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: atVenu
provenance_date: '2026-11-09'
provider_name: atVenu
provider_slug: atvenu
slug: atvenu-eligibility
source_date: '2026-11-09'
source_filename: atvenu-eligibility.yml
source_heading: Eligibility
source_page: https://www.atvenu.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: atVenu\naid: atvenu\nurl: https://www.atvenu.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process.\nminimum_age:\n  value: '16'\n  text: You must be 16 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/atvenu/eligibility/atvenu-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from atVenu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Live Events
- Commerce
- Point-of-Sale
---

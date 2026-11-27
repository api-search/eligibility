---
api_specs:
- filename: appdome-api-account-maintenance-api-openapi.yml
  format: yaml
  label: Appdome API Account Maintenance API
  slug: appdome-api-account-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-api-account-maintenance-api-openapi.yml
- filename: appdome-api-team-management-api-openapi.yml
  format: yaml
  label: Appdome API Team Management API
  slug: appdome-api-team-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-api-team-management-api-openapi.yml
- filename: appdome-api-user-management-api-openapi.yml
  format: yaml
  label: Appdome API User Management API
  slug: appdome-api-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-api-user-management-api-openapi.yml
- filename: appdome-app-validation-api-openapi.yml
  format: yaml
  label: Appdome App Validation API
  slug: appdome-app-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-app-validation-api-openapi.yml
- filename: appdome-device-match-api-openapi.yml
  format: yaml
  label: Appdome Device Match API
  slug: appdome-device-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-device-match-api-openapi.yml
- filename: appdome-secure-certificate-api-openapi.yml
  format: yaml
  label: Appdome Secure Certificate API
  slug: appdome-secure-certificate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-secure-certificate-api-openapi.yml
- filename: appdome-tasks-api-openapi.yml
  format: yaml
  label: Appdome Tasks API
  slug: appdome-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdome/openapi/appdome-tasks-api-openapi.yml
claim_count: 2
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
  - summary: Competitors and benchmarking
    text: You may not access the Service if you are our direct competitor, except with our prior written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify your identity, the enterprise you represent, or that you are a human being through one or more means, including sending you an email verification and/or asking you to provide a telephone number
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Appdome
provenance_date: '2026-11-09'
provider_name: Appdome
provider_slug: appdome
slug: appdome-eligibility
source_date: '2026-11-09'
source_filename: appdome-eligibility.yml
source_heading: Eligibility
source_page: https://www.appdome.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appdome\naid: appdome\nurl: https://www.appdome.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitors and benchmarking\n  text: You may not access the Service if you are our direct competitor, except with our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify your identity, the enterprise you represent, or that you are a human being through one or\n    more means, including sending you an email verification and/or asking\
  \ you to provide a telephone number\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appdome/eligibility/appdome-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Appdome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile App Security
- Mobile App Defense
- DevSecOps
- Application Security
- Mobile
- CI/CD
- App Signing
- Fraud Prevention
- Code Signing
- Developer Tools
---

---
api_specs:
- filename: v12-documents-api-openapi.yml
  format: yaml
  label: V12 Documents API
  slug: v12-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-documents-api-openapi.yml
- filename: v12-findings-api-openapi.yml
  format: yaml
  label: V12 Findings API
  slug: v12-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-findings-api-openapi.yml
- filename: v12-me-api-openapi.yml
  format: yaml
  label: V12 Me API
  slug: v12-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-me-api-openapi.yml
- filename: v12-members-api-openapi.yml
  format: yaml
  label: V12 Members API
  slug: v12-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-members-api-openapi.yml
- filename: v12-repositories-api-openapi.yml
  format: yaml
  label: V12 Repositories API
  slug: v12-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-repositories-api-openapi.yml
- filename: v12-runs-api-openapi.yml
  format: yaml
  label: V12 Runs API
  slug: v12-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-runs-api-openapi.yml
- filename: v12-steers-api-openapi.yml
  format: yaml
  label: V12 Steers API
  slug: v12-steers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-steers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into this agreement.
    type: individual
  - text: The Service is for business and professional use, not personal, family, or household use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Specially regulated data
    text: Customer must not submit protected health information, payment-card data, government classified information, export-controlled technical data, biometric identifiers, or another specially regulated category unless an Order Form expressly permits it.
  - summary: Prohibited end uses and countries
    text: will not use the Service for a prohibited end use or in a prohibited country or region.
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
name: V12
provenance_date: '2026-11-10'
provider_name: V12
provider_slug: v12
slug: v12-eligibility
source_date: '2026-11-10'
source_filename: v12-eligibility.yml
source_heading: Eligibility
source_page: https://v12.sh/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: V12\naid: v12\nurl: https://v12.sh/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into this agreement.\n- type: business\n  text: The Service is for business and professional use, not personal, family, or household use.\nrestricted_uses:\n- summary: Specially regulated data\n  text: Customer must not submit protected health information, payment-card data, government classified information,\n    export-controlled technical data, biometric identifiers, or another\
  \ specially regulated category unless an Order\n    Form expressly permits it.\n- summary: Prohibited end uses and countries\n  text: will not use the Service for a prohibited end use or in a prohibited country or region.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/v12/eligibility/v12-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from V12's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- DevOps
- Automation
- Code Analysis
---

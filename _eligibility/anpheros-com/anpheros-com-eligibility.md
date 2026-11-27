---
api_specs:
- filename: anpheros-com-access-requests-api-openapi.yml
  format: yaml
  label: anpheros-com Access requests API
  slug: anpheros-com-access-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-access-requests-api-openapi.yml
- filename: anpheros-com-admin-api-openapi.yml
  format: yaml
  label: anpheros-com Admin API
  slug: anpheros-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-admin-api-openapi.yml
- filename: anpheros-com-anpheros-search-api-openapi.yml
  format: yaml
  label: anpheros-com Anpheros Search API
  slug: anpheros-com-anpheros-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-anpheros-search-api-openapi.yml
- filename: anpheros-com-fhir-r4-api-openapi.yml
  format: yaml
  label: anpheros-com FHIR R4 API
  slug: anpheros-com-fhir-r4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-fhir-r4-api-openapi.yml
- filename: anpheros-com-icd-10-to-icd-11-api-openapi.yml
  format: yaml
  label: anpheros-com ICD-10 to ICD-11 API
  slug: anpheros-com-icd-10-to-icd-11-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-icd-10-to-icd-11-api-openapi.yml
- filename: anpheros-com-oauth-api-openapi.yml
  format: yaml
  label: anpheros-com OAuth API
  slug: anpheros-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-oauth-api-openapi.yml
- filename: anpheros-com-patient-me-api-openapi.yml
  format: yaml
  label: anpheros-com Patient (me) API
  slug: anpheros-com-patient-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-patient-me-api-openapi.yml
- filename: anpheros-com-rest-v1-api-openapi.yml
  format: yaml
  label: anpheros-com REST v1 API
  slug: anpheros-com-rest-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-rest-v1-api-openapi.yml
- filename: anpheros-com-smart-health-links-api-openapi.yml
  format: yaml
  label: anpheros-com SMART Health Links API
  slug: anpheros-com-smart-health-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-smart-health-links-api-openapi.yml
- filename: anpheros-com-webhooks-api-openapi.yml
  format: yaml
  label: anpheros-com Webhooks API
  slug: anpheros-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to have an account.
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful use
    text: use Anpheros for illegal purposes or to harm someone else
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
name: anpheros-com
provenance_date: '2026-11-09'
provider_name: anpheros-com
provider_slug: anpheros-com
slug: anpheros-com-eligibility
source_date: '2026-11-09'
source_filename: anpheros-com-eligibility.yml
source_heading: Eligibility
source_page: https://anpheros.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: anpheros-com\naid: anpheros-com\nurl: https://anpheros.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: use Anpheros for illegal purposes or to harm someone else\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to have an account.\n"
source_yaml_url: https://artifacts.apis.io/anpheros-com/eligibility/anpheros-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from anpheros-com's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Digital Health
- FHIR
- Medical Records
---

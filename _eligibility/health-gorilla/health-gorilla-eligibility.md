---
api_specs:
- filename: health-gorilla-binary-api-openapi.yml
  format: yaml
  label: Health Gorilla Binary API
  slug: health-gorilla-binary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-binary-api-openapi.yml
- filename: health-gorilla-coverage-api-openapi.yml
  format: yaml
  label: Health Gorilla Coverage API
  slug: health-gorilla-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-coverage-api-openapi.yml
- filename: health-gorilla-diagnosticreport-api-openapi.yml
  format: yaml
  label: Health Gorilla DiagnosticReport API
  slug: health-gorilla-diagnosticreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-diagnosticreport-api-openapi.yml
- filename: health-gorilla-observation-api-openapi.yml
  format: yaml
  label: Health Gorilla Observation API
  slug: health-gorilla-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-observation-api-openapi.yml
- filename: health-gorilla-patient-api-openapi.yml
  format: yaml
  label: Health Gorilla Patient API
  slug: health-gorilla-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-patient-api-openapi.yml
- filename: health-gorilla-practitioner-api-openapi.yml
  format: yaml
  label: Health Gorilla Practitioner API
  slug: health-gorilla-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-practitioner-api-openapi.yml
- filename: health-gorilla-requestgroup-api-openapi.yml
  format: yaml
  label: Health Gorilla RequestGroup API
  slug: health-gorilla-requestgroup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-requestgroup-api-openapi.yml
- filename: health-gorilla-servicerequest-api-openapi.yml
  format: yaml
  label: Health Gorilla ServiceRequest API
  slug: health-gorilla-servicerequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-servicerequest-api-openapi.yml
- filename: health-gorilla-capability-statement-api-openapi.yml
  format: yaml
  label: Health Gorilla Capability Statement API
  slug: health-gorilla-capability-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-capability-statement-api-openapi.yml
- filename: health-gorilla-document-reference-api-openapi.yml
  format: yaml
  label: Health Gorilla Document Reference API
  slug: health-gorilla-document-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-document-reference-api-openapi.yml
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
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: A license agreement must be signed before deploying Health Gorilla's API to production within the Offering.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Health Gorilla
provenance_date: '2026-11-09'
provider_name: Health Gorilla
provider_slug: health-gorilla
slug: health-gorilla-eligibility
source_date: '2026-11-09'
source_filename: health-gorilla-eligibility.yml
source_heading: Eligibility
source_page: https://developer.healthgorilla.com/docs/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Health Gorilla\naid: health-gorilla\nurl: https://developer.healthgorilla.com/docs/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: A license agreement must be signed before deploying Health Gorilla's API to production within the Offering.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/health-gorilla/eligibility/health-gorilla-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Health Gorilla's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Interoperability
- FHIR
- Clinical Data
- Lab Ordering
- TEFCA
- QHIN
- Health Information Exchange
- Lab Results
- Clinical Documents
- SMART on FHIR
- Patient Records
- HL7
---

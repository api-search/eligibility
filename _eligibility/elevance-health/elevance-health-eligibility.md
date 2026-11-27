---
api_specs:
- filename: elevance-health-claims-api-openapi.yml
  format: yaml
  label: Elevance Health Claims API
  slug: elevance-health-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elevance-health/openapi/elevance-health-claims-api-openapi.yml
- filename: elevance-health-conformance-api-openapi.yml
  format: yaml
  label: Elevance Health Conformance API
  slug: elevance-health-conformance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elevance-health/openapi/elevance-health-conformance-api-openapi.yml
- filename: elevance-health-coverage-api-openapi.yml
  format: yaml
  label: Elevance Health Coverage API
  slug: elevance-health-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elevance-health/openapi/elevance-health-coverage-api-openapi.yml
- filename: elevance-health-patient-api-openapi.yml
  format: yaml
  label: Elevance Health Patient API
  slug: elevance-health-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elevance-health/openapi/elevance-health-patient-api-openapi.yml
- filename: elevance-health-provider-directory-api-openapi.yml
  format: yaml
  label: Elevance Health Provider Directory API
  slug: elevance-health-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elevance-health/openapi/elevance-health-provider-directory-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the content and information included at this Application is appropriate or may be downloaded outside of the United States.
  minimum_age:
    text: This Application is not intended to attract children under the age of 13.
    value: null
  restricted_uses:
  - summary: Automated and AI access restricted
    text: We reserve the right to restrict, suspend, or revoke access to any Application by such technologies at any time.
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
name: Elevance Health
provenance_date: '2026-11-09'
provider_name: Elevance Health
provider_slug: elevance-health
slug: elevance-health-eligibility
source_date: '2026-11-09'
source_filename: elevance-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.anthem.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elevance Health\naid: elevance-health\nurl: https://www.anthem.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the content and information included at this Application is appropriate or may be\n    downloaded outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Automated and AI access restricted\n  text: We reserve the right to restrict, suspend, or revoke access to any Application by such technologies at any\n    time.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: This Application is not intended to attract children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/elevance-health/eligibility/elevance-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Elevance Health's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Healthcare
- Health Insurance
- FHIR
- Interoperability
- CMS Interoperability
- SMART on FHIR
- Da Vinci PDEX
- CARIN Blue Button
- Payers
- Provider Directory
- Formulary
- HL7
---

---
api_specs:
- filename: clover-health-fhir-r4-formulary-api-api-openapi.yml
  format: yaml
  label: Clover Health Fhir R4 Formulary API
  slug: clover-health-fhir-r4-formulary-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover-health/openapi/clover-health-fhir-r4-formulary-api-api-openapi.yml
- filename: clover-health-fhir-r4-providerdirectory-api-api-openapi.yml
  format: yaml
  label: Clover Health FHIR R4 ProviderDirectory API
  slug: clover-health-fhir-r4-providerdirectory-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover-health/openapi/clover-health-fhir-r4-providerdirectory-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: on behalf of yourself or your company
    type: business
  - text: on behalf of yourself or your company
    type: individual
  minimum_age:
    text: You further certify that you are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Only with individual's approval and direction
    text: You may not access, connect to, retrieve data from, or use in any way the API except with the approval and at the direction of the individual
  - summary: Unlawful or prohibited purposes
    text: You agree that you will not use the Service or the API for any other unlawful or prohibited purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Prior to creating your account, you will be subject to Clover Health, LLC’s Information Security Standard in order to determine that your application does not present a security risk
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clover Health
provenance_date: '2026-11-09'
provider_name: Clover Health
provider_slug: clover-health
slug: clover-health-eligibility
source_date: '2026-11-09'
source_filename: clover-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloverhealth.com/developers/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clover Health\naid: clover-health\nurl: https://www.cloverhealth.com/developers/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: on behalf of yourself or your company\n- type: individual\n  text: on behalf of yourself or your company\nrestricted_uses:\n- summary: Only with individual's approval and direction\n  text: You may not access, connect to, retrieve data from, or use in any way the API except with the approval and\n    at the direction of the individual\n- summary: Unlawful or prohibited purposes\n  text: You agree\
  \ that you will not use the Service or the API for any other unlawful or prohibited purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Prior to creating your account, you will be subject to Clover Health, LLC’s Information Security Standard\n    in order to determine that your application does not present a security risk\nminimum_age:\n  value: '18'\n  text: You further certify that you are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/clover-health/eligibility/clover-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Clover Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Medicare Advantage
- FHIR
- Interoperability
- Provider Directory
- Formulary
- Patient Access
- Payers
---

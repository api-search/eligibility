---
api_specs:
- filename: pointclickcare-assessments-api-openapi.yml
  format: yaml
  label: PointClickCare Assessments API
  slug: pointclickcare-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-assessments-api-openapi.yml
- filename: pointclickcare-diagnoses-api-openapi.yml
  format: yaml
  label: PointClickCare Diagnoses API
  slug: pointclickcare-diagnoses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-diagnoses-api-openapi.yml
- filename: pointclickcare-facilities-api-openapi.yml
  format: yaml
  label: PointClickCare Facilities API
  slug: pointclickcare-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-facilities-api-openapi.yml
- filename: pointclickcare-medications-api-openapi.yml
  format: yaml
  label: PointClickCare Medications API
  slug: pointclickcare-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-medications-api-openapi.yml
- filename: pointclickcare-patients-api-openapi.yml
  format: yaml
  label: PointClickCare Patients API
  slug: pointclickcare-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-patients-api-openapi.yml
- filename: pointclickcare-vitals-api-openapi.yml
  format: yaml
  label: PointClickCare Vitals API
  slug: pointclickcare-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-vitals-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This agreement applies exclusively to U.S.-based customers that meet HIPAA’s definition of a Covered Entity.
  entity_types:
  - text: customers classified as Covered Entities under the Health Insurance Portability and Accountability Act (HIPAA)
    type: other
  minimum_age:
    text: null
    value: null
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
name: PointClickCare
provenance_date: '2026-11-10'
provider_name: PointClickCare
provider_slug: pointclickcare
slug: pointclickcare-eligibility
source_date: '2026-11-10'
source_filename: pointclickcare-eligibility.yml
source_heading: Eligibility
source_page: https://pointclickcare.com/legal/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PointClickCare\naid: pointclickcare\nurl: https://pointclickcare.com/legal/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This agreement applies exclusively to U.S.-based customers that meet HIPAA’s definition of a Covered Entity.\nentity_types:\n- type: other\n  text: customers classified as Covered Entities under the Health Insurance Portability and Accountability Act (HIPAA)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pointclickcare/eligibility/pointclickcare-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from PointClickCare's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Long-Term Care
- Post-Acute Care
- Electronic Health Records
- FHIR
- Senior Care
- Interoperability
---

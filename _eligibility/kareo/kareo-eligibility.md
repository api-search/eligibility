---
api_specs:
- filename: kareo-administrative-api-openapi.yml
  format: yaml
  label: Kareo Administrative API
  slug: kareo-administrative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-administrative-api-openapi.yml
- filename: kareo-appointments-api-openapi.yml
  format: yaml
  label: Kareo Appointments API
  slug: kareo-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-appointments-api-openapi.yml
- filename: kareo-billing-api-openapi.yml
  format: yaml
  label: Kareo Billing API
  slug: kareo-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-billing-api-openapi.yml
- filename: kareo-encounters-api-openapi.yml
  format: yaml
  label: Kareo Encounters API
  slug: kareo-encounters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-encounters-api-openapi.yml
- filename: kareo-patients-api-openapi.yml
  format: yaml
  label: Kareo Patients API
  slug: kareo-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-patients-api-openapi.yml
- filename: kareo-providers-api-openapi.yml
  format: yaml
  label: Kareo Providers API
  slug: kareo-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kareo/openapi/kareo-providers-api-openapi.yml
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
  - summary: Adult, gambling, tobacco/alcohol applications
    text: You may not use the Tebra API in any Application that includes adult content, promotes gambling, involves the sale of tobacco or alcohol to persons under 21 years of age
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
name: Kareo
provenance_date: '2026-11-09'
provider_name: Kareo
provider_slug: kareo
slug: kareo-eligibility
source_date: '2026-11-09'
source_filename: kareo-eligibility.yml
source_heading: Eligibility
source_page: https://www.tebra.com/api-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kareo\naid: kareo\nurl: https://www.tebra.com/api-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult, gambling, tobacco/alcohol applications\n  text: You may not use the Tebra API in any Application that includes adult content, promotes gambling, involves\n    the sale of tobacco or alcohol to persons under 21 years of age\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kareo/eligibility/kareo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Kareo's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Medical Software
- Electronic Health Records
- Practice Management
- Medical Billing
- Patient Scheduling
- Clinical Data
- Insurance Eligibility
- HIPAA
---

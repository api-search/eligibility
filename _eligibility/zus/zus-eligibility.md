---
api_specs:
- filename: zus-auth-api-openapi.yml
  format: yaml
  label: Zus Health Auth API
  slug: zus-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-auth-api-openapi.yml
- filename: zus-documents-api-openapi.yml
  format: yaml
  label: Zus Health Documents API
  slug: zus-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-documents-api-openapi.yml
- filename: zus-fhir-api-openapi.yml
  format: yaml
  label: Zus Health FHIR API
  slug: zus-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-fhir-api-openapi.yml
- filename: zus-patient-api-openapi.yml
  format: yaml
  label: Zus Health Patient API
  slug: zus-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-api-openapi.yml
- filename: zus-patient-history-api-openapi.yml
  format: yaml
  label: Zus Health Patient History API
  slug: zus-patient-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-history-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: residents of the United States
  entity_types:
  - text: The Website is offered and available only to users who are 18 years old or older, and who are residents of the United States.
    type: individual
  minimum_age:
    text: The Website is offered and available only to users who are 18 years old or older
    value: '18'
  restricted_uses:
  - summary: Non-medical-advice use
    text: Nothing on the Website is intended to be a substitute for professional medical advice, diagnosis, or treatment.
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
name: Zus Health
provenance_date: '2026-11-10'
provider_name: Zus Health
provider_slug: zus
slug: zus-eligibility
source_date: '2026-11-10'
source_filename: zus-eligibility.yml
source_heading: Eligibility
source_page: https://www.zushealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zus Health\naid: zus\nurl: https://www.zushealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: residents of the United States\nentity_types:\n- type: individual\n  text: The Website is offered and available only to users who are 18 years old or older, and who are residents\n    of the United States.\nrestricted_uses:\n- summary: Non-medical-advice use\n  text: Nothing on the Website is intended to be a substitute for professional medical advice, diagnosis, or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Website is offered and available only to users who are 18 years old or older\n"
source_yaml_url: https://artifacts.apis.io/zus/eligibility/zus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zus Health's own page on 2026-11-10.
synthetic: false
tags:
- Health
- FHIR
- Interoperability
- Patient Data
- Healthcare
---

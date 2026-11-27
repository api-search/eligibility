---
api_specs:
- filename: xcures-application-api-openapi.yml
  format: yaml
  label: xCures Application API
  slug: xcures-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-application-api-openapi.yml
- filename: xcures-checklist-api-openapi.yml
  format: yaml
  label: xCures Checklist API
  slug: xcures-checklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-checklist-api-openapi.yml
- filename: xcures-clinical-concepts-api-openapi.yml
  format: yaml
  label: xCures Clinical Concepts API
  slug: xcures-clinical-concepts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-clinical-concepts-api-openapi.yml
- filename: xcures-document-api-openapi.yml
  format: yaml
  label: xCures Document API
  slug: xcures-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-document-api-openapi.yml
- filename: xcures-fhir-api-openapi.yml
  format: yaml
  label: xCures FHIR API
  slug: xcures-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-fhir-api-openapi.yml
- filename: xcures-project-api-openapi.yml
  format: yaml
  label: xCures Project API
  slug: xcures-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-project-api-openapi.yml
- filename: xcures-query-api-openapi.yml
  format: yaml
  label: xCures Query API
  slug: xcures-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-query-api-openapi.yml
- filename: xcures-reciprocity-template-api-openapi.yml
  format: yaml
  label: xCures Reciprocity Template API
  slug: xcures-reciprocity-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-reciprocity-template-api-openapi.yml
- filename: xcures-subject-api-openapi.yml
  format: yaml
  label: xCures Subject API
  slug: xcures-subject-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-subject-api-openapi.yml
- filename: xcures-summary-api-openapi.yml
  format: yaml
  label: xCures Summary API
  slug: xcures-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-summary-api-openapi.yml
- filename: xcures-oauth-api-openapi.yml
  format: yaml
  label: xCures O Auth API
  slug: xcures-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use a service as a health care provider, you will be asked to create an account.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: you are not located in, under the control of, or a national or resident of any restricted country or on any such list.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of the account creation process, you will be asked to provide certain information (including identification and contact details)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: xCures
provenance_date: '2026-11-10'
provider_name: xCures
provider_slug: xcures
slug: xcures-eligibility
source_date: '2026-11-10'
source_filename: xcures-eligibility.yml
source_heading: Eligibility
source_page: https://xcures.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: xCures\naid: xcures\nurl: https://xcures.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: To use a service as a health care provider, you will be asked to create an account.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: you are not located in, under the control of, or a national or resident of any restricted country or on\n    any such list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the account creation process, you will be asked to provide\
  \ certain information (including identification\n    and contact details)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xcures/eligibility/xcures-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from xCures's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- Medical Records
- Interoperability
- FHIR
- Oncology
- Real-World Data
- Clinical Data
- Artificial Intelligence
- TEFCA
- Carequality
- Patient Data
- HITRUST
- HIPAA
- A2A
---

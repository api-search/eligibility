---
api_specs:
- filename: buoy-health-complaints-api-openapi.yml
  format: yaml
  label: Buoy Health Complaints API
  slug: buoy-health-complaints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-complaints-api-openapi.yml
- filename: buoy-health-intents-api-openapi.yml
  format: yaml
  label: Buoy Health Intents API
  slug: buoy-health-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-intents-api-openapi.yml
- filename: buoy-health-interviews-api-openapi.yml
  format: yaml
  label: Buoy Health Interviews API
  slug: buoy-health-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-interviews-api-openapi.yml
- filename: buoy-health-queries-api-openapi.yml
  format: yaml
  label: Buoy Health Queries API
  slug: buoy-health-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-queries-api-openapi.yml
- filename: buoy-health-questions-api-openapi.yml
  format: yaml
  label: Buoy Health Questions API
  slug: buoy-health-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-questions-api-openapi.yml
- filename: buoy-health-results-api-openapi.yml
  format: yaml
  label: Buoy Health Results API
  slug: buoy-health-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buoy-health/openapi/buoy-health-results-api-openapi.yml
claim_count: 9
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving the APIs under the applicable laws of the United States.
  entity_types:
  - text: You may not use the APIs and may not accept the Terms if (i) you are not of legal age to form a binding contract with Buoy
    type: individual
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity, then the following applies instead of the paragraph above
    type: government
  minimum_age:
    text: you are not of legal age to form a binding contract with Buoy
    value: legal age
  restricted_uses:
  - summary: Life-critical or safety uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - source: https://www.buoyhealth.com/terms
    summary: Not a medical advice substitute
    text: Buoy is not a substitute for and does not provide professional medical advice, diagnosis, or treatment.
  - source: https://www.buoyhealth.com/terms
    summary: No infants
    text: Please do not use our Services for infants.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain APIs you may be required to provide certain information (such as identification or contact details) as part of the registration process for the APIs
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Buoy Health
provenance_date: '2026-11-09'
provider_name: Buoy Health
provider_slug: buoy-health
slug: buoy-health-eligibility
source_date: '2026-11-09'
source_filename: buoy-health-eligibility.yml
source_heading: Eligibility
source_page: https://static.buoyhealth.com/Buoy+API+Terms+of+Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buoy Health\naid: buoy-health\nurl: https://static.buoyhealth.com/Buoy+API+Terms+of+Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://static.buoyhealth.com/Buoy+API+Terms+of+Service.pdf\n  - https://www.buoyhealth.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving\n    the APIs under the applicable laws of the United States.\nentity_types:\n- type: individual\n  text: You may not use the APIs and may not accept the Terms if (i) you are not of legal age to form a binding\n    contract\
  \ with Buoy\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\n- type: government\n  text: If you are accepting the Terms on behalf of a United States federal government entity, then the following\n    applies instead of the paragraph above\nrestricted_uses:\n- summary: Life-critical or safety uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: Not a medical advice substitute\n  text: Buoy is not a substitute for and does not provide professional medical advice, diagnosis, or treatment.\n  source: https://www.buoyhealth.com/terms\n- summary: No infants\n  text: Please do not use our Services for infants.\n  source: https://www.buoyhealth.com/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain APIs you may be\
  \ required to provide certain information (such as identification\n    or contact details) as part of the registration process for the APIs\nminimum_age:\n  value: legal age\n  text: you are not of legal age to form a binding contract with Buoy\n"
source_yaml_url: https://artifacts.apis.io/buoy-health/eligibility/buoy-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 9 quoted statements, read from Buoy Health's own page on 2026-11-09.
synthetic: false
tags:
- Symptom Checker
- medical-triage
- Digital Health
- Healthcare
- Clinical AI
- Care Navigation
- Patient Engagement
- Diagnosis
- Telehealth
- OAuth
- Authentication
---

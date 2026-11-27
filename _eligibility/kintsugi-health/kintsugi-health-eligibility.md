---
api_specs:
- filename: kintsugi-health-feedback-api-openapi.yml
  format: yaml
  label: Kintsugi Health Feedback API
  slug: kintsugi-health-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-feedback-api-openapi.yml
- filename: kintsugi-health-initiate-api-openapi.yml
  format: yaml
  label: Kintsugi Health Initiate API
  slug: kintsugi-health-initiate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-initiate-api-openapi.yml
- filename: kintsugi-health-kintsugi-health-api-api-openapi.yml
  format: yaml
  label: Kintsugi Health Kintsugi Health API
  slug: kintsugi-health-kintsugi-health-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-kintsugi-health-api-api-openapi.yml
- filename: kintsugi-health-predict-api-openapi.yml
  format: yaml
  label: Kintsugi Health Predict API
  slug: kintsugi-health-predict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-predict-api-openapi.yml
- filename: kintsugi-health-prediction-api-openapi.yml
  format: yaml
  label: Kintsugi Health Prediction API
  slug: kintsugi-health-prediction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-prediction-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Kintsugi Properties are controlled and offered by Kintsugi from its facilities in the United States of America. Kintsugi makes no representations that Kintsugi Properties are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KINTSUGI
    type: individual
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE APPLICATION.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KINTSUGI
    value: legal age
  restricted_uses:
  - summary: Not for emergency medical needs
    text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL NEEDS.
  - summary: Not a substitute for professional medical advice
    text: Kintsugi’s Services, including Kintsugi Concierge Representatives, are not intended to provide medical advice to users
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
name: Kintsugi Health
provenance_date: '2026-11-09'
provider_name: Kintsugi Health
provider_slug: kintsugi-health
slug: kintsugi-health-eligibility
source_date: '2026-11-09'
source_filename: kintsugi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.kintsugihealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kintsugi Health\naid: kintsugi-health\nurl: https://www.kintsugihealth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Kintsugi Properties are controlled and offered by Kintsugi from its facilities in the United States of America.\n    Kintsugi makes no representations that Kintsugi Properties are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KINTSUGI\n- type: business\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE,\
  \ IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE APPLICATION.\nrestricted_uses:\n- summary: Not for emergency medical needs\n  text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL NEEDS.\n- summary: Not a substitute for professional medical advice\n  text: Kintsugi’s Services, including Kintsugi Concierge Representatives, are not intended to provide medical advice\n    to users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KINTSUGI\n"
source_yaml_url: https://artifacts.apis.io/kintsugi-health/eligibility/kintsugi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Kintsugi Health's own page on 2026-11-09.
synthetic: false
tags:
- Health Tech
- Artificial Intelligence
- Voice Analytics
- Mental Health
- Digital Health
---

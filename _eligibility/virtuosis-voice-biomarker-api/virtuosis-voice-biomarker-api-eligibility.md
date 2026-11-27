---
api_specs:
- filename: virtuosis-voice-biomarker-api-accounts-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Accounts API
  slug: virtuosis-voice-biomarker-api-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-accounts-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-recordings-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Recordings API
  slug: virtuosis-voice-biomarker-api-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-recordings-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-usage-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Usage API
  slug: virtuosis-voice-biomarker-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-usage-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-ping-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Ping API
  slug: virtuosis-voice-biomarker-api-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-ping-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: personal use by a consumer
    type: individual
  minimum_age:
    text: An individual below the legal age of majority may use a Service only through or with a parent or legal representative, and only where the Service is intended for minors.
    value: null
  restricted_uses:
  - summary: No emotion inference in workplace or education
    text: use the Services to infer emotions of individuals in a workplace or educational setting, except where permitted for medical or safety reasons
  - summary: No sole-basis automated decisions
    text: use outputs as the sole basis for an emergency, diagnosis, treatment, employment, insurance or other decision with legal or similarly significant effects
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
name: Virtuosis Voice Biomarker API
provenance_date: '2026-11-10'
provider_name: Virtuosis Voice Biomarker API
provider_slug: virtuosis-voice-biomarker-api
slug: virtuosis-voice-biomarker-api-eligibility
source_date: '2026-11-10'
source_filename: virtuosis-voice-biomarker-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.virtuosis.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virtuosis Voice Biomarker API\naid: virtuosis-voice-biomarker-api\nurl: https://www.virtuosis.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: personal use by a consumer\nrestricted_uses:\n- summary: No emotion inference in workplace or education\n  text: use the Services to infer emotions of individuals in a workplace or educational setting, except where permitted\n    for medical or safety reasons\n- summary: No sole-basis automated decisions\n  text: use outputs as the sole basis for an emergency, diagnosis, treatment,\
  \ employment, insurance or other decision\n    with legal or similarly significant effects\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: An individual below the legal age of majority may use a Service only through or with a parent or legal representative,\n    and only where the Service is intended for minors.\n"
source_yaml_url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/eligibility/virtuosis-voice-biomarker-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Virtuosis Voice Biomarker API's own page on 2026-11-10.
synthetic: false
tags:
- Digital Health
- VoiceBiomarkers
- Speech Analysis
- acoustic analysis
- Medical Devices
- Mental Health
- Wellbeing
- neurodegenerative screening
- Telehealth
- Remote Monitoring
- communication coaching
- Clinical Research
- Health AI
- Clinical Decision Support
---

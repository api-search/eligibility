---
api_specs:
- filename: vera-health-chat-api-openapi.yml
  format: yaml
  label: Vera Health Chat API
  slug: vera-health-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vera-health/openapi/vera-health-chat-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: you warrant that you (as an individual or as a representative of any entity on whose behalf you use the Services) are not located in, or a resident of, any country that is subject to applicable U.S. trade sanctions or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea, Donetsk, or Luhansk regions).
  entity_types:
  - text: By using the Services, you acknowledge you are a healthcare professional (in practice or in training)
    type: individual
  - text: If you are using the Services on behalf of an organization, you are agreeing to these Terms on behalf of that organization
    type: business
  minimum_age:
    text: The Services are meant for use only by those over 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No patient-specific clinical use
    text: The Services do not provide, and shall not be used to obtain, diagnoses, treatment recommendations or any other output related to a specific patient’s medical condition.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By registering and using the Services, you also affirm that you are or are training to be a qualified healthcare professional in each applicable jurisdiction.
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vera Health
provenance_date: '2026-11-10'
provider_name: Vera Health
provider_slug: vera-health
slug: vera-health-eligibility
source_date: '2026-11-10'
source_filename: vera-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.verahealth.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vera Health\naid: vera-health\nurl: https://www.verahealth.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: you warrant that you (as an individual or as a representative of any entity on whose behalf you use the\n    Services) are not located in, or a resident of, any country that is subject to applicable U.S. trade sanctions\n    or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea, Donetsk, or Luhansk regions).\nentity_types:\n- type: individual\n  text: By using the Services, you acknowledge you are a healthcare\
  \ professional (in practice or in training)\n- type: business\n  text: If you are using the Services on behalf of an organization, you are agreeing to these Terms on behalf of\n    that organization\nrestricted_uses:\n- summary: No patient-specific clinical use\n  text: The Services do not provide, and shall not be used to obtain, diagnoses, treatment recommendations or any\n    other output related to a specific patient’s medical condition.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By registering and using the Services, you also affirm that you are or are training to be a qualified healthcare\n    professional in each applicable jurisdiction.\nminimum_age:\n  value: '18'\n  text: The Services are meant for use only by those over 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/vera-health/eligibility/vera-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Vera Health's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Artificial Intelligence
- Clinical Decision Support
- Medical Knowledge
- Healthcare
---

---
api_specs:
- filename: moondream-openai-compatibility-api-openapi.yml
  format: yaml
  label: Moondream OpenAI Compatibility API
  slug: moondream-openai-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moondream/openapi/moondream-openai-compatibility-api-openapi.yml
- filename: moondream-skills-api-openapi.yml
  format: yaml
  label: Moondream Skills API
  slug: moondream-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moondream/openapi/moondream-skills-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any embargoed country or region.
  entity_types:
  - text: you have the authority to enter into these Terms personally
    type: individual
  - text: if you are accessing or using the Service on behalf of an entity, on behalf of the entity identified in the order form or account registration process
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Biometric, children's and special-category data
    text: You shall not use the Service to process biometric data, personal data of children, or other special categories of personal data as defined under applicable data protection laws without M87 Labs' prior written consent.
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
name: Moondream
provenance_date: '2026-11-10'
provider_name: Moondream
provider_slug: moondream
slug: moondream-eligibility
source_date: '2026-11-10'
source_filename: moondream-eligibility.yml
source_heading: Eligibility
source_page: https://moondream.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moondream\naid: moondream\nurl: https://moondream.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any embargoed country or region.\nentity_types:\n- type: individual\n  text: you have the authority to enter into these Terms personally\n- type: business\n  text: if you are accessing or using the Service on behalf of an entity, on behalf of the entity identified in\n    the order form or account registration process\nrestricted_uses:\n- summary: Biometric, children's\
  \ and special-category data\n  text: You shall not use the Service to process biometric data, personal data of children, or other special categories\n    of personal data as defined under applicable data protection laws without M87 Labs' prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/moondream/eligibility/moondream-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Moondream's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Vision Language Model
- Object Detection
- Image Captioning
- OCR
- Developer Tools
---

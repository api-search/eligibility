---
api_specs:
- filename: autoderm-ai-dermatology-api-device-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Device API
  slug: autoderm-ai-dermatology-api-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-device-api-openapi.yml
- filename: autoderm-ai-dermatology-api-inference-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Inference API
  slug: autoderm-ai-dermatology-api-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-inference-api-openapi.yml
- filename: autoderm-ai-dermatology-api-system-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API System API
  slug: autoderm-ai-dermatology-api-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-system-api-openapi.yml
- filename: autoderm-ai-dermatology-api-utils-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Utils API
  slug: autoderm-ai-dermatology-api-utils-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-utils-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - US
    served:
    - EU
    - GB
    text: The service is CE-marked for use in the EU and the United Kingdom. Use in the United States of America is for demonstration purposes only pending FDA clearance; it must not be used by US residents for medical guidance.
  entity_types:
  - text: The service is intended for persons capable of forming legally binding contracts.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Users lacking cognitive capacity
    text: by users who lack the cognitive capacity to understand that outputs are informational and not a diagnosis
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Autoderm – AI Dermatology API
provenance_date: '2026-11-09'
provider_name: Autoderm – AI Dermatology API
provider_slug: autoderm-ai-dermatology-api
slug: autoderm-ai-dermatology-api-eligibility
source_date: '2026-11-09'
source_filename: autoderm-ai-dermatology-api-eligibility.yml
source_heading: Eligibility
source_page: https://autoderm.ai/terms-of-service-autoderm/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autoderm – AI Dermatology API\naid: autoderm-ai-dermatology-api\nurl: https://autoderm.ai/terms-of-service-autoderm/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EU\n  - GB\n  excluded:\n  - US\n  text: The service is CE-marked for use in the EU and the United Kingdom. Use in the United States of America is\n    for demonstration purposes only pending FDA clearance; it must not be used by US residents for medical guidance.\nentity_types:\n- type: individual\n  text: The service is intended for persons capable of forming legally binding contracts.\nrestricted_uses:\n- summary: Users lacking cognitive\
  \ capacity\n  text: by users who lack the cognitive capacity to understand that outputs are informational and not a diagnosis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/autoderm-ai-dermatology-api/eligibility/autoderm-ai-dermatology-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Autoderm – AI Dermatology API's own page on 2026-11-09.
synthetic: false
tags:
- dermatology-api
- ai-dermatology
- Medical Imaging
- Telehealth
- skin-analysis
- REST API
- OpenAPI
- Llms.txt
- ce-marked
- White Label
- Healthcare
- Medical AI
- Computer Vision
- Medical Devices
- ICD-10
- image-classification
- Clinical Decision Support
- triage
---

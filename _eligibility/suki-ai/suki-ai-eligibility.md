---
api_specs:
- filename: suki-ai-ambient-content-api-openapi.yml
  format: yaml
  label: Suki AI Ambient Content API
  slug: suki-ai-ambient-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-ambient-content-api-openapi.yml
- filename: suki-ai-ambient-sessions-api-openapi.yml
  format: yaml
  label: Suki AI Ambient Sessions API
  slug: suki-ai-ambient-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-ambient-sessions-api-openapi.yml
- filename: suki-ai-authentication-api-openapi.yml
  format: yaml
  label: Suki AI Authentication API
  slug: suki-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-authentication-api-openapi.yml
- filename: suki-ai-feedback-api-openapi.yml
  format: yaml
  label: Suki AI Feedback API
  slug: suki-ai-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-feedback-api-openapi.yml
- filename: suki-ai-form-filling-content-api-openapi.yml
  format: yaml
  label: Suki AI Form Filling Content API
  slug: suki-ai-form-filling-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-form-filling-content-api-openapi.yml
- filename: suki-ai-form-filling-sessions-api-openapi.yml
  format: yaml
  label: Suki AI Form Filling Sessions API
  slug: suki-ai-form-filling-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-form-filling-sessions-api-openapi.yml
- filename: suki-ai-info-api-openapi.yml
  format: yaml
  label: Suki AI Info API
  slug: suki-ai-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-info-api-openapi.yml
- filename: suki-ai-notifications-api-openapi.yml
  format: yaml
  label: Suki AI Notifications API
  slug: suki-ai-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-notifications-api-openapi.yml
- filename: suki-ai-user-preferences-api-openapi.yml
  format: yaml
  label: Suki AI User Preferences API
  slug: suki-ai-user-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-user-preferences-api-openapi.yml
- filename: suki-ai-content-api-openapi.yml
  format: yaml
  label: Suki AI Content API
  slug: suki-ai-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-content-api-openapi.yml
- filename: suki-ai-preferences-api-openapi.yml
  format: yaml
  label: Suki AI Preferences API
  slug: suki-ai-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-preferences-api-openapi.yml
- filename: suki-ai-sessions-api-openapi.yml
  format: yaml
  label: Suki AI Sessions API
  slug: suki-ai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-sessions-api-openapi.yml
- filename: suki-ai-templates-api-openapi.yml
  format: yaml
  label: Suki AI Templates API
  slug: suki-ai-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/suki-ai/openapi/suki-ai-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Suki Platform on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  - text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use, duplication, reproduction, release, modification, disclosure, or transfer of the Suki Platform
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Ambient capture limited to patient-provider conversations
    text: Customer will ensure that all Authorized Users only use Ambient Capture features to monitor and record patient conversations with physicians or other healthcare providers and for no other purpose.
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
name: Suki AI
provenance_date: '2026-11-10'
provider_name: Suki AI
provider_slug: suki-ai
slug: suki-ai-eligibility
source_date: '2026-11-10'
source_filename: suki-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.suki.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Suki AI\naid: suki-ai\nurl: https://www.suki.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Suki Platform on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\n- type: government\n  text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use,\n    duplication, reproduction, release, modification, disclosure, or transfer of the Suki Platform\nrestricted_uses:\n\
  - summary: Ambient capture limited to patient-provider conversations\n  text: Customer will ensure that all Authorized Users only use Ambient Capture features to monitor and record patient\n    conversations with physicians or other healthcare providers and for no other purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/suki-ai/eligibility/suki-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Suki AI's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Ambient AI
- Clinical Documentation
- Voice AI
- Speech Recognition
- EHR Integration
- SDK
- Dictation
- Real-Time
---

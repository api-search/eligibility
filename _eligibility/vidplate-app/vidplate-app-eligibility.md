---
api_specs:
- filename: vidplate-app-account-api-openapi.yml
  format: yaml
  label: VidPlate Account API
  slug: vidplate-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-account-api-openapi.yml
- filename: vidplate-app-render-nodes-api-openapi.yml
  format: yaml
  label: VidPlate Render nodes API
  slug: vidplate-app-render-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-render-nodes-api-openapi.yml
- filename: vidplate-app-render-presets-api-openapi.yml
  format: yaml
  label: VidPlate Render presets API
  slug: vidplate-app-render-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-render-presets-api-openapi.yml
- filename: vidplate-app-renders-api-openapi.yml
  format: yaml
  label: VidPlate Renders API
  slug: vidplate-app-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-renders-api-openapi.yml
- filename: vidplate-app-storage-destinations-api-openapi.yml
  format: yaml
  label: VidPlate Storage destinations API
  slug: vidplate-app-storage-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-storage-destinations-api-openapi.yml
- filename: vidplate-app-templates-api-openapi.yml
  format: yaml
  label: VidPlate Templates API
  slug: vidplate-app-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-templates-api-openapi.yml
- filename: vidplate-app-uploads-api-openapi.yml
  format: yaml
  label: VidPlate Uploads API
  slug: vidplate-app-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-uploads-api-openapi.yml
- filename: vidplate-app-webhook-endpoints-api-openapi.yml
  format: yaml
  label: VidPlate Webhook endpoints API
  slug: vidplate-app-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-webhook-endpoints-api-openapi.yml
claim_count: 2
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
  - summary: AI misuse restrictions
    text: 'Users must not use AI-powered features to generate, distribute, or facilitate:'
  - summary: Sensitive personal data
    text: Users must not upload or transfer sensitive personal data, including but not limited to health data, biometric data, or financial data subject to special regulations.
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
name: VidPlate
provenance_date: '2026-11-10'
provider_name: VidPlate
provider_slug: vidplate-app
slug: vidplate-app-eligibility
source_date: '2026-11-10'
source_filename: vidplate-app-eligibility.yml
source_heading: Eligibility
source_page: https://vidplate.app/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VidPlate\naid: vidplate-app\nurl: https://vidplate.app/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: AI misuse restrictions\n  text: 'Users must not use AI-powered features to generate, distribute, or facilitate:'\n- summary: Sensitive personal data\n  text: Users must not upload or transfer sensitive personal data, including but not limited to health data, biometric\n    data, or financial data subject to special regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vidplate-app/eligibility/vidplate-app-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from VidPlate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Rendering
- 3D
- Templates
---

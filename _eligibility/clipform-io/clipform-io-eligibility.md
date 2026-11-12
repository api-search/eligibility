---
api_specs:
- filename: clipform-io-analytics-api-openapi.yml
  format: yaml
  label: Clipform Analytics API
  slug: clipform-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-analytics-api-openapi.yml
- filename: clipform-io-authentication-api-openapi.yml
  format: yaml
  label: Clipform Authentication API
  slug: clipform-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-authentication-api-openapi.yml
- filename: clipform-io-dynamic-links-api-openapi.yml
  format: yaml
  label: Clipform Dynamic Links API
  slug: clipform-io-dynamic-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-dynamic-links-api-openapi.yml
- filename: clipform-io-forms-api-openapi.yml
  format: yaml
  label: Clipform Forms API
  slug: clipform-io-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-forms-api-openapi.yml
- filename: clipform-io-integrations-api-openapi.yml
  format: yaml
  label: Clipform Integrations API
  slug: clipform-io-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-integrations-api-openapi.yml
- filename: clipform-io-node-media-api-openapi.yml
  format: yaml
  label: Clipform Node Media API
  slug: clipform-io-node-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-node-media-api-openapi.yml
- filename: clipform-io-nodes-api-openapi.yml
  format: yaml
  label: Clipform Nodes API
  slug: clipform-io-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-nodes-api-openapi.yml
- filename: clipform-io-tags-api-openapi.yml
  format: yaml
  label: Clipform Tags API
  slug: clipform-io-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-tags-api-openapi.yml
- filename: clipform-io-tracked-links-api-openapi.yml
  format: yaml
  label: Clipform Tracked Links API
  slug: clipform-io-tracked-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-tracked-links-api-openapi.yml
- filename: clipform-io-webhooks-api-openapi.yml
  format: yaml
  label: Clipform Webhooks API
  slug: clipform-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to hold an account.
    value: '18'
  restricted_uses:
  - summary: Sensitive data collection
    text: You must not use forms to collect passwords or login credentials, payment card numbers, or government-issued identification numbers or documents.
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
name: Clipform
provenance_date: '2026-11-09'
provider_name: Clipform
provider_slug: clipform-io
slug: clipform-io-eligibility
source_date: '2026-11-09'
source_filename: clipform-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.clipform.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clipform\naid: clipform-io\nurl: https://www.clipform.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive data collection\n  text: You must not use forms to collect passwords or login credentials, payment card numbers, or government-issued\n    identification numbers or documents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/clipform-io/eligibility/clipform-io-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Clipform's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Forms
- Form Builder
- Video
- Surveys
- Webhooks
- MCP
- Lead Capture
---

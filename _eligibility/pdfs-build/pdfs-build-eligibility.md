---
api_specs:
- filename: pdfs-build-delegated-agents-api-openapi.yml
  format: yaml
  label: pdfs-build Delegated agents API
  slug: pdfs-build-delegated-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-delegated-agents-api-openapi.yml
- filename: pdfs-build-embedded-editor-api-openapi.yml
  format: yaml
  label: pdfs-build Embedded editor API
  slug: pdfs-build-embedded-editor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-embedded-editor-api-openapi.yml
- filename: pdfs-build-legacy-v1-api-openapi.yml
  format: yaml
  label: pdfs-build Legacy v1 API
  slug: pdfs-build-legacy-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-legacy-v1-api-openapi.yml
- filename: pdfs-build-render-jobs-api-openapi.yml
  format: yaml
  label: pdfs-build Render jobs API
  slug: pdfs-build-render-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-render-jobs-api-openapi.yml
- filename: pdfs-build-render-logs-api-openapi.yml
  format: yaml
  label: pdfs-build Render logs API
  slug: pdfs-build-render-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-render-logs-api-openapi.yml
- filename: pdfs-build-rendering-api-openapi.yml
  format: yaml
  label: pdfs-build Rendering API
  slug: pdfs-build-rendering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-rendering-api-openapi.yml
- filename: pdfs-build-template-gallery-api-openapi.yml
  format: yaml
  label: pdfs-build Template gallery API
  slug: pdfs-build-template-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-template-gallery-api-openapi.yml
- filename: pdfs-build-templates-api-openapi.yml
  format: yaml
  label: pdfs-build Templates API
  slug: pdfs-build-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-templates-api-openapi.yml
- filename: pdfs-build-webhooks-api-openapi.yml
  format: yaml
  label: pdfs-build Webhooks API
  slug: pdfs-build-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract in your jurisdiction.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Regulated data submissions
    text: Do not submit special-category, health, financial-account, government-identification, children's, export-controlled, or other regulated data unless we have agreed in writing that the Service and relevant providers are suitable for it.
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
name: pdfs-build
provenance_date: '2026-11-10'
provider_name: pdfs-build
provider_slug: pdfs-build
slug: pdfs-build-eligibility
source_date: '2026-11-10'
source_filename: pdfs-build-eligibility.yml
source_heading: Eligibility
source_page: https://pdfs.build/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pdfs-build\naid: pdfs-build\nurl: https://pdfs.build/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract in your jurisdiction.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: Regulated data submissions\n  text: Do not submit special-category, health, financial-account, government-identification, children's, export-controlled,\n\
  \    or other regulated data unless we have agreed in writing that the Service and relevant providers are suitable\n    for it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/pdfs-build/eligibility/pdfs-build-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from pdfs-build's own page on 2026-11-10.
synthetic: false
tags:
- PDF
- Template Engine
- Rendering
- Software-as-a-Service
- Document Generation
---

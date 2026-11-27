---
api_specs:
- filename: dify-conversations-api-openapi.yml
  format: yaml
  label: Dify Conversations API
  slug: dify-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-conversations-api-openapi.yml
- filename: dify-files-api-openapi.yml
  format: yaml
  label: Dify Files API
  slug: dify-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-files-api-openapi.yml
- filename: dify-applications-api-openapi.yml
  format: yaml
  label: Dify Applications API
  slug: dify-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-applications-api-openapi.yml
- filename: dify-annotations-api-openapi.yml
  format: yaml
  label: Dify Annotations API
  slug: dify-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-annotations-api-openapi.yml
- filename: dify-audio-api-openapi.yml
  format: yaml
  label: Dify Audio API
  slug: dify-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-audio-api-openapi.yml
- filename: dify-feedback-api-openapi.yml
  format: yaml
  label: Dify Feedback API
  slug: dify-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-feedback-api-openapi.yml
- filename: dify-end-users-api-openapi.yml
  format: yaml
  label: Dify End Users API
  slug: dify-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-end-users-api-openapi.yml
- filename: dify-human-input-api-openapi.yml
  format: yaml
  label: Dify Human Input API
  slug: dify-human-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-human-input-api-openapi.yml
- filename: dify-documents-api-openapi.yml
  format: yaml
  label: Dify Documents API
  slug: dify-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-documents-api-openapi.yml
- filename: dify-chunks-api-openapi.yml
  format: yaml
  label: Dify Chunks API
  slug: dify-chunks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-chunks-api-openapi.yml
- filename: dify-tags-api-openapi.yml
  format: yaml
  label: Dify Knowledge Tags API
  slug: dify-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-tags-api-openapi.yml
- filename: dify-metadata-api-openapi.yml
  format: yaml
  label: Dify Metadata API
  slug: dify-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-metadata-api-openapi.yml
- filename: dify-models-api-openapi.yml
  format: yaml
  label: Dify Models API
  slug: dify-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-models-api-openapi.yml
- filename: dify-knowledge-pipeline-api-openapi.yml
  format: yaml
  label: Dify Knowledge Pipeline API
  slug: dify-knowledge-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-knowledge-pipeline-api-openapi.yml
- filename: dify-chat-messages-api-openapi.yml
  format: yaml
  label: Dify Chat Messages API
  slug: dify-chat-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-chat-messages-api-openapi.yml
- filename: dify-completion-messages-api-openapi.yml
  format: yaml
  label: Dify Completion Messages API
  slug: dify-completion-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-completion-messages-api-openapi.yml
- filename: dify-knowledge-bases-api-openapi.yml
  format: yaml
  label: Dify Knowledge Bases API
  slug: dify-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-knowledge-bases-api-openapi.yml
- filename: dify-workflow-runs-api-openapi.yml
  format: yaml
  label: Dify Workflow Runs API
  slug: dify-workflow-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dify/openapi/dify-workflow-runs-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, under the control of, or a national or resident of any country against which the United States currently has sanctions.
  entity_types:
  - text: in the case of an individual accepting this Agreement on his or her own behalf, such individual
    type: individual
  - text: “You” or “Your” means you or the entity that you represent in accepting these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities and sensitive data
    text: You may not access or use the Service for any High-Risk Activities or to upload or transmit any Sensitive Personal Data.
  - summary: Automated decisions without human supervision
    text: (3) to make automated decisions that may have a detrimental impact on individual rights without appropriate human supervision
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must create a username and password and provide us with the information required during the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dify
provenance_date: '2026-11-09'
provider_name: Dify
provider_slug: dify
slug: dify-eligibility
source_date: '2026-11-09'
source_filename: dify-eligibility.yml
source_heading: Eligibility
source_page: https://dify.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dify\naid: dify\nurl: https://dify.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, under the control of, or a national or resident of any country against which the\n    United States currently has sanctions.\nentity_types:\n- type: individual\n  text: in the case of an individual accepting this Agreement on his or her own behalf, such individual\n- type: business\n  text: “You” or “Your” means you or the entity that you represent in accepting these Terms.\nrestricted_uses:\n- summary: High-risk activities and sensitive data\n  text:\
  \ You may not access or use the Service for any High-Risk Activities or to upload or transmit any Sensitive\n    Personal Data.\n- summary: Automated decisions without human supervision\n  text: (3) to make automated decisions that may have a detrimental impact on individual rights without appropriate\n    human supervision\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must create a username and password and provide us with the information required during the registration\n    process\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dify/eligibility/dify-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Dify's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLMOps
- Backend-as-a-Service
- Agents
- Workflows
- Knowledge Management
- RAG
- MCP
- Low-Code
- Open Source
- A2A
---

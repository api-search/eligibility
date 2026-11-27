---
api_specs:
- filename: copyai-copy-ai-api-api-openapi.yml
  format: yaml
  label: Copy.ai Copy.ai API
  slug: copyai-copy-ai-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyai/openapi/copyai-copy-ai-api-api-openapi.yml
- filename: copyai-webhook-api-openapi.yml
  format: yaml
  label: Copy.ai Webhook API
  slug: copyai-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyai/openapi/copyai-webhook-api-openapi.yml
- filename: copyai-workflow-api-openapi.yml
  format: yaml
  label: Copy.ai Workflow API
  slug: copyai-workflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyai/openapi/copyai-workflow-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: Provide or upload any information to the Services that is “Protected Health Information” as defined under the Health Insurance Portability and Accountability Act
  - summary: Electoral campaign content
    text: generating content for dissemination in electoral campaigns
  - summary: Embargoed countries
    text: accessing or authorizing anyone to access the Services from an embargoed country as prohibited by the United States government
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may need to provide additional information to verify your identity before completing your Subscription
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Copy.ai
provenance_date: '2026-11-09'
provider_name: Copy.ai
provider_slug: copyai
slug: copyai-eligibility
source_date: '2026-11-09'
source_filename: copyai-eligibility.yml
source_heading: Eligibility
source_page: https://www.copy.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copy.ai\naid: copyai\nurl: https://www.copy.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Protected health information\n  text: Provide or upload any information to the Services that is “Protected Health Information” as defined under\n    the Health Insurance Portability and Accountability\
  \ Act\n- summary: Electoral campaign content\n  text: generating content for dissemination in electoral campaigns\n- summary: Embargoed countries\n  text: accessing or authorizing anyone to access the Services from an embargoed country as prohibited by the United\n    States government\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Subscription\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/copyai/eligibility/copyai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Copy.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Content Generation
- Automation
- Software-as-a-Service
- Company
---

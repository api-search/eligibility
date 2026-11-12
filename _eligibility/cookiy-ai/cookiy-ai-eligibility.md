---
api_specs:
- filename: cookiy-ai-quant-surveys-api-openapi.yml
  format: yaml
  label: Cookiy AI Quant Surveys API
  slug: cookiy-ai-quant-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-quant-surveys-api-openapi.yml
- filename: cookiy-ai-studies-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies API
  slug: cookiy-ai-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-api-openapi.yml
- filename: cookiy-ai-studies-checkout-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Checkout API
  slug: cookiy-ai-studies-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-checkout-api-openapi.yml
- filename: cookiy-ai-studies-discussion-guide-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Discussion Guide API
  slug: cookiy-ai-studies-discussion-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-discussion-guide-api-openapi.yml
- filename: cookiy-ai-studies-interviews-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Interviews API
  slug: cookiy-ai-studies-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-interviews-api-openapi.yml
- filename: cookiy-ai-studies-recruit-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Recruit API
  slug: cookiy-ai-studies-recruit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-recruit-api-openapi.yml
- filename: cookiy-ai-studies-report-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Report API
  slug: cookiy-ai-studies-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-report-api-openapi.yml
- filename: cookiy-ai-studies-synthetic-interview-api-openapi.yml
  format: yaml
  label: Cookiy AI Studies / Synthetic Interview API
  slug: cookiy-ai-studies-synthetic-interview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-studies-synthetic-interview-api-openapi.yml
- filename: cookiy-ai-user-api-openapi.yml
  format: yaml
  label: Cookiy AI User API
  slug: cookiy-ai-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiy-ai/openapi/cookiy-ai-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for business use.
    type: business
  minimum_age:
    text: you are at least 18 years of age (or the age of majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: Under-18 individuals and children
    text: The Service is not directed at children, and individuals under 18 may not create accounts or independently participate in the Service.
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
name: Cookiy AI
provenance_date: '2026-11-09'
provider_name: Cookiy AI
provider_slug: cookiy-ai
slug: cookiy-ai-eligibility
source_date: '2026-11-09'
source_filename: cookiy-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cookiy.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cookiy AI\naid: cookiy-ai\nurl: https://cookiy.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended solely for business use.\nrestricted_uses:\n- summary: Under-18 individuals and children\n  text: The Service is not directed at children, and individuals under 18 may not create accounts or independently\n    participate in the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age (or the age of majority\
  \ in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/cookiy-ai/eligibility/cookiy-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cookiy AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- User Research
- AI Interviews
- Surveys
- Market Research
- Participant Recruitment
- Qualitative Research
- Agent Skills
- AI Agents
---

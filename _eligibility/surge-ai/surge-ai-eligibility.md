---
api_specs:
- filename: surge-ai-projects-api-openapi.yml
  format: yaml
  label: Surge AI Projects API
  slug: surge-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surge-ai/openapi/surge-ai-projects-api-openapi.yml
- filename: surge-ai-tasks-api-openapi.yml
  format: yaml
  label: Surge AI Tasks API
  slug: surge-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surge-ai/openapi/surge-ai-tasks-api-openapi.yml
- filename: surge-ai-teams-api-openapi.yml
  format: yaml
  label: Surge AI Teams API
  slug: surge-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surge-ai/openapi/surge-ai-teams-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years of age to use our Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited conduct
    text: Use our Services for any illegal or unauthorized purpose, or engage in, encourage or promote any activity that violates these Terms.
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
name: Surge AI
provenance_date: '2026-11-10'
provider_name: Surge AI
provider_slug: surge-ai
slug: surge-ai-eligibility
source_date: '2026-11-10'
source_filename: surge-ai-eligibility.yml
source_heading: Eligibility
source_page: https://surgehq.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Surge AI\naid: surge-ai\nurl: https://surgehq.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited conduct\n  text: Use our Services for any illegal or unauthorized purpose, or engage in, encourage or promote any activity\n    that violates these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/surge-ai/eligibility/surge-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Surge AI's own page on 2026-11-10.
synthetic: false
tags:
- Human Data
- RLHF
- SFT
- Rubrics
- Verifiers
- RL Environments
- Multi-Modal
- Internationalization
- Labeling
---

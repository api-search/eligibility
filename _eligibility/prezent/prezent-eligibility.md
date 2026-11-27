---
api_specs:
- filename: prezent-audiences-api-openapi.yml
  format: yaml
  label: Prezent Audiences API
  slug: prezent-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-audiences-api-openapi.yml
- filename: prezent-autogenerator-api-openapi.yml
  format: yaml
  label: Prezent AutoGenerator API
  slug: prezent-autogenerator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-autogenerator-api-openapi.yml
- filename: prezent-file-access-api-openapi.yml
  format: yaml
  label: Prezent File Access API
  slug: prezent-file-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-file-access-api-openapi.yml
- filename: prezent-health-api-openapi.yml
  format: yaml
  label: Prezent Health API
  slug: prezent-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-health-api-openapi.yml
- filename: prezent-streaming-api-openapi.yml
  format: yaml
  label: Prezent Streaming API
  slug: prezent-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-streaming-api-openapi.yml
- filename: prezent-template-converter-api-openapi.yml
  format: yaml
  label: Prezent Template Converter API
  slug: prezent-template-converter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-template-converter-api-openapi.yml
- filename: prezent-themes-api-openapi.yml
  format: yaml
  label: Prezent Themes API
  slug: prezent-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-themes-api-openapi.yml
- filename: prezent-upload-api-openapi.yml
  format: yaml
  label: Prezent Upload API
  slug: prezent-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-upload-api-openapi.yml
- filename: prezent-webhooks-api-openapi.yml
  format: yaml
  label: Prezent Webhooks API
  slug: prezent-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prezent/openapi/prezent-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You shall not permit Members to access or use any Service in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: if you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity and its affiliates to these terms and conditions
    type: business
  - text: Member Means an individual who is authorized by You to use a Service and who is registered with a user ID and password to access the Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitor access restriction
    text: 'access any Service : (i) if You are Prezent’s direct competitor, except with Prezent’s prior written consent'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prezent
provenance_date: '2026-11-10'
provider_name: Prezent
provider_slug: prezent
slug: prezent-eligibility
source_date: '2026-11-10'
source_filename: prezent-eligibility.yml
source_heading: Eligibility
source_page: https://www.prezent.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prezent\naid: prezent\nurl: https://www.prezent.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You shall not permit Members to access or use any Service in a U.S. embargoed country (currently Cuba, Iran,\n    North Korea, Sudan, Syria or Crimea)\nentity_types:\n- type: business\n  text: if you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity and its affiliates to these terms and conditions\n- type: individual\n  text: Member Means\
  \ an individual who is authorized by You to use a Service and who is registered with a user ID\n    and password to access the Service.\nrestricted_uses:\n- summary: Competitor access restriction\n  text: 'access any Service : (i) if You are Prezent’s direct competitor, except with Prezent’s prior written consent'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prezent/eligibility/prezent-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Prezent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Presentations
- Generative AI
- AI Agents
- Life Sciences
- Content Generation
- Enterprise
- MCP
- Productivity
---

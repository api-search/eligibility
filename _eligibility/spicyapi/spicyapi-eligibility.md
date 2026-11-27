---
api_specs:
- filename: spicyapi-account-api-openapi.yml
  format: yaml
  label: SpicyAPI Account API
  slug: spicyapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-account-api-openapi.yml
- filename: spicyapi-media-api-openapi.yml
  format: yaml
  label: SpicyAPI Media API
  slug: spicyapi-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-media-api-openapi.yml
- filename: spicyapi-models-api-openapi.yml
  format: yaml
  label: SpicyAPI Models API
  slug: spicyapi-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-models-api-openapi.yml
- filename: spicyapi-openai-compatible-api-openapi.yml
  format: yaml
  label: SpicyAPI OpenAI Compatible API
  slug: spicyapi-openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-openai-compatible-api-openapi.yml
- filename: spicyapi-tasks-api-openapi.yml
  format: yaml
  label: SpicyAPI Tasks API
  slug: spicyapi-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-tasks-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CN
    - GB
    - HK
    - MO
    - SA
    - AE
    - QA
    - KW
    - BH
    - OM
    - PK
    - BD
    - AF
    - ID
    - MY
    - BN
    served: []
    text: We do not offer the service to users in mainland China. We also do not offer the service to users in the United Kingdom, Hong Kong, Macau, Saudi Arabia, the United Arab Emirates, Qatar, Kuwait, Bahrain, Oman, Pakistan, Bangladesh, Afghanistan, Indonesia, Malaysia or Brunei
  entity_types:
  - text: You must be at least 18 years old to hold an account, or the age of majority where you live if that is higher.
    type: individual
  - text: Where you open an account for an organisation, you confirm that you have authority to bind it
    type: business
  minimum_age:
    text: You must be at least 18 years old to hold an account, or the age of majority where you live if that is higher.
    value: '18'
  restricted_uses:
  - summary: Minor sexual content
    text: You may not use the service to generate, request or distribute sexual content involving minors or anyone who appears to be a minor
  - summary: Real child face-swap
    text: to process an image of a real child through a face-swap or head-swap endpoint or a model capable of adult output
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A registered platform account does not verify your end users.
excluded_countries:
- CN
- GB
- HK
- MO
- SA
- AE
- QA
- KW
- BH
- OM
- PK
- BD
- AF
- ID
- MY
- BN
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SpicyAPI
provenance_date: '2026-11-10'
provider_name: SpicyAPI
provider_slug: spicyapi
slug: spicyapi-eligibility
source_date: '2026-11-10'
source_filename: spicyapi-eligibility.yml
source_heading: Eligibility
source_page: https://spicyapi.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SpicyAPI\naid: spicyapi\nurl: https://spicyapi.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CN\n  - GB\n  - HK\n  - MO\n  - SA\n  - AE\n  - QA\n  - KW\n  - BH\n  - OM\n  - PK\n  - BD\n  - AF\n  - ID\n  - MY\n  - BN\n  text: We do not offer the service to users in mainland China. We also do not offer the service to users in the\n    United Kingdom, Hong Kong, Macau, Saudi Arabia, the United Arab Emirates, Qatar, Kuwait, Bahrain, Oman, Pakistan,\n    Bangladesh, Afghanistan, Indonesia, Malaysia or Brunei\nentity_types:\n- type: individual\n  text: You must be at least 18\
  \ years old to hold an account, or the age of majority where you live if that is higher.\n- type: business\n  text: Where you open an account for an organisation, you confirm that you have authority to bind it\nrestricted_uses:\n- summary: Minor sexual content\n  text: You may not use the service to generate, request or distribute sexual content involving minors or anyone\n    who appears to be a minor\n- summary: Real child face-swap\n  text: to process an image of a real child through a face-swap or head-swap endpoint or a model capable of adult\n    output\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A registered platform account does not verify your end users.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to hold an account, or the age of majority where you live if that is higher.\n"
source_yaml_url: https://artifacts.apis.io/spicyapi/eligibility/spicyapi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from SpicyAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative Media
- LLM
- Video Generation
- Image Generation
- Model Aggregator
---

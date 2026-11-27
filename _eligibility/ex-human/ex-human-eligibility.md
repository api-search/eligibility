---
api_specs:
- filename: ex-human-animations-api-openapi.yml
  format: yaml
  label: Ex-Human Animations API
  slug: ex-human-animations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-animations-api-openapi.yml
- filename: ex-human-chatbot-api-openapi.yml
  format: yaml
  label: Ex-Human Chatbot API
  slug: ex-human-chatbot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-chatbot-api-openapi.yml
- filename: ex-human-image-generation-api-openapi.yml
  format: yaml
  label: Ex-Human Image Generation API
  slug: ex-human-image-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-image-generation-api-openapi.yml
- filename: ex-human-text-to-speech-api-openapi.yml
  format: yaml
  label: Ex-Human Text to Speech API
  slug: ex-human-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-text-to-speech-api-openapi.yml
- filename: ex-human-admin-api-openapi.yml
  format: yaml
  label: Ex-Human Admin API
  slug: ex-human-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-admin-api-openapi.yml
- filename: ex-human-metrics-api-openapi.yml
  format: yaml
  label: Ex-Human Metrics API
  slug: ex-human-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex-human/openapi/ex-human-metrics-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
  restricted_uses:
  - summary: United States Federal Government end use
    text: If You are a U.S. federal government end user, our Service is a "Commercial Item" as that term is defined at 48 C.F.R. §2.101.
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
name: Ex-Human
provenance_date: '2026-11-09'
provider_name: Ex-Human
provider_slug: ex-human
slug: ex-human-eligibility
source_date: '2026-11-09'
source_filename: ex-human-eligibility.yml
source_heading: Eligibility
source_page: https://www.privacypolicies.com/live/6e088827-d8ce-4369-bb65-6b0bd4a23146
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ex-Human\naid: ex-human\nurl: https://www.privacypolicies.com/live/6e088827-d8ce-4369-bb65-6b0bd4a23146\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to the United States government embargo, or that has been\n    designated by the United States government as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses:\n- summary:\
  \ United States Federal Government end use\n  text: If You are a U.S. federal government end user, our Service is a \"Commercial Item\" as that term is defined\n    at 48 C.F.R. §2.101.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ex-human/eligibility/ex-human-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ex-Human's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversational AI
- AI Companion
- Generative AI
- Text-to-Speech
- Image Generation
- Video Generation
- Avatars
- Multi-Modal
---

---
api_specs:
- filename: orkas-audio-api-openapi.yml
  format: yaml
  label: Orkas Audio API
  slug: orkas-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-audio-api-openapi.yml
- filename: orkas-images-api-openapi.yml
  format: yaml
  label: Orkas Images API
  slug: orkas-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-images-api-openapi.yml
- filename: orkas-openapi-json-api-openapi.yml
  format: yaml
  label: Orkas Openapi.json API
  slug: orkas-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-openapi-json-api-openapi.yml
- filename: orkas-search-api-openapi.yml
  format: yaml
  label: Orkas Search API
  slug: orkas-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-search-api-openapi.yml
- filename: orkas-videos-api-openapi.yml
  format: yaml
  label: Orkas Videos API
  slug: orkas-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-videos-api-openapi.yml
- filename: orkas-chat-completions-api-openapi.yml
  format: yaml
  label: Orkas Chat Completions API
  slug: orkas-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-chat-completions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old, and the minimum age required by your jurisdiction, to use the Service.
    value: '13'
  restricted_uses:
  - summary: Sanctions/export-barred users
    text: The Service is not intended for users who are barred from receiving it under the laws of their jurisdiction or under any applicable export-control or sanctions regime.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to use the Service. To create an account, you sign in with one of the supported login methods shown in the product
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orkas
provenance_date: '2026-11-10'
provider_name: Orkas
provider_slug: orkas
slug: orkas-eligibility
source_date: '2026-11-10'
source_filename: orkas-eligibility.yml
source_heading: Eligibility
source_page: https://orkas.ai/views/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orkas\naid: orkas\nurl: https://orkas.ai/views/legal/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: Sanctions/export-barred users\n  text: The Service is not intended for users who are barred from receiving it under the laws of their jurisdiction\n    or under any applicable export-control or sanctions regime.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You need an account to use the Service. To create an account, you sign in with one of the supported login\n    methods shown in the product\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old, and the minimum age required by your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/orkas/eligibility/orkas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Orkas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chatbots
- Media
---

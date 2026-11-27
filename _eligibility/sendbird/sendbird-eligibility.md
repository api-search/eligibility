---
api_specs:
- filename: sendbird-channels-api-openapi.yml
  format: yaml
  label: Sendbird Channels API
  slug: sendbird-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbird/openapi/sendbird-channels-api-openapi.yml
- filename: sendbird-messages-api-openapi.yml
  format: yaml
  label: Sendbird Messages API
  slug: sendbird-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbird/openapi/sendbird-messages-api-openapi.yml
- filename: sendbird-moderation-api-openapi.yml
  format: yaml
  label: Sendbird Moderation API
  slug: sendbird-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbird/openapi/sendbird-moderation-api-openapi.yml
- filename: sendbird-users-api-openapi.yml
  format: yaml
  label: Sendbird Users API
  slug: sendbird-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbird/openapi/sendbird-users-api-openapi.yml
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
    - RU
    - BY
    served: []
    text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan,Syria
  entity_types:
  - text: THIS IS A LEGAL AGREEMENT BETWEEN YOU AND THE LEGAL ENTITY YOU REPRESENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consequential automated decisions
    text: Customer shall not use the AI Services or Outputs as substantial factor in making decisions that have a material legal or similarly significant effect on any individual
  - summary: Export and sanctions
    text: Customer agrees that it will not import, export, re-export, transfer or otherwise use the SendBird Platform or SendBird Proprietary Materials in violation of these laws and regulations
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
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sendbird
provenance_date: '2026-11-10'
provider_name: Sendbird
provider_slug: sendbird
slug: sendbird-eligibility
source_date: '2026-11-10'
source_filename: sendbird-eligibility.yml
source_heading: Eligibility
source_page: https://sendbird.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sendbird\naid: sendbird\nurl: https://sendbird.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  - RU\n  - BY\n  text: a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan,Syria\nentity_types:\n- type: business\n  text: THIS IS A LEGAL AGREEMENT BETWEEN YOU AND THE LEGAL ENTITY YOU REPRESENT\nrestricted_uses:\n- summary: Consequential automated decisions\n  text: Customer shall not use the AI Services or Outputs as substantial factor in making decisions that have a\n    material legal or similarly significant effect\
  \ on any individual\n- summary: Export and sanctions\n  text: Customer agrees that it will not import, export, re-export, transfer or otherwise use the SendBird Platform\n    or SendBird Proprietary Materials in violation of these laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sendbird/eligibility/sendbird-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Sendbird's own page on 2026-11-10.
synthetic: false
tags:
- Customer Service
- Voice
- Video
- Omnichannel
- WhatsApp
- SMS
---

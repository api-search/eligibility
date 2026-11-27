---
api_specs:
- filename: google-chat-spaces-api-openapi.yml
  format: yaml
  label: Google Chat Spaces API
  slug: google-chat-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chat/openapi/google-chat-spaces-api-openapi.yml
- filename: google-chat-media-api-openapi.yml
  format: yaml
  label: Google Chat Chat Media API
  slug: google-chat-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chat/openapi/google-chat-media-api-openapi.yml
- filename: google-chat-users-api-openapi.yml
  format: yaml
  label: Google Chat Chat Users API
  slug: google-chat-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chat/openapi/google-chat-users-api-openapi.yml
- filename: google-chat-custom-emojis-api-openapi.yml
  format: yaml
  label: Google Chat Custom Emojis API
  slug: google-chat-custom-emojis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-chat/openapi/google-chat-custom-emojis-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs ... if ... you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity, then the following applies instead of the paragraph above
    type: government
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: legal age
  restricted_uses:
  - summary: Health data (HIPAA)
    text: If you are (or become) a "covered entity" or "business associate" as defined in HIPAA, you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  - summary: Life-critical or ITAR-controlled use
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
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
name: Google Chat
provenance_date: '2026-11-09'
provider_name: Google Chat
provider_slug: google-chat
slug: google-chat-eligibility
source_date: '2026-11-09'
source_filename: google-chat-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Chat\naid: google-chat\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs ... if ... you are a person barred from using or receiving the APIs under the applicable\n    laws of the United States or other countries including the country in which you are resident or from which you\n    use the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\n- type: government\n  text: If you are\
  \ accepting the Terms on behalf of a United States federal government entity, then the following\n    applies instead of the paragraph above\nrestricted_uses:\n- summary: Health data (HIPAA)\n  text: If you are (or become) a \"covered entity\" or \"business associate\" as defined in HIPAA, you will not use\n    the APIs for any purpose or in any manner involving transmitting protected health information to Google unless\n    you have received prior written consent to such use from Google.\n- summary: Life-critical or ITAR-controlled use\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-chat/eligibility/google-chat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Google Chat's own page on 2026-11-09.
synthetic: false
tags:
- Chat
- Collaboration
- Google
- Google Workspace
- Messaging
- Spaces
---

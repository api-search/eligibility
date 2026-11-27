---
api_specs:
- filename: sobot-agent-api-openapi.yml
  format: yaml
  label: Sobot Agent API
  slug: sobot-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-agent-api-openapi.yml
- filename: sobot-basic-public-service-api-openapi.yml
  format: yaml
  label: Sobot basic-public/service/坐席信息管理 API
  slug: sobot-basic-public-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-basic-public-service-api-openapi.yml
- filename: sobot-exts-api-openapi.yml
  format: yaml
  label: Sobot Exts API
  slug: sobot-exts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-exts-api-openapi.yml
- filename: sobot-user-api-openapi.yml
  format: yaml
  label: Sobot User API
  slug: sobot-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-user-api-openapi.yml
- filename: sobot-openapi-plant-store-api-openapi.yml
  format: yaml
  label: Sobot OpenAPI Plant Store API
  slug: sobot-openapi-plant-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-openapi-plant-store-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services are mainly provided to companies or legal entities
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency calling
    text: the telephony functionality is not intended to support or carry emergency calls to any emergency services
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
name: Sobot
provenance_date: '2026-11-10'
provider_name: Sobot
provider_slug: sobot
slug: sobot-eligibility
source_date: '2026-11-10'
source_filename: sobot-eligibility.yml
source_heading: Eligibility
source_page: https://www.sobot.io/terms-of-services/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sobot\naid: sobot\nurl: https://www.sobot.io/terms-of-services/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services are mainly provided to companies or legal entities\nrestricted_uses:\n- summary: No emergency calling\n  text: the telephony functionality is not intended to support or carry emergency calls to any emergency services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sobot/eligibility/sobot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sobot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Contact Center
- Customer Service
- Live Chat
- Chatbots
- Voice
- Ticketing
- WhatsApp
- Omnichannel
- Communications
- Artificial Intelligence
---

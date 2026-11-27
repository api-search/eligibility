---
api_specs:
- filename: chatway-app-openapi-generated.yml
  format: yaml
  label: Chatway API
  slug: chatway-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatway-app/openapi/_ae-authored/chatway-app-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accessing the Services on behalf of a business, government, or non-profit entity, You must use the actual name of Your organization and have authorization to create their account
    type: business
  minimum_age:
    text: Use of the Service is restricted to those individuals 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Offensive, harassing or sexual content
    text: be offensive, illegal, inappropriate or in any way, or promote racism, bigotry, hatred or physical harm of any kind against any group or individual
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Chatway reserves the right to conduct verification and security procedures in respect of all information provided by You to Chatway.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chatway
provenance_date: '2026-11-09'
provider_name: Chatway
provider_slug: chatway-app
slug: chatway-app-eligibility
source_date: '2026-11-09'
source_filename: chatway-app-eligibility.yml
source_heading: Eligibility
source_page: https://chatway.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatway\naid: chatway-app\nurl: https://chatway.app/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accessing the Services on behalf of a business, government, or non-profit entity, You must use\n    the actual name of Your organization and have authorization to create their account\nrestricted_uses:\n- summary: Offensive, harassing or sexual content\n  text: be offensive, illegal, inappropriate or in any way, or promote racism, bigotry, hatred or physical harm\n    of any kind against any group or individual\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Chatway reserves the right to conduct verification and security procedures in respect of all information\n    provided by You to Chatway.\nminimum_age:\n  value: '18'\n  text: Use of the Service is restricted to those individuals 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/chatway-app/eligibility/chatway-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Chatway's own page on 2026-11-09.
synthetic: false
tags:
- Live Chat
- Artificial Intelligence
- Customer Service
- MCP
- Chatbots
- Company
---

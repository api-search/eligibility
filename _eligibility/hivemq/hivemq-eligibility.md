---
api_specs:
- filename: hivemq-asyncapi.yml
  format: yaml
  label: HiveMQ MQTT over WebSocket
  slug: mqtt-websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/hivemq/asyncapi/hivemq-asyncapi.yml
- filename: hivemq-data-hub-api-openapi.yml
  format: yaml
  label: HiveMQ Data Hub API
  slug: hivemq-data-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-data-hub-api-openapi.yml
- filename: hivemq-management-api-openapi.yml
  format: yaml
  label: HiveMQ Management API
  slug: hivemq-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-management-api-openapi.yml
- filename: hivemq-mqtt-api-openapi.yml
  format: yaml
  label: HiveMQ Mqtt API
  slug: hivemq-mqtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemq/openapi/hivemq-mqtt-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account, you must be at least 18 years old, and you must provide truthful and accurate information about yourself.
    type: individual
  - text: If you access the Sites on behalf of a company, you represent that you are authorized to do so.
    type: business
  minimum_age:
    text: To create an account, you must be at least 18 years old, and you must provide truthful and accurate information about yourself.
    value: '18'
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
name: HiveMQ
provenance_date: '2026-11-09'
provider_name: HiveMQ
provider_slug: hivemq
slug: hivemq-eligibility
source_date: '2026-11-09'
source_filename: hivemq-eligibility.yml
source_heading: Eligibility
source_page: https://www.hivemq.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HiveMQ\naid: hivemq\nurl: https://www.hivemq.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account, you must be at least 18 years old, and you must provide truthful and accurate information\n    about yourself.\n- type: business\n  text: If you access the Sites on behalf of a company, you represent that you are authorized to do so.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To create an account,\
  \ you must be at least 18 years old, and you must provide truthful and accurate information\n    about yourself.\n"
source_yaml_url: https://artifacts.apis.io/hivemq/eligibility/hivemq-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from HiveMQ's own page on 2026-11-09.
synthetic: false
tags:
- MQTT
- IoT
- Messaging
- Message Broker
- Pub/Sub
- WebSocket
- Real-Time
---

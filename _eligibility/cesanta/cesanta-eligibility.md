---
api_specs:
- filename: cesanta-data-api-openapi.yml
  format: yaml
  label: Cesanta Data API
  slug: cesanta-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-data-api-openapi.yml
- filename: cesanta-devices-api-openapi.yml
  format: yaml
  label: Cesanta Devices API
  slug: cesanta-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-devices-api-openapi.yml
- filename: cesanta-keys-api-openapi.yml
  format: yaml
  label: Cesanta Keys API
  slug: cesanta-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-keys-api-openapi.yml
- filename: cesanta-logs-api-openapi.yml
  format: yaml
  label: Cesanta Logs API
  slug: cesanta-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cesanta/openapi/cesanta-logs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms ("Customer")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High risk activities
    text: use the Services for High Risk Activities
  - summary: ITAR-controlled data
    text: process or store any Customer Data that is subject to the International Traffic in Arms Regulations
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
name: Cesanta
provenance_date: '2026-11-09'
provider_name: Cesanta
provider_slug: cesanta
slug: cesanta-eligibility
source_date: '2026-11-09'
source_filename: cesanta-eligibility.yml
source_heading: Eligibility
source_page: https://cesanta.com/Cloud_Platform_ToS.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cesanta\naid: cesanta\nurl: https://cesanta.com/Cloud_Platform_ToS.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High risk activities\n  text: use the Services for High Risk Activities\n- summary: ITAR-controlled data\n  text: process or store any Customer Data that is subject to the International Traffic in Arms Regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/cesanta/eligibility/cesanta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cesanta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Embedded
- Device Management
- Firmware
- OTA
- Networking
- MQTT
---

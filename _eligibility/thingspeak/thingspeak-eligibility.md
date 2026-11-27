---
api_specs:
- filename: thingspeak-channels-api-openapi.yml
  format: yaml
  label: ThingSpeak Channels API
  slug: thingspeak-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingspeak/openapi/thingspeak-channels-api-openapi.yml
- filename: thingspeak-update-api-openapi.yml
  format: yaml
  label: ThingSpeak Update API
  slug: thingspeak-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingspeak/openapi/thingspeak-update-api-openapi.yml
- filename: thingspeak-mqtt-asyncapi.yml
  format: yaml
  label: ThingSpeak MQTT API
  slug: thingspeak-mqtt-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/thingspeak/asyncapi/thingspeak-mqtt-asyncapi.yml
- filename: thingspeak-channels-json-api-openapi.yml
  format: yaml
  label: ThingSpeak Channels.json API
  slug: thingspeak-channels-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingspeak/openapi/thingspeak-channels-json-api-openapi.yml
- filename: thingspeak-talkbacks-api-openapi.yml
  format: yaml
  label: ThingSpeak Talkbacks API
  slug: thingspeak-talkbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingspeak/openapi/thingspeak-talkbacks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All users of a ThingSpeak license should work predominantly in the country that you chose when you purchased the license.
  entity_types:
  - text: Non-commercial users can use ThingSpeak for free subject to the limitations of the free license option.
    type: individual
  - text: All other commercial uses require a standard commercial license.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use
    text: All other commercial uses require a standard commercial license.
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
name: ThingSpeak
provenance_date: '2026-11-10'
provider_name: ThingSpeak
provider_slug: thingspeak
slug: thingspeak-eligibility
source_date: '2026-11-10'
source_filename: thingspeak-eligibility.yml
source_heading: Eligibility
source_page: https://thingspeak.mathworks.com/pages/license_faq
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThingSpeak\naid: thingspeak\nurl: https://thingspeak.mathworks.com/pages/license_faq\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All users of a ThingSpeak license should work predominantly in the country that you chose when you purchased\n    the license.\nentity_types:\n- type: individual\n  text: Non-commercial users can use ThingSpeak for free subject to the limitations of the free license option.\n- type: business\n  text: All other commercial uses require a standard commercial license.\nrestricted_uses:\n- summary: Commercial use\n  text: All other commercial uses require\
  \ a standard commercial license.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thingspeak/eligibility/thingspeak-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ThingSpeak's own page on 2026-11-10.
synthetic: false
tags:
- IoT
- Analytics
- Time Series
- MQTT
- MATLAB
- Sensors
- Telemetry
- Real-Time
---

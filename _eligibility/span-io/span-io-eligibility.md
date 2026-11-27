---
api_specs:
- filename: span-ebus-asyncapi.yml
  format: yaml
  label: SPAN eBus MQTT API
  slug: span-ebus-mqtt-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/span-io/asyncapi/span-ebus-asyncapi.yml
- filename: span-io-auth-api-openapi.yml
  format: yaml
  label: SPAN Auth API
  slug: span-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-auth-api-openapi.yml
- filename: span-io-circuits-api-openapi.yml
  format: yaml
  label: SPAN Circuits API
  slug: span-io-circuits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-circuits-api-openapi.yml
- filename: span-io-islanding-state-api-openapi.yml
  format: yaml
  label: SPAN Islanding State API
  slug: span-io-islanding-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-islanding-state-api-openapi.yml
- filename: span-io-panel-api-openapi.yml
  format: yaml
  label: SPAN Panel API
  slug: span-io-panel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-panel-api-openapi.yml
- filename: span-io-spaces-api-openapi.yml
  format: yaml
  label: SPAN Spaces API
  slug: span-io-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-spaces-api-openapi.yml
- filename: span-io-status-api-openapi.yml
  format: yaml
  label: SPAN Status API
  slug: span-io-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-status-api-openapi.yml
- filename: span-io-storage-api-openapi.yml
  format: yaml
  label: SPAN Storage API
  slug: span-io-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-storage-api-openapi.yml
- filename: span-io-wifi-api-openapi.yml
  format: yaml
  label: SPAN Wifi API
  slug: span-io-wifi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/span-io/openapi/span-io-wifi-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Span controls and operates the Platform from its headquarters in the United States of America
  entity_types:
  - text: you are at least 18 years of age, or if you are under 18 years of age but are at least 13 years old
    type: individual
  - text: if you have completed the required training from Span and have agreed to be an authorized installer
    type: other
  minimum_age:
    text: If you are not at least 13 years old, you may not use the Platform or Products at any time or in any manner
    value: '13'
  restricted_uses:
  - summary: No life-safety or critical use
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE PLATFORM OR PRODUCTS FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Span will send you an email invitation inviting you to create an Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SPAN
provenance_date: '2026-11-10'
provider_name: SPAN
provider_slug: span-io
slug: span-io-eligibility
source_date: '2026-11-10'
source_filename: span-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.span.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SPAN\naid: span-io\nurl: https://www.span.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Span controls and operates the Platform from its headquarters in the United States of America\nentity_types:\n- type: individual\n  text: you are at least 18 years of age, or if you are under 18 years of age but are at least 13 years old\n- type: other\n  text: if you have completed the required training from Span and have agreed to be an authorized installer\nrestricted_uses:\n- summary: No life-safety or critical use\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE PLATFORM\
  \ OR PRODUCTS FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Span will send you an email invitation inviting you to create an Account\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years old, you may not use the Platform or Products at any time or in any manner\n"
source_yaml_url: https://artifacts.apis.io/span-io/eligibility/span-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from SPAN's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Home Energy
- Electrification
- Smart Panel
- Electrical Panel
- Home Automation
- Solar
- Energy Storage
- EV Charging
- Grid
- Islanding
- Backup Power
- Demand Response
- IoT
- MQTT
- Homie
- Electrification Bus
- On-Premises
- Real-Time
---

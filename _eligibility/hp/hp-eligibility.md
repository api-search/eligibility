---
api_specs:
- filename: hp-analytics-api-openapi.yml
  format: yaml
  label: HP Analytics API
  slug: hp-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-analytics-api-openapi.yml
- filename: hp-devices-api-openapi.yml
  format: yaml
  label: HP Devices API
  slug: hp-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-devices-api-openapi.yml
- filename: hp-incidents-api-openapi.yml
  format: yaml
  label: HP Incidents API
  slug: hp-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hp/openapi/hp-incidents-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Developer must comply with all domestic and international laws and regulations, including United States export laws and regulations, that are applicable to its use of the Services.
  entity_types:
  - text: If You are using the Services on behalf of your employer, you hereby represent that you are authorized by your employer to bind it to the terms of this Agreement.
    type: business
  - text: If You are a consumer, in the event required by applicable law in your location, any disputes arising in connection with the Agreement may be governed by the laws and the courts of your country and locality where You reside.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No deep packet inspection or network surveillance
    text: (5) use the API in conjunction with deep packet inspection and/or any form of network surveillance technology; to monitor Internet and/or other telecommunications traffic
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Developer must register to establish an account (your “Account”).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HP
provenance_date: '2026-11-09'
provider_name: HP
provider_slug: hp
slug: hp-eligibility
source_date: '2026-11-09'
source_filename: hp-eligibility.yml
source_heading: Eligibility
source_page: https://developers.hp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HP\naid: hp\nurl: https://developers.hp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Developer must comply with all domestic and international laws and regulations, including United States\n    export laws and regulations, that are applicable to its use of the Services.\nentity_types:\n- type: business\n  text: If You are using the Services on behalf of your employer, you hereby represent that you are authorized by\n    your employer to bind it to the terms of this Agreement.\n- type: individual\n  text: If You are a consumer, in the event required by applicable law\
  \ in your location, any disputes arising in\n    connection with the Agreement may be governed by the laws and the courts of your country and locality where\n    You reside.\nrestricted_uses:\n- summary: No deep packet inspection or network surveillance\n  text: (5) use the API in conjunction with deep packet inspection and/or any form of network surveillance technology;\n    to monitor Internet and/or other telecommunications traffic\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Developer must register to establish an account (your “Account”).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hp/eligibility/hp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from HP's own page on 2026-11-09.
synthetic: false
tags:
- Computer Hardware
- Device Management
- Printing
- Technology
- Fortune 100
---

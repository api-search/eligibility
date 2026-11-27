---
api_specs:
- filename: afero-authentication-api-openapi.yml
  format: yaml
  label: Afero Cloud Authentication API
  slug: authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afero/openapi/afero-authentication-api-openapi.yml
- filename: afero-users-api-openapi.yml
  format: yaml
  label: Afero Cloud Users API
  slug: users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afero/openapi/afero-users-api-openapi.yml
- filename: afero-devices-api-openapi.yml
  format: yaml
  label: Afero Cloud Devices API
  slug: devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afero/openapi/afero-devices-api-openapi.yml
- filename: afero-ota-api-openapi.yml
  format: yaml
  label: Afero Cloud OTA Firmware API
  slug: ota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afero/openapi/afero-ota-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Developer represents and warrants that (y) it is not located in a country that is subject to a U.S. Government embargo
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Excluded high-risk uses
    text: Developer will not use the Afero Platform for any Excluded Uses.
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
name: Afero
provenance_date: '2026-11-09'
provider_name: Afero
provider_slug: afero
slug: afero-eligibility
source_date: '2026-11-09'
source_filename: afero-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.afero.io/tos/developer/v1/developer.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Afero\naid: afero\nurl: https://cdn.afero.io/tos/developer/v1/developer.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Developer represents and warrants that (y) it is not located in a country that is subject to a U.S. Government\n    embargo\nentity_types: []\nrestricted_uses:\n- summary: Excluded high-risk uses\n  text: Developer will not use the Afero Platform for any Excluded Uses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/afero/eligibility/afero-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Afero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- IoT Platform
- Connected Devices
- Device Management
- Firmware
- Over-the-Air Updates
- Bluetooth Low Energy
- Embedded Security
- Hardware
---

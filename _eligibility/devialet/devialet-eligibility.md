---
api_specs:
- filename: devialet-audio-settings-api-openapi.yml
  format: yaml
  label: Devialet Audio Settings API
  slug: devialet-audio-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-audio-settings-api-openapi.yml
- filename: devialet-devices-api-openapi.yml
  format: yaml
  label: Devialet Devices API
  slug: devialet-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-devices-api-openapi.yml
- filename: devialet-groups-api-openapi.yml
  format: yaml
  label: Devialet Groups API
  slug: devialet-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-groups-api-openapi.yml
- filename: devialet-playback-api-openapi.yml
  format: yaml
  label: Devialet Playback API
  slug: devialet-playback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-playback-api-openapi.yml
- filename: devialet-sound-control-api-openapi.yml
  format: yaml
  label: Devialet Sound Control API
  slug: devialet-sound-control-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-sound-control-api-openapi.yml
- filename: devialet-systems-api-openapi.yml
  format: yaml
  label: Devialet Systems API
  slug: devialet-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/devialet/openapi/devialet-systems-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Devialet only accepts orders for delivery in countries where Devialet sells on its Website.
  entity_types:
  - text: The Customer is an end consumer, a person (and not a company)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional use, resale or distribution
    text: Any purchase made for the purpose of professional use, resale or distribution is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Devialet may ask the Customer for additional information and documents in the context of executing, managing the order or disputes with the Customer (for example a copy of an identity card, a sworn declaration, a copy of a police report).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Devialet
provenance_date: '2026-11-09'
provider_name: Devialet
provider_slug: devialet
slug: devialet-eligibility
source_date: '2026-11-09'
source_filename: devialet-eligibility.yml
source_heading: Eligibility
source_page: https://www.devialet.com/en-eu/legal/general-terms-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Devialet\naid: devialet\nurl: https://www.devialet.com/en-eu/legal/general-terms-of-sale/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Devialet only accepts orders for delivery in countries where Devialet sells on its Website.\nentity_types:\n- type: individual\n  text: The Customer is an end consumer, a person (and not a company)\nrestricted_uses:\n- summary: Professional use, resale or distribution\n  text: Any purchase made for the purpose of professional use, resale or distribution is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Devialet may ask the Customer for additional information and documents in the context of executing, managing\n    the order or disputes with the Customer (for example a copy of an identity card, a sworn declaration, a copy\n    of a police report).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/devialet/eligibility/devialet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Devialet's own page on 2026-11-09.
synthetic: false
tags:
- Audio
- Consumer Electronics
- Smart Speakers
- Home Automation
- Custom Installation
- Device Control
- Local Network API
- IoT
- Hardware
- Music
- France
---

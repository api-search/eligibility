---
api_specs:
- filename: halo-h5pc-api-openapi.yml
  format: yaml
  label: Halo H5pc API
  slug: halo-h5pc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-h5pc-api-openapi.yml
- filename: halo-h5-api-openapi.yml
  format: yaml
  label: Halo H5 API
  slug: halo-h5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-h5-api-openapi.yml
- filename: halo-hw2-api-openapi.yml
  format: yaml
  label: Halo Hw2 API
  slug: halo-hw2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-hw2-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to access and use Game Data and API, you must register for an API Key.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted advertising categories
    text: 'Advertisements for the following kinds of products or services, or with the following kinds of content, are restricted: alcohol; tobacco; firearms; illegal gambling sites or services; dating or personals sites or services; adult products or services; debt services; online pharmacies; religion or religious content; political campaigns or issues'
  - summary: No competitive gaming devices
    text: be developed or distributed for any competitive gaming device or service, including without limitation PlayStation 3 or 4; Nintendo Wii, WiiU, DS or 3DS.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Microsoft is not obligated to grant you an API Key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Halo
provenance_date: '2026-11-09'
provider_name: Halo
provider_slug: halo
slug: halo-eligibility
source_date: '2026-11-09'
source_filename: halo-eligibility.yml
source_heading: Eligibility
source_page: https://developer.haloapi.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halo\naid: halo\nurl: https://developer.haloapi.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: In order to access and use Game Data and API, you must register for an API Key.\nrestricted_uses:\n- summary: Restricted advertising categories\n  text: 'Advertisements for the following kinds of products or services, or with the following kinds of content,\n    are restricted: alcohol; tobacco; firearms; illegal gambling sites or services; dating or personals sites or\n    services; adult products or services; debt services;\
  \ online pharmacies; religion or religious content; political\n    campaigns or issues'\n- summary: No competitive gaming devices\n  text: be developed or distributed for any competitive gaming device or service, including without limitation PlayStation\n    3 or 4; Nintendo Wii, WiiU, DS or 3DS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Microsoft is not obligated to grant you an API Key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halo/eligibility/halo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Halo's own page on 2026-11-09.
synthetic: false
tags:
- Game Data
- Gaming
- Halo
- Microsoft
- Player Statistics
- Public APIs
- Video Games
- Xbox
---

---
api_specs:
- filename: carhandshake-com-openapi-generated.yml
  format: yaml
  label: Car Handshake API
  slug: carhandshake-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carhandshake-com/openapi/_ae-authored/carhandshake-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Car Handshake supports the United States and supported Canadian regions outside Quebec, but not every location has inventory
  entity_types:
  - text: You must be at least 13 to use Car Handshake.
    type: individual
  minimum_age:
    text: You must be at least 13 to use Car Handshake.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Read-only inventory and dealership searches do not require a Car Handshake account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Car Handshake
provenance_date: '2026-11-09'
provider_name: Car Handshake
provider_slug: carhandshake-com
slug: carhandshake-com-eligibility
source_date: '2026-11-09'
source_filename: carhandshake-com-eligibility.yml
source_heading: Eligibility
source_page: https://carhandshake.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Car Handshake\naid: carhandshake-com\nurl: https://carhandshake.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Car Handshake supports the United States and supported Canadian regions outside Quebec, but not every location\n    has inventory\nentity_types:\n- type: individual\n  text: You must be at least 13 to use Car Handshake.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Read-only inventory and dealership searches do not require a Car Handshake account.\nminimum_age:\n  value: '13'\n  text: You must be\
  \ at least 13 to use Car Handshake.\n"
source_yaml_url: https://artifacts.apis.io/carhandshake-com/eligibility/carhandshake-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Car Handshake's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Car
- Marketplace
- Automotive
---

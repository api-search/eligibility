---
api_specs:
- filename: chargy-locations-api-openapi.yml
  format: yaml
  label: char.gy Locations API
  slug: chargy-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chargy/openapi/chargy-locations-api-openapi.yml
- filename: chargy-tariffs-api-openapi.yml
  format: yaml
  label: char.gy Tariffs API
  slug: chargy-tariffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chargy/openapi/chargy-tariffs-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: IF YOU LIVE IN (OR YOUR PRINCIPAL PLACE OF BUSINESS IS IN) THE UNITED STATES THE FOLLOWING SHALL GOVERN TO THE FULLEST EXTENT ALLOWED BY APPLICABLE LAW
  entity_types:
  - text: These Terms are for household and consumer use
    type: individual
  - text: if you wish to use the Service on behalf of an enterprise, organisation or business (except as a sole trader), please contact us at hello@char.gy.
    type: business
  minimum_age:
    text: To use the Service, you must be 17 of age or older.
    value: '17'
  restricted_uses:
  - summary: Commercial vehicles
    text: Our standard Service is not available for commercial vehicles and these Terms are not applicable to commercial users.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Service you will need to register with us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: char.gy
provenance_date: '2026-11-09'
provider_name: char.gy
provider_slug: chargy
slug: chargy-eligibility
source_date: '2026-11-09'
source_filename: chargy-eligibility.yml
source_heading: Eligibility
source_page: https://char.gy/us/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: char.gy\naid: chargy\nurl: https://char.gy/us/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: IF YOU LIVE IN (OR YOUR PRINCIPAL PLACE OF BUSINESS IS IN) THE UNITED STATES THE FOLLOWING SHALL GOVERN\n    TO THE FULLEST EXTENT ALLOWED BY APPLICABLE LAW\nentity_types:\n- type: individual\n  text: These Terms are for household and consumer use\n- type: business\n  text: if you wish to use the Service on behalf of an enterprise, organisation or business (except as a sole trader),\n    please contact us at hello@char.gy.\nrestricted_uses:\n- summary: Commercial vehicles\n\
  \  text: Our standard Service is not available for commercial vehicles and these Terms are not applicable to commercial\n    users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the Service you will need to register with us.\nminimum_age:\n  value: '17'\n  text: To use the Service, you must be 17 of age or older.\n"
source_yaml_url: https://artifacts.apis.io/chargy/eligibility/chargy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from char.gy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United Kingdom
- EV Charging
- Electricity
- Utilities
- OCPI
- Charge Point Operator
- Open Data
- Roaming
- Tariffs
- Mobility
- Electrification
---

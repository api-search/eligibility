---
api_specs:
- filename: flyitalyadsb-live-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Live API
  slug: flyitalyadsb-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-live-api-openapi.yml
- filename: flyitalyadsb-account-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Account API
  slug: flyitalyadsb-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-account-api-openapi.yml
- filename: flyitalyadsb-events-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Events API
  slug: flyitalyadsb-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-events-api-openapi.yml
- filename: flyitalyadsb-flights-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Flights API
  slug: flyitalyadsb-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-flights-api-openapi.yml
- filename: flyitalyadsb-history-api-openapi.yml
  format: yaml
  label: FlyItalyADSB History API
  slug: flyitalyadsb-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-history-api-openapi.yml
- filename: flyitalyadsb-keys-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Keys API
  slug: flyitalyadsb-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-keys-api-openapi.yml
- filename: flyitalyadsb-live-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Live API
  slug: flyitalyadsb-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-live-api-openapi.yml
- filename: flyitalyadsb-watch-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Watch API
  slug: flyitalyadsb-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-watch-api-openapi.yml
- filename: flyitalyadsb-webhooks-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Webhooks API
  slug: flyitalyadsb-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To businesses in the European Union and the United Kingdom that give a valid VAT number, and to customers in the United States, they are sold directly by Nesso Labs S.r.l.
  entity_types:
  - text: To businesses in the European Union and the United Kingdom that give a valid VAT number
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety of life, ATC or navigation
    text: use the data for safety of life, air traffic control or navigation
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
name: FlyItalyADSB
provenance_date: '2026-11-09'
provider_name: FlyItalyADSB
provider_slug: flyitalyadsb
slug: flyitalyadsb-eligibility
source_date: '2026-11-09'
source_filename: flyitalyadsb-eligibility.yml
source_heading: Eligibility
source_page: https://flyitalyadsb.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlyItalyADSB\naid: flyitalyadsb\nurl: https://flyitalyadsb.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To businesses in the European Union and the United Kingdom that give a valid VAT number, and to customers\n    in the United States, they are sold directly by Nesso Labs S.r.l.\nentity_types:\n- type: business\n  text: To businesses in the European Union and the United Kingdom that give a valid VAT number\nrestricted_uses:\n- summary: Safety of life, ATC or navigation\n  text: use the data for safety of life, air traffic control or navigation\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flyitalyadsb/eligibility/flyitalyadsb-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from FlyItalyADSB's own page on 2026-11-09.
synthetic: false
tags:
- ADS-B
- MLAT
- Aviation
- Flight Tracking
- Open Data
---

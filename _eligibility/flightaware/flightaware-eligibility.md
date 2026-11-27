---
api_specs:
- filename: flightaware-airports-api-openapi.yml
  format: yaml
  label: FlightAware Airports API
  slug: flightaware-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-airports-api-openapi.yml
- filename: flightaware-alerts-api-openapi.yml
  format: yaml
  label: FlightAware Alerts API
  slug: flightaware-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-alerts-api-openapi.yml
- filename: flightaware-flights-api-openapi.yml
  format: yaml
  label: FlightAware Flights API
  slug: flightaware-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-flights-api-openapi.yml
- filename: flightaware-foresight-api-openapi.yml
  format: yaml
  label: FlightAware Foresight API
  slug: flightaware-foresight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-foresight-api-openapi.yml
- filename: flightaware-history-api-openapi.yml
  format: yaml
  label: FlightAware History API
  slug: flightaware-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-history-api-openapi.yml
- filename: flightaware-miscellaneous-api-openapi.yml
  format: yaml
  label: FlightAware Miscellaneous API
  slug: flightaware-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-miscellaneous-api-openapi.yml
- filename: flightaware-operators-api-openapi.yml
  format: yaml
  label: FlightAware Operators API
  slug: flightaware-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-operators-api-openapi.yml
- filename: flightaware-account-api-openapi.yml
  format: yaml
  label: FlightAware Account API
  slug: flightaware-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-account-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to this Website from territories where this Website's contents are illegal is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical or operational aviation use
    text: You may not use the Website for any aviation, commercial, operational, law enforcement, judicial, or safety-critical activity that relies on the availability, validity, or accuracy of FlightAware data.
  - summary: Betting, wagering or prediction markets
    text: in connection with any betting, wagering, gambling, prediction market, event contract, or similar platform or product that enables participants to place, trade, or settle positions based on the occurrence or outcome of future events.
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
name: FlightAware
provenance_date: '2026-11-09'
provider_name: FlightAware
provider_slug: flightaware
slug: flightaware-eligibility
source_date: '2026-11-09'
source_filename: flightaware-eligibility.yml
source_heading: Eligibility
source_page: https://www.flightaware.com/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlightAware\naid: flightaware\nurl: https://www.flightaware.com/about/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to this Website from territories where this Website's contents are illegal is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Safety-critical or operational aviation use\n  text: You may not use the Website for any aviation, commercial, operational, law enforcement, judicial, or safety-critical\n    activity that relies on the availability, validity, or accuracy of FlightAware data.\n- summary: Betting, wagering or prediction markets\n\
  \  text: in connection with any betting, wagering, gambling, prediction market, event contract, or similar platform\n    or product that enables participants to place, trade, or settle positions based on the occurrence or outcome\n    of future events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flightaware/eligibility/flightaware-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from FlightAware's own page on 2026-11-09.
synthetic: false
tags:
- Aviation
- Flights
- Flight Tracking
- Mapping
- Radar
- Satellite
- Traffic Control
---

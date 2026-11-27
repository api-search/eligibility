---
api_specs:
- filename: marine-traffic-ais-api-api-openapi.yml
  format: yaml
  label: MarineTraffic AIS API
  slug: marine-traffic-ais-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-ais-api-api-openapi.yml
- filename: marine-traffic-balances-api-openapi.yml
  format: yaml
  label: MarineTraffic Balances API
  slug: marine-traffic-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-balances-api-openapi.yml
- filename: marine-traffic-fleets-api-openapi.yml
  format: yaml
  label: MarineTraffic Fleets API
  slug: marine-traffic-fleets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-fleets-api-openapi.yml
- filename: marine-traffic-passage-plans-api-openapi.yml
  format: yaml
  label: MarineTraffic Passage Plans API
  slug: marine-traffic-passage-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-passage-plans-api-openapi.yml
- filename: marine-traffic-port-events-api-openapi.yml
  format: yaml
  label: MarineTraffic Port Events API
  slug: marine-traffic-port-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-port-events-api-openapi.yml
- filename: marine-traffic-ports-information-api-openapi.yml
  format: yaml
  label: MarineTraffic Ports Information API
  slug: marine-traffic-ports-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-ports-information-api-openapi.yml
- filename: marine-traffic-reverse-geocoding-api-openapi.yml
  format: yaml
  label: MarineTraffic Reverse Geocoding API
  slug: marine-traffic-reverse-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-reverse-geocoding-api-openapi.yml
- filename: marine-traffic-routing-information-api-openapi.yml
  format: yaml
  label: MarineTraffic Routing Information API
  slug: marine-traffic-routing-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-routing-information-api-openapi.yml
- filename: marine-traffic-search-vessel-api-openapi.yml
  format: yaml
  label: MarineTraffic Search Vessel API
  slug: marine-traffic-search-vessel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-search-vessel-api-openapi.yml
- filename: marine-traffic-single-vessel-events-api-openapi.yml
  format: yaml
  label: MarineTraffic Single Vessel Events API
  slug: marine-traffic-single-vessel-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-single-vessel-events-api-openapi.yml
- filename: marine-traffic-vessel-historical-track-api-openapi.yml
  format: yaml
  label: MarineTraffic Vessel Historical Track API
  slug: marine-traffic-vessel-historical-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-vessel-historical-track-api-openapi.yml
- filename: marine-traffic-vessel-information-api-openapi.yml
  format: yaml
  label: MarineTraffic Vessel Information API
  slug: marine-traffic-vessel-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-vessel-information-api-openapi.yml
- filename: marine-traffic-vessel-positions-legacy-api-api-openapi.yml
  format: yaml
  label: MarineTraffic Vessel Positions (Legacy API) API
  slug: marine-traffic-vessel-positions-legacy-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-vessel-positions-legacy-api-api-openapi.yml
- filename: marine-traffic-voyage-information-api-openapi.yml
  format: yaml
  label: MarineTraffic Voyage Information API
  slug: marine-traffic-voyage-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marine-traffic/openapi/marine-traffic-voyage-information-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned parties and countries
    text: You may not use, promote or sell any products or services which contain the Data to any individual or entity, which is owned, controlled or associated with a proscribed country (or to any sanctioned country)
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
name: MarineTraffic
provenance_date: '2026-11-10'
provider_name: MarineTraffic
provider_slug: marine-traffic
slug: marine-traffic-eligibility
source_date: '2026-11-10'
source_filename: marine-traffic-eligibility.yml
source_heading: Eligibility
source_page: https://www.kpler.com/company/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MarineTraffic\naid: marine-traffic\nurl: https://www.kpler.com/company/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned parties and countries\n  text: You may not use, promote or sell any products or services which contain the Data to any individual or entity,\n    which is owned, controlled or associated with a proscribed country (or to any sanctioned country)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marine-traffic/eligibility/marine-traffic-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from MarineTraffic's own page on 2026-11-10.
synthetic: false
tags:
- AIS
- Maritime
- Vessel Tracking
- Shipping
- Ports
- Voyage Forecasting
- Geospatial
- Kpler
---

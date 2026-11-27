---
api_specs:
- filename: sound-transit-agencies-api-openapi.yml
  format: yaml
  label: Sound Transit Agencies API
  slug: sound-transit-agencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-agencies-api-openapi.yml
- filename: sound-transit-arrivals-and-departures-api-openapi.yml
  format: yaml
  label: Sound Transit Arrivals And Departures API
  slug: sound-transit-arrivals-and-departures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-arrivals-and-departures-api-openapi.yml
- filename: sound-transit-routes-api-openapi.yml
  format: yaml
  label: Sound Transit Routes API
  slug: sound-transit-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-routes-api-openapi.yml
- filename: sound-transit-stops-api-openapi.yml
  format: yaml
  label: Sound Transit Stops API
  slug: sound-transit-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-stops-api-openapi.yml
- filename: sound-transit-system-api-openapi.yml
  format: yaml
  label: Sound Transit System API
  slug: sound-transit-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-system-api-openapi.yml
- filename: sound-transit-trips-api-openapi.yml
  format: yaml
  label: Sound Transit Trips API
  slug: sound-transit-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-trips-api-openapi.yml
- filename: sound-transit-vehicles-api-openapi.yml
  format: yaml
  label: Sound Transit Vehicles API
  slug: sound-transit-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sound-transit/openapi/sound-transit-vehicles-api-openapi.yml
claim_count: 3
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
  - summary: Malicious or criminal intent
    text: Malicious intent
  - summary: Intent to commit a crime
    text: Intent to commit a crime
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using the Data or completing the registration required to access the data, you agree to be bound by all of the terms and conditions set forth in these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sound Transit
provenance_date: '2026-11-10'
provider_name: Sound Transit
provider_slug: sound-transit
slug: sound-transit-eligibility
source_date: '2026-11-10'
source_filename: sound-transit-eligibility.yml
source_heading: Eligibility
source_page: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/transit-data-terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sound Transit\naid: sound-transit\nurl: https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/transit-data-terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Malicious or criminal intent\n  text: Malicious intent\n- summary: Intent to commit a crime\n  text: Intent to commit a crime\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By using the Data or completing the registration required to access the data, you agree to be bound by all\n    of the terms and conditions\
  \ set forth in these Terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sound-transit/eligibility/sound-transit-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Sound Transit's own page on 2026-11-10.
synthetic: false
tags:
- Transit
- Transportation
- GTFS
- Real-Time
- Public Transit
- Government
- Seattle
---

---
api_specs:
- filename: opensky-flights-api-openapi.yml
  format: yaml
  label: OpenSky Network Flights API
  slug: opensky-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-flights-api-openapi.yml
- filename: opensky-state-vectors-api-openapi.yml
  format: yaml
  label: OpenSky Network State Vectors API
  slug: opensky-state-vectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-state-vectors-api-openapi.yml
- filename: opensky-tracks-api-openapi.yml
  format: yaml
  label: OpenSky Network Tracks API
  slug: opensky-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensky/openapi/opensky-tracks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: OpenSky Network, an non-profit association pursuant to Article 60 ff. of the Swiss Civil Code
    type: nonprofit
  - text: Any use by a for-profit or commercial entity requires written permission and a license granted by the OpenSky Network. This includes any and all government and military contractors.
    type: business
  - text: Government entities may obtain an exemption at the discretion of the OpenSky Network.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Operational REST API use
    text: Use of the REST API in any operational capacity — including but not limited to integration into a live product, service, or automated system — requires a written license from OpenSky Network, regardless of the entity's non-profit status.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: This AGREEMENT shall become effective as of the date of approval by OpenSky Network.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OpenSky Network
provenance_date: '2026-11-10'
provider_name: OpenSky Network
provider_slug: opensky
slug: opensky-eligibility
source_date: '2026-11-10'
source_filename: opensky-eligibility.yml
source_heading: Eligibility
source_page: https://opensky-network.org/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenSky Network\naid: opensky\nurl: https://opensky-network.org/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: OpenSky Network, an non-profit association pursuant to Article 60 ff. of the Swiss Civil Code\n- type: business\n  text: Any use by a for-profit or commercial entity requires written permission and a license granted by the OpenSky\n    Network. This includes any and all government and military contractors.\n- type: government\n  text: Government entities may obtain an exemption at the discretion of the OpenSky\
  \ Network.\nrestricted_uses:\n- summary: Operational REST API use\n  text: Use of the REST API in any operational capacity — including but not limited to integration into a live product,\n    service, or automated system — requires a written license from OpenSky Network, regardless of the entity's non-profit\n    status.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: This AGREEMENT shall become effective as of the date of approval by OpenSky Network.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opensky/eligibility/opensky-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from OpenSky Network's own page on 2026-11-10.
synthetic: false
tags:
- Aviation
- Flight Tracking
- ADS-B
- Aircraft
- Airport
- Real-Time
- Historical Data
---

---
api_specs:
- filename: flightpowers-com-account-api-openapi.yml
  format: yaml
  label: flightpowers-com Account API
  slug: flightpowers-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-account-api-openapi.yml
- filename: flightpowers-com-flights-api-openapi.yml
  format: yaml
  label: flightpowers-com Flights API
  slug: flightpowers-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-flights-api-openapi.yml
- filename: flightpowers-com-hotels-api-openapi.yml
  format: yaml
  label: flightpowers-com Hotels API
  slug: flightpowers-com-hotels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-hotels-api-openapi.yml
- filename: flightpowers-com-verify-api-openapi.yml
  format: yaml
  label: flightpowers-com Verify API
  slug: flightpowers-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-verify-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: This site has no signup, no login, and no account system.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: flightpowers-com
provenance_date: '2026-11-09'
provider_name: flightpowers-com
provider_slug: flightpowers-com
slug: flightpowers-com-eligibility
source_date: '2026-11-09'
source_filename: flightpowers-com-eligibility.yml
source_heading: Eligibility
source_page: https://flightpowers.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flightpowers-com\naid: flightpowers-com\nurl: https://flightpowers.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: This site has no signup, no login, and no account system.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flightpowers-com/eligibility/flightpowers-com-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from flightpowers-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Data
- Flights
- Hotels
---

---
api_specs:
- filename: country-state-city-api-cities-api-openapi.yml
  format: yaml
  label: Country State City API Cities API
  slug: country-state-city-api-cities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/country-state-city-api/openapi/country-state-city-api-cities-api-openapi.yml
- filename: country-state-city-api-countries-api-openapi.yml
  format: yaml
  label: Country State City API Countries API
  slug: country-state-city-api-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/country-state-city-api/openapi/country-state-city-api-countries-api-openapi.yml
- filename: country-state-city-api-states-api-openapi.yml
  format: yaml
  label: Country State City API States API
  slug: country-state-city-api-states-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/country-state-city-api/openapi/country-state-city-api-states-api-openapi.yml
claim_count: 2
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
  - summary: Illegal purposes
    text: Use the Service for illegal purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account by providing a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Country State City API
provenance_date: '2026-11-09'
provider_name: Country State City API
provider_slug: country-state-city-api
slug: country-state-city-api-eligibility
source_date: '2026-11-09'
source_filename: country-state-city-api-eligibility.yml
source_heading: Eligibility
source_page: https://app.countrystatecity.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Country State City API\naid: country-state-city-api\nurl: https://app.countrystatecity.in/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account by providing a valid email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/country-state-city-api/eligibility/country-state-city-api-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Country State City API's own page on 2026-11-09.
synthetic: false
tags:
- Capital
- Cities
- Countries
- Currency
- Geography
- Geolocation
- ISO 3166
- JSON
- Phone Codes
- Provinces
- Reference Data
- Regions
- States
- Timezone
---

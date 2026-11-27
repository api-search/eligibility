---
api_specs:
- filename: twitterapi-io-oapi-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Oapi API
  slug: twitterapi-io-oapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-oapi-api-openapi.yml
- filename: twitterapi-io-plants-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Plants API
  slug: twitterapi-io-plants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-plants-api-openapi.yml
- filename: twitterapi-io-twitter-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Twitter API
  slug: twitterapi-io-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-twitter-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: We prohibit use of the Service from embargoed regions (including Cuba, Iran, North Korea, Syria, Crimea, Donetsk, and Luhansk).
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into binding contracts.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into binding contracts.
    value: '18'
  restricted_uses:
  - summary: Personal data misuse
    text: Collect, sell, or distribute personal data for harassment, stalking, doxxing, or discriminatory targeting.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TwitterAPI.io
provenance_date: '2026-11-10'
provider_name: TwitterAPI.io
provider_slug: twitterapi-io
slug: twitterapi-io-eligibility
source_date: '2026-11-10'
source_filename: twitterapi-io-eligibility.yml
source_heading: Eligibility
source_page: https://twitterapi.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TwitterAPI.io\naid: twitterapi-io\nurl: https://twitterapi.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: We prohibit use of the Service from embargoed regions (including Cuba, Iran, North Korea, Syria, Crimea,\n    Donetsk, and Luhansk).\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into binding contracts.\nrestricted_uses:\n- summary: Personal data misuse\n  text: Collect, sell, or distribute personal data for harassment, stalking, doxxing, or discriminatory targeting.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/twitterapi-io/eligibility/twitterapi-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from TwitterAPI.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- xAPI
- Data Provider
- REST
- Third Party
---
